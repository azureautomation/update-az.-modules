Update Az. Modules
==================

            

Very powerful Powershell function which is made to download set of Az.* modules from Powershell gallery, compress them, upload to temporary blob storage on the Azure and then import them to target automation account.


Linear cleanup is following the logic, so everything that is downloaded will be also removed, which will keep the system clean.


Storage account is also being destroyed after all of the modules have been hosted and uploaded to Automation account.


You have to be authenticated against the proper Azure Context.


I assume you have working Powershell environment, with the Nuget package management and PowershellGet , as well as working set of Az. modules to reach Azure services.


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
