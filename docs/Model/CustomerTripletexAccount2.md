# CustomerTripletexAccount2

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**administrator** | [**\Swagger\Client\Model\Employee**](Employee.md) |  | [optional] 
**customer_id** | **int** | The customer id to an already created customer to create a Tripletex account for. | [optional] 
**account_type** | **string** |  | 
**modules** | [**\Swagger\Client\Model\SalesModuleDTO[]**](SalesModuleDTO.md) |  | 
**type** | **string** |  | 
**send_emails** | **bool** | Should the emails normally sent during creation be sent in this case? | [optional] [default to false]
**auto_validate_user_login** | **bool** | Should the user be automatically validated? | [optional] [default to false]
**create_api_token** | **bool** | Creates a token for the admin user. The accounting office could also use their tokens so you might not need this. | [optional] [default to false]
**send_invoice_to_customer** | **bool** | Should the invoices for this account be sent to the customer? | [optional] [default to false]
**customer_invoice_email** | **string** | The address to send the invoice to at the customer. | [optional] 
**number_of_employees** | **int** | The number of employees in the customer company. Is used for calculating prices and setting some default settings, i.e. approval settings for timesheet. | [optional] 
**administrator_password** | **string** | The password of the administrator user. | [optional] 
**chart_of_accounts_type** | **string** | The chart of accounts to use for the new company | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

