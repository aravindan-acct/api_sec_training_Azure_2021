### Template Parameters

1. "Resource Group" - Select the resource group that was created as part of the base_template_new.json
2. "adminpassword" - Password to login to the Linux server i.e. the frontend Web UI server deployed as part of this template.
3. "bwafpassword" - Password to login to the Barracuda Cloudgen WAF that was deployed as part of the base_template_new.json
4. "wafPrivateIPAddress" - Private IP address of the Barracuda Cloudgen WAF that was deployed as part of the base_template_new.json
5. "wafPublicIPAddress" - Public IP address of the Barracuda Cloudgen WAF that was deployed as part of the base_template_new.json

### Deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faravindan-acct%2Fapi_sec_training_Azure_2021%2Fmain%2Ffrontend_app%2Ffrontend_app_new.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>

### Additional Notes

The template takes about 5 minutes to create the resources and complete the script execution to configure the WAF.

