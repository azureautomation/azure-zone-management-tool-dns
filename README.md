Azure Zone Management Tool - DNS
================================

            

 

**Updates v1.1 Adds VM Alignment function to allow the zone to be automatically aligned with existing Azure VMs.**


This script was create to ease management pains around Azure Zone DNS Management. The script also supports CSV Format imports for record creation and deletion. There is also an -getinfo option which allows for easy retrieval of
 zone record set information. To get the latest version or checkout the csv template please visit Github.


EXAMPLES
 .\AZRM-MngdnsZone.ps1 -Action getinfo -ZoneName myzone.net -rg zone-dns

 .\AZRM-MngdnsZone.ps1 -Action createzone -ZoneName rmp.net -rg rmp-dns



        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
