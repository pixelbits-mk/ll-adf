az ad sp create-for-rbac ^
  --name "github-actions-sp" ^
  --role "Contributor" ^
  --scopes /subscriptions/ab98b12f-042b-45fa-8c23-0286079a0117 ^
  --sdk-auth
  
AZURE_CREDENTIALS
{
  "clientId": "88292e4e-6323-4193-bd08-68639e69b392",
  "clientSecret": "eNW8Q~52lEpzMqbgxCeIqAF494RmxTjC5q-awc4s",
  "subscriptionId": "ab98b12f-042b-45fa-8c23-0286079a0117",
  "tenantId": "df6b18d9-22de-4a09-841c-49b4f8fe9cfe",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}