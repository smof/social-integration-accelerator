<b>social-integration-accelerator</b>
<br/>
<br/>
Scripted utility to accelerate the integration of 3rd party OAuth2/OIDC compliant identity providers into ForgeRock Access Management 5.0 
<br/>
<br/>
![ScreenShot](./what-it-is.png)
<br/>
<br/>
<b>Running: </b>
<br/>
1 - clone/download, chmod +x on social-integration-accelerator if necessary <br/>
2 - from bash, run ./social-integration-accelerator <br/>
![ScreenShot](./menu.png) <br/>
3 - select option C, and edit any settings <br/>
![ScreenShot](./settings.png) <br/>
4 - select option 1, to pull down .well-known JSON payload <br/>
5 - select option 2, to create the necessary templates <br/>
6 - select option 3/4, to view/edit the templates, adding in any client Id's or secrets and checking any mappings  <br/>
![ScreenShot](./auth-module-template.png) <br/>
7 - select option 5 to import into AM via amster
![ScreenShot](./amster-import.png) <br/>
<br/>
<br/>
<b>Limitations</b><br/>
1 - Need to add client Id and secrets manually and check mappings are accurate <br/>
2 - If the login logo is required on the AM first screen, need to manually export the SocialAuthentication.json from AM using amster and upload necessary logo <br/>
3 - If IDP doesn't support .well-known URL download, have to create templates and manually add in URL's <br/>
<br/>
<br/>
Use as-is.  Note this utility is a community contribution only and is not supported by ForgeRock.
<br/>
See LICENSE for further details.
<br/>

