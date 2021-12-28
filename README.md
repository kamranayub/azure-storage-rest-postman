# Azure Storage Postman Collection

![screenshot](https://user-images.githubusercontent.com/563819/46709351-f1015080-cc08-11e8-961b-66078a744fe8.png)

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
   - _azure_storage_account_ - Your Azure Storage account name
   - _azure_storage_key_ - Your secret Storage key
   - _azure_storage_container_ - Your blob storage container name

The first two variable values can be found in the Azure Portal for your storage account (navigate to the container in question, then select _Access keys_ on the left hand menu and tap _Show keys_).

The _azure_storage_container_ variable specifies name of your blob storage container to be used in Upload/Get/Delete blob requests. The rest of the variables will be filled in automatically.

See [Azure Storage REST API docs](https://docs.microsoft.com/en-us/rest/api/storageservices/)
