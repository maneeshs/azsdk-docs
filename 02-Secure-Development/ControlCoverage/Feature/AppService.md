<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>AppService</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td>All users/identities must be granted minimum required permissions using Role Based Access Control (RBAC)</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Custom domain with SSL binding must be configured for App Service</td><td>Medium</td><td>Yes</td></tr>
<tr><td>App Service must authenticate users using Azure Active Directory backed credentials</td><td>High</td><td>Yes</td></tr>
<tr><td>Publish profile credentials must not be used for App Service deployment</td><td>High</td><td>No</td></tr>
<tr><td>Trigger URL for the App Service Web Job must require authentication</td><td>High</td><td>No</td></tr>
<tr><td>The webhook used for a Web Job must encrypt sensitive data in transit</td><td>High</td><td>No</td></tr>
<tr><td>All App Service secrets should be stored in Key Vault</td><td>Medium</td><td>No</td></tr>
<tr><td>App Service should use Notification Hub for push notification (instead of directly using Push Notification Service)</td><td>Medium</td><td>No</td></tr>
<tr><td>Remote debugging must be turned off for App Service</td><td>High</td><td>Yes</td></tr>
<tr><td>Web Sockets should be disabled for App Service</td><td>Medium</td><td>Yes</td></tr>
<tr><td>&#39;Always On&#39; should be configured for App Service</td><td>Medium</td><td>Yes</td></tr>
<tr><td>The latest version of .NET framework version should be used for App Service</td><td>Low</td><td>Yes</td></tr>
<tr><td>64-bit platform should be used for App Service</td><td>Low</td><td>Yes</td></tr>
<tr><td>Deployment of App Service should be done using ARM template</td><td>Medium</td><td>No</td></tr>
<tr><td>App Service must be deployed on a minimum of two instances to ensure availability</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Backup feature must be configured to backup data for App Service</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Auditing and Monitoring must be enabled for App Service</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Auto healing should be configured for App Service</td><td>Medium</td><td>No</td></tr>
<tr><td>App Service must only be accessible over HTTPS</td><td>High</td><td>Yes</td></tr>
<tr><td>WEBSITE_LOAD_CERTIFICATES parameter must not be set to &#39;*&#39; (i.e. all) for App Service</td><td>High</td><td>Yes</td></tr>
</table>
</body></html>
