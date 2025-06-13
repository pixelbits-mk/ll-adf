
az deployment group create --name deploy-adf-qa --resource-group test --template-file dev-ll-adf/ARMTemplateForFactory.json --parameters @config/qa.parameters.json