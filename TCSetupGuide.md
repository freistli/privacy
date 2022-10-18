1. Register App in Azure AD https://aad.portal.azure.com (Refer to [Register your app with the Azure AD v2.0 endpoint](https://learn.microsoft.com/en-us/graph/auth-register-app-v2?view=graph-rest-1.0)), with below scopes for Delegated Permissions of Microsoft Graph, granted the scopes with Admin consent:
  
                "User.Read.All
                "Group.Read.All"
                "Chat.Create"
                "ChannelSettings.Read.All"
                "ChannelMessage.Send"

2. Add Mobile and desktop applications call back, set "https://login.microsoftonline.com/common/oauth2/nativeclient" as call back Url

   ![image](https://user-images.githubusercontent.com/8623897/196481082-ac1d9ce5-398e-47d8-a531-9b1a9c290d68.png)

   Copy Tenant ID and Client ID of the App from https://aad.portal.azure.com.

3. The login users need to be in the AAD group (create it if don't have) and be able to get Admin Consent to use the above scopes: 

   **TeamsCommunicatorGP**

  ![image](https://user-images.githubusercontent.com/8623897/196481916-bada985b-8725-45e3-b334-e74a8dd2b19b.png)

 4. Config Tenant ID, Client ID, and Redirect Uri as below. If the register the app as Multi-Tenant, use **common** in the Tenant ID field, otherwise, use the real Tenant ID


   ![image](https://user-images.githubusercontent.com/8623897/196483155-ef6ed635-373c-4a6e-90c2-50d5bcc77669.png)

   
   

