# Sandpit: Managed Images Attributes

Microsoft may have reinstated SharePoint's ability to process and save EXIF data for photographs and images in specially named custom fields. However, this solution demonstrates how you can discover the field names if you choose to use the out-of-the-box (OOTB) functionality and how to create a solution yourself using Power Automate. It can also be easily adapted for use with Azure Logic Apps.

To transform this into an enterprise-grade solution, we can incorporate SharePoint Search. By creating managed properties and refinable strings, we can then showcase a catalogue of photographs on a SharePoint page using PnP Search web parts.

The full article will be available at [www.sjlewis.com](https://www.sjlewis.com/)

## Power Platform Solution Config

When importing the **Sandpit: Manage Image Attributes** solution into an environment, you will need to configure the following properties:

- Sandpit-MIA-Tenant
  > The tenant name used within the SharePoint URL.
- Sandpit-MIA-SharePoint
  > Connection reference for the 'Sandpit: Manage Image Attributes' solution.
- Sandpit-MIA-SPSite
  > Connection to the site collection.
- Sandpit-MIA-SPLibrary
  > Connection to the Image library.
- Sandpit-MIA-SPView
  > The GUID for the 'zzzCloudFlow' view.
