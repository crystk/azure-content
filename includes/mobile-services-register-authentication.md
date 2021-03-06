
* Click Azure Portal > **Mobile Services** > your mobile service > **Dashboard**, and make a note of the **Mobile Service URL** value.

* Register your app with [Google](mobile-services-how-to-register-google-authentication.md), [Facebook](mobile-services-how-to-register-facebook-authentication.md), [Twitter](mobile-services-how-to-register-twitter-authentication.md), [Microsoft](mobile-services-how-to-register-microsoft-authentication.md), or [Azure Active Directory](mobile-services-how-to-register-active-directory-authentication.md). Make a note of the client identity and client secret values generated by the provider. Do not distribute or share the client secret.

* Click Azure Portal > **Mobile Services** > your mobile service > **Identity** > your identity provider **settings**. Enter the app ID and secret value from your provider. You've now configured both your app and your mobile service to work with your auth provider. You may optionally repeat all these steps for each additional identity provider you'd like to support.

    > [AZURE.IMPORTANT] Verify that you've set the correct redirect URI on your identity provider's developer site. As described in the linked instructions for each provider above, the redirect URI may be different for a .NET backend service vs. for a JavaScript backend service. An incorrectly configured redirect URI may result in the login screen not being displayed properly and the app malfunctioning in unexpected ways.
