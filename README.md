# Crowdstrike-deploymwent
This script is designed to constatly onboard agents on a Organization Unit. The script verifies if CS-SERVICE is running on a system and pushes to that system if it doesnt have cs-service
To Use? 
1, Open in notepad and input 
$SourcePath = "",
$CID = "",
$InstallerName = "",
where source path is source path on network
cid is customer id
installer name is crowdstrike .exe.

Set script to run on startup Via GPO
AND YOU ARE GOOD TO GO.


