# docker-iis-wcf-mgmt
IIS on Windows with IIS Managemenet. Ready for Ria Services, WCF, Windows Authentification ASP.Net

Get an IIS with Remote Management, Ready for WCF, Ria Services, Silverlight RIA Apps, ASP.Net Apps, WebSockets, Dynamic Compression, ISAPI Filters.

Just need to ADD files to C:\inetpub\wwwroot: ADD . C:/inetpub/wwwroot/

Exposes port 80 and 8172 for IIS Management

To remove the iisstart.htm default document, you can modify your web.config like the following example

<system.webServer>
<defaultDocument enabled="true">
<files>
<remove value="iisstart.htm" />
<add value="mystartpage.aspx" />
</files>
</defaultDocument>
</system.webServer>
