![Azure Sentinel Project Diagram](https://user-images.githubusercontent.com/31329300/209582975-542a7422-bea5-454b-97e9-d096bc4a0d00.png)

# Azure Sentinel (SIEM) Project

• Used custom PowerShell script to extract metadata from Windows Event Viewer to be forwarded to third party API in order to derive geolocation data.

• Configured Log Analytics Workspace in Azure to ingest custom logs containing geographic information (latitude, longitude, state/province, and country)

• Configured Custom Fields in Log Analytics Workspace with the intent of mapping geo data in Azure Sentinel.

• Configured Azure Sentinel (Microsoft's cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attacks
      of attackts

![Screenshot1 Sentinel](https://user-images.githubusercontent.com/31329300/206350753-064829f1-eed6-4dfe-a494-301a96d2e246.png)



