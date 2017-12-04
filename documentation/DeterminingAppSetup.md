# Determining App Setup

## Content Rating Level
Your app's content rating level inform users of it's maturity level. The possible rating levels are:

* Everyone
* Low maturity
* Medium maturity
* High maturity

[Determine your app’s content rating](https://support.google.com/googleplay/android-developer/answer/188189) . Providing an appropriate rating for your app is a requirement of the Developer Program Policies but, it also ensures your app gets seen by the right age-based audiences.

## Country Distribution
Determine what countries and territories you'd like to distribute your app in. Usually, developers want to distribute as widely as possible to grow their customer base, but you may decide there are certain app requirements, launch dependencies or business needs which may cause you to exclude certain countries.

The countries you decide to launch in will affect:

* The need for localized app resources
* The need for localized app descriptions in the Developer Console
* Country specific requirements
* Time zone support
* Local pricing

[Setup your app’s price and countries of distribution](https://support.google.com/googleplay/android-developer/answer/6334373). Once you’ve determined your [monetization model](https://developer.android.com/distribute/best-practices/earn/monetization-options.html), setup your app as free or paid and select the countries in which it will be distributed. 

## App's Overall Size
As of the time of this publishing, the max size for an APK published on Google Play is 100MB. If your app is larger than this, Google Play allows you to attach two large expansion files that supplement your APK. To set this up, use [APK Expansion Files](https://developer.android.com/google/play/expansion-files.html).

Also, before you build your release-ready APK, run [Proguard](https://developer.android.com/studio/build/shrink-code.html) to remove unused code and resources to shrink the size of your app binary.

## Confirm Target Platform Versions & Device Screens
Ensure your app runs on the Android platform versions and device screen sizes you plan on.

Double-check the minSdkVersion which is the minimum version your app will be compatible with. Android platform versions are defined by the [API level](https://developer.android.com/guide/topics/manifest/uses-sdk-element.html#ApiLevels).

For device screen sizes, run the app on a range of screen sizes and pixel densities. Checkout the [Support Multiple Screens](https://developer.android.com/guide/practices/screens_support.html) guide to understand how to prepare your app. Additionally, see the current breakdown of Android platform versions and screen sizes available in the world in the [Device Dashboard](https://developer.android.com/about/dashboards/index.html) to help you decide which versions and screen sizes to you'd like to target.

Additionally, there are a number of 3rd party testing platforms that allow you to test your app on many real devices all in the cloud. For example, [Xamarin Test Cloud](https://www.xamarin.com/test-cloud).

[Define your app’s device compatibility](https://support.google.com/googleplay/android-developer/answer/7353455?visit_id=1-636480105572559028-3255797253&rd=1). Let the Play Store know which Android versions and device screen sizes your app is designed to work on.

## Free or Priced App?
You can publish your app as free to download or priced.

Free apps can be downloaded by any Android user in Google Play. Free apps must remain free; however, you can still sell [In-app Products](https://developer.android.com/google/play/billing/billing_overview.html#products) and [Subscriptions](https://developer.android.com/google/play/billing/billing_subscriptions.html) via Google Play's In-app [Billing Service](https://developer.android.com/google/play/billing/index.html).

Priced apps can be downloaded only by users who are in a country that supports paid downloads and have registered a form of payment in Google Play, such as a credit card or Direct Carrier Billing. Priced apps can be changed to free at any time.

If you do decide on a priced app or are selling in-app products, you'll need to setup a [Google payments merchant account](https://developer.android.com/distribute/best-practices/launch/index.html) before you can publish.

## In-app Billing or Android Pay
If your are looking for more ways to monetize your app and build engagement, you should consider [In-app Billing](https://developer.android.com/google/play/billing/index.html) which allows you to you sell either downloadable digital content in your app such media files or photos or Android Pay which simplifies selling physical goods and services such as food or clothing to your users.

## Set Product Prices
If your app is priced or you’re selling in-app or physical products, determine the currency or types of currencies you’d like to accept. You have the flexibility in the Developer Console to price products individually in different currencies so you can adjust according to exchange rates and market conditions.

* [Offer apps in multiple currencies](https://support.google.com/googleplay/android-developer/answer/1169947)
* [Setup prices & app distribution for your app's country](https://support.google.com/googleplay/android-developer/answer/6334373?visit_id=1-636275525080183095-4138352002&rd=1#paid_free)
* [Transaction fees](https://support.google.com/googleplay/android-developer/answer/112622)
* [Tax rates & value-added tax](https://support.google.com/googleplay/android-developer/answer/138000)

## Start Localization
Lastly, make sure your app meets localization needs. This includes app resources (e.g. strings, images, etc), your app's Google Play store listing details, and graphic assets screenshots, and videos.

Review the [Localization](https://developer.android.com/distribute/best-practices/launch/localization-checklist.html) Checklist for key steps.

For Resource localization, checkout the [Localizing with Resources](https://developer.android.com/guide/topics/resources/localization.html) guide.









