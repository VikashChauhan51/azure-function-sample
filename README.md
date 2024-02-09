# azure-function-sample
azure, azure functions, durable functions


## Local debugging
Add `local.settings.json` file at root level of function project.

```Json
{
    "IsEncrypted": false,
    "Values": {
        "AzureWebJobsStorage": "UseDevelopmentStorage=true",
        "FUNCTIONS_WORKER_RUNTIME": "dotnet-isolated",
         "StorageConnectionString": "UseDevelopmentStorage=true"
    }
}
```