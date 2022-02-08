# drmm_webhook_notification_templates

What is this?
- The files in this repo are JSON blobs for creating message cards in Microsoft Teams, via a webhook notification. 
- The files are for Datto RMM alerts, with different files containing payloads for alerts being created, and alerts being resolved.

A note on making message cards:
- There are many resources available on how to construct JSON blobs to send into Microsoft Teams. For testing them on-the-fly, and just getting to grips with this, https://messagecardplayground.azurewebsites.net/ is a good resource.

Support for Datto RMM variables
- There are a number of variables supported in these payloads, such as [device_hostname], or [platform] which is useful when constructing URLs.
- This can unlock a huge amount of potential, for example displaying important device specific information, or constructing links to open a device page.
- For more details on these, please review the Datto RMM Help. https://rmm.datto.com/help/en/Content/0HOME/Home.htm
