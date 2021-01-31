# Module 14 setup

1. Click on the following button to open the ARM template in the Azure portal:

    <a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsolliancenet%2Fmicrosoft-data-engineering-ilt%2Fmain%2Fsetup%2F14%2fmodule-14-template.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png" /></a>

2. On the **Custom deployment** form fill in the fields described below.

   - **Subscription**: Select your desired subscription for the deployment.
   - **Resource group**: Create a new resource group named **`ms-dataengineering-14`**.
   - **Region**: The Azure region where your lab environment will be created.
   - **Unique Suffix**: This unique suffix will be used naming resources that will created as part of your deployment. Make sure you follow correct Azure [Resource naming](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/naming-and-tagging#resource-naming) conventions.
   - **SQL Administrator Login Password**: Provide a strong password for the SQLPool that will be created as part of your deployment. [Visit here](https://docs.microsoft.com/en-us/sql/relational-databases/security/password-policy?view=sql-server-ver15#password-complexity) to read about password rules in place.

   > **Important:** You will need your password during the lab. Save your password in Notepad or similar text editor so you can reference it during the lab.

3. Select the **Review + create** button, then **Create**. The provisioning of your deployment resources will take approximately 10 minutes. **Wait** until provisioning successfully completes before continuing.

    > **Note**: You may experience a deployment step failing in regards to Role Assignment. This error may safely be ignored.
