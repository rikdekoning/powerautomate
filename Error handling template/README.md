# Power Automate - Error handling template #
With this template, you will be provided with out-of-the-box error handling for your Power Automate flows.
It contains the following features:
- TRY, CATCH, FINALLY configuration
- README which shows how to configure the flow
- Error collecting from actions within the TRY scope
- Mail to predefined recipient, containing the errors and a link to the flow run

The flow needs to be imported into your environment before you can make any configuration changes. To do so, follow the following steps:
1. Download the .ZIP from this repository
2. Go to the [Power Automate Maker portal](https://make.powerautomate.com "Power Automate Maker Portal")
3. Go to __My flows__ 
4. Select __Import__ - __Import Package (Legacay)__
5. Select the .ZIP file you downloaded in Step 1, the flow will now be uploaded to your environment
6. If you want to change the name of your flow, click on the __Create as new__ link, provide a __Resource name__ and click __Save__
7. Select the Office 365 Outlook connection you wish to use by clicking the __Select during import__ link, select an existing connection or create a new one and click __Save__
8. Click __Import__ and your flow will be imported into your environment (this might take a few moments)
9. When imported, you can configure the flow according to your process by clicking the __Open flow__ link at the top
    1. Check the README action in the flow on how to configure the flow
10. Don't forget to enable the flow when you're done
