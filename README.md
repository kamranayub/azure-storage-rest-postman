# Azure Storage Postman Collection

I've built a [Postman](https://getpostman.com/apps) collection that can automatically generate the appropriate `Authorization` HTTP header with signature to sign requests. Used for my Pluralsight course, [Configuring CORS Access with Storage](https://github.com/kamranayub/pluralsight-azure-cors-storage)

To use the collection:

1. Clone or download the JSON file
1. Open the Postman app
1. Click the orange "Import" button
1. Choose the file
1. Import it
1. Edit the new collection using the "..." menu
1. Go to the **Variables** tab
1. Fill in the variables for:
   - *azure_storage_account* - Your Azure Storage account name
   - *azure_storage_key* - Your secret Storage key

These two variable values can be found in the Azure Portal for your storage account. The rest of the variables will be filled in automatically.

See [Azure Storage REST API docs](https://docs.microsoft.com/en-us/rest/api/storageservices/)