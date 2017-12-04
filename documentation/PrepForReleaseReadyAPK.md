# Prep for Release-Ready APK

After preparing your app to meet UI, compatibility, and quality requirements, it’s time to configure your app for release, upload the release-ready APK to your Developer Console and distribute to users.

Preparing the application for release is a required development task for all Android apps, and involves configuring, building, and testing a release version of the app. Before we begin this process, let's determine the materials and resources we’ll need to gather.

## Cryptographic Key
First, you’ll need a Cryptographic key. Applications installed on an Android device must be digitally signed with a certificate that is owned by the app’s developer. In other words, the developer holds a private key to the app’s certificate. This certificate is used to identify the creator of the app and to maintain trust between applications.

[How to obtain a certificate to sign your application.](https://developer.android.com/studio/publish/app-signing.html)

## App Icon
Next, double-check that your app’s icon meets the [app launcher icon guidelines](https://material.io/guidelines/style/icons.html).

An app’s launcher icon has 3 goals:

* Promotes the brand and tells the app’s story
* Helps users discover the app on Google Play
* Functions well in the launcher (meaning it looks great on any background and placed next to other icons)  

## End-User License Agreement (EULA)

A EULA is an agreement between you, the developer, and the end-user.

If we look at Section 5.4 of the Developer Distribution Agreement, it states:

*5.4 You grant to the user a non-exclusive, worldwide, and perpetual license to perform, display, and use the Product on the Device...If you choose, you may include a separate end user license agreement (EULA) in your Product that will govern the user’s rights to the Product, but, to the extent that EULA conflicts with this Agreement, this Agreement shall supersede the EULA.*

In other words, drafting your own EULA is not required, but could be helpful in protecting your intellectual property rights, limit your liability, and disclaim warranties.

If you decide to draft your own EULA and need some examples to help get you started, you can check out the licenses for popular github projects:

* [Square Open Source](https://square.github.io/) has several open source projects with license agreements that could fit your situation. Navigate to the License file for any project, to see which license they use.
* The [Apache License](https://www.apache.org/licenses/LICENSE-2.0.html) is an open source software license popularly used for products users can freely use, modify, and distribute.
* Another popular open source license is the [MIT license](https://opensource.org/licenses/MIT). The MIT license is shorter, simpler, and allows users more freedom in using your product than the Apache License does.
* If you need help choosing between types of open source licenses, check out [www.choosealicense.com](www.choosealicense.com) to help you decide which open source license best fits your situation.
You can also check out the EULA for apps you commonly use already.

If you have downloaded the Udacity app on your device, you can see the license wording we use directly in the app in the Settings menu, under License.

Google also has specific EULAs for their apps - for example, check out the one in Maps under the Settings menu.

## Promotional Materials
Lastly, make sure you have the promotional or marketing materials ready to showcase your app so that it attracts new users on Google Play. For more info, see the [Graphic Assets for your Application documentation](https://support.google.com/googleplay/android-developer/answer/1078870).

Prepare screenshots for each supported device -- phone, tablet, TV, or wear. Make sure they meet the min and max dimensions so they represent your app in the best light on Google Play. Remember, all apps listed must have a high-res icon. A Feature graphic, displayed at the top of your Store Listing Page can grab a new user’s attention.

Also consider promotional graphics, banner assets (for Android TV), 360 degree stereoscopic images (for Daydream-enabled apps), and a potential promo video.