How to use a PS Command on a remote Azure VM from a Runbook
===========================================================

            

**Description**


This runbook connects into an Azure virtual machine and runs the PowerShell command passed in through the input parameters.  It has a dependency on the Connect-AzureVM runbook to set up the connection to the virtual machine before the command can
 be run.

**


Requirements


**

Before importing and using this runbook the following items must be made available: 




  *  An Automation credential asset containing an Active Directory Org Id username / password with access to this Azure subscription.

  *  Connect-AzureVM runbook must be imported and published.  This runbook can be downloaded here: [http://gallery.technet.microsoft.com/scriptcenter/Connect-to-an-Azure-85f0782c](http://gallery.technet.microsoft.com/scriptcenter/Connect-to-an-Azure-85f0782c)


 



**


Runbook Content


**

** **The runbook's content is displayed below: 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
