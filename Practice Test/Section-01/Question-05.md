## MetaData
Question Type : Dropdown

## Question
You are an Azure administrator and you need to deploy several resources into the RG1 resource group through an ARM template. For this, you use the following files both stored locally:<br> • Template.json <br>• Template.parameters.json<br> Please complete the PowerShell command below <br>[[DropDown 1]]_[[DropDown 2]] RG1 -[[DropDown 3]] Template.json -[[DropDown 4]]

## Options
DropDown 1 : New-AzResourceGroupDeployment 
DropDown 1 : New-AzManagementGroupDeployment 
DropDown 2 : Name
DropDown 2 : ResourceGroupName 
DropDown 3 : TemplateUri
DropDown 3 : TemplateName
DropDown 4 : TemplateParameterUri
DropDown 4 : TemplateParameterFile

## Answers
DropDown 1 : New-AzResourceGroupDeployment : 3
DropDown 2 : ResourceGroupName : 3
DropDown 3 : TemplateName : 3
DropDown 4 : TemplateParameterFile : 3

## Reference Links
https://learn.microsoft.com/en-us/powershell/module/az.resources/new-azresourcegroupdeployment

## Explanation
New-AzResourceGroupDeployment -ResourceGroupName "RG1" `
    -TemplateFile "<path_to_template.json>" `
    -TemplateParameterFile "<path_to_template.parameters.json>"

<path_to_template.json> with the actual local file path of your Template.json file
<path_to_template.parameters.json> with the actual local file path of your Template.parameters.json file.
