# Mail-Exchange-Server-GAL-not-synchronising-contacts-with-outlook-clients
If you have added a user to your domain and its not showing up I did this to fix it.

<ul>
<li>Make sure Mail Exchange Agent service is started</li>
<li>in Powershell run Update-GlobalAddressList -Identity “Default Global Address List”</li>
<li>In EMC goto organisation / mailbox / offline address book / right click on OAB and update</li>
<li>On clients that do not sync then goto tools, send/recieve and choose download address book</li>
</ul>
