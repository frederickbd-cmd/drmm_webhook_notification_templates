# drmm_webhook_notification_templates

What is this?
- The files in this repo are JSON blobs for creating message cards in Microsoft Teams, via a webhook notification. 
- The files are for Datto RMM alerts, with different files containing payloads for alerts being created, and alerts being resolved.

Support for Datto RMM variables
- There are a number of variables supported in these payloads, such as [device_hostname] etc.
- This can unlock a huge amount of potential, for excample displaying important device specific information, or constructing links to open a device page.
- For more details on these, please review the Datto RMM Help. https://rmm.datto.com/help/en/Content/0HOME/Home.htm

A note on constructing links:
- Also, please note that the URLs for the action buttons will have to change for your platform. In these examples they are 'sandboxrmm'. If your Datto RMM platform is Concord, for example, change the 'sandbox' out for 'concord'.
