# Mail-Exchange-Server-GAL-not-synchronising-contacts-with-outlook-clients
If you have added a user to your domain and its not showing up I did this to fix it.

– Make sure Mail Exchange Agent service is started
– in Powershell run Update-GlobalAddressList -Identity “Default Global Address List”
– In EMC goto organisation / mailbox / offline address book / right click on OAB and update
– On clients that do not sync then goto tools, send/recieve and choose download address book
