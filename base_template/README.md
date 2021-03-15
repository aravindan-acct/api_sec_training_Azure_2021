### Template Parameters

1. "Resource Group" - Create a new resource group. This resource group will be same for the resources that will be created as part of the frontend_app_new.json template as well.
2. "adminpassword" - Password to login to the Linux server i.e. the API Server, deployed as part of this template.
3. "wafadminpassword" - Password for the Barracuda Cloudgen WAF instance. Username to login is "admin".

### Deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faravindan-acct%2Fapi_sec_training_Azure_2021%2Fmain%2Fbase_template%2Fbase_template_new.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>

### Additional Notes

The template takes about 10-12 minutes to create the resources and complete the bootup process of the Barracuda Cloudgen WAF.