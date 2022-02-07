# Microsoft ARM例子


[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fqiaolb%2Farm_first_001%2Fmaster%2Fazuredeploy.json)

### 执行方式

`Powershell`命令如下：
#### 登录Azure

```
Connect-AzAccount
```

设置订阅

```
Set-AzContext [SubscriptionID/SubscriptionName]
```

###创建资源

```
New-AzDeployment -TemplateFile ./azuredeploy.json -TemplateParameterFile ./azuredeploy.parameters.json
```