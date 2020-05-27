
# App-O-Track In-App SDK
**English Version** | [Русская Версия](/README.md)
> SDK to monetize your apps with ads

[Connect my app!](https://accgp.store/sdk)

## Getting Started
> **Note:** we had to restrict the access to the SDK package. Source codes and instructions are available on request.

### Payout Model for App-O-Track ADs
Users will interact with ADs in this way:

- User starts the application
- SDK checks if the user's location is presented in ADs white list
    - If it is, users will see **ADs only**, instead of application at all. There is no possibility to close ADs.
    - If it is not, the application will work as usual, without ADs.

Currently, payouts are provided only at a fixed rate, for example, once a week. This means that payment will occur regardless of the number of applications installs or the number of users. The specific tariff and frequency of payouts you always can check with your manager.

**We guarantee** a good rating of the application on Google Play and an increase in the number of installations as we will promote the application.

### Get an SDK package
Please follow these steps:
1. Decide which application you want to monetize. You must have access to the source code. Keep in mind that some users will see ADs only.
2. Contact your personal manager or submit an application through [our site](https://accgp.store/sdk). Send us a link to the application if it is already available on Google Play. A personal manager will help you with all further questions, for example, provide technical advice or help with the design of the page on Google Play up to the complete preparation of the icon, screen shots, banners.
3. Gen an SDK package from your manager. AppotrackActivity.java is the main and only file of our SDK. Put it in your project in the package `com.appotrack_sdk` and move on to the next section of this document. See the demo project in the `/example` directory if you have additional questions about integration.
4. Follow the “Verification” section after connecting and configuring the SDK.
 
### Verification
Your manager will verify SDK setup by himself using APK file of the app.
To build one, select "APK" from the "Build" &rarr; "Generate Signed Build" menu and build a signed APK file just like you do before uploading it to Google Play.
Then send an APK file to your manager.
