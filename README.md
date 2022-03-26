# Smite-API-Module
The goal of this project is to build out a fully functioning Powershell module that will simplify the use of the Smite API

**How to use:**
You can import this with "Import-module C:\pathtofile.psm1" 

After you've done this you will be able to run the commands

**Currently supported commands**
Import-GodIds `
Get-Playerstats
Get-Smiteitems
Get-Gods
Check-SmiteConnection
Test-SmiteSession
Get-HirezServerStatus
Get-DataUsed
Get-DemoDetails
Get-EsportsProLeagueDetails
Get-Friends
Get-GodRanks
Get-GodSkins

**Examples**
Get-Playerstats -Devid 1234 -Authkey "Authorizationkey1234" -PlayerName Username

Get-Gods -Devid $devid -Authkey $authkey

Get-GodSkins -Devid $Devid -Authkey $authkey -GodName "Bellona"


**Next steps for this module:**
-Continue adding cmdlets
-Start building out help files for commands
-Create a manifest file for the module
-Upload file to PSGallery
