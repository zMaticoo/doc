---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# User Guide

## Contact our business manager <a href="#td5qs" id="td5qs"></a>

Mail：[sunny.yang@zmaticoo.com](mailto:sunny.yang@zmaticoo.com)

Tel：0086 18292453580&#x20;

## Create a zMaticoo Account <a href="#td5qs" id="td5qs"></a>

You can sign up for zMaticoo SDK at our [registration page.](https://ssp.zmaticoo.com/#/signUpF)

You need to provide the following information to complete registration:

* An Email address.
* Payment information (Wire or Paypal supported).
* Company information.

## How can I start monetizing my app properties?  <a href="#m2ml5" id="m2ml5"></a>

1. Sign in to your zMaticoo account at [login page](https://ssp.zmaticoo.com/#/signIn) .
2. The following sections show you how to use zMaticoo Supply-Side Platform.
3. Integrate zMaticoo SDK(Android or iOS) into your app.
4. Add a test device in SSP to display test ads to check whether the advertising network is nomal.
5. Pushlish your app and view revenue in reports.

## How do I add my app?

### Adding a new app

1. You can add a new app via 【Application】 > 【Apps】 > 【Add App】

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

2. Please fill in the following information

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

* **Bundle ID:** If you have an Android app, you should fill in the package name, such as com.example.xxx; If you have an iOS app, you should fill in the idstore-id, such as 123456789.
  * The package name you fill in must be complete, as we will use it to check its uniqueness on our platform. However when you request ads, we will only check the main package name so that you do not have to add the package again for other channels. Of course, you can manually add the packages for other channels so as to distinguish data from such channels.&#x20;
* **App Store URL:** Fill in the details page link of the Google Play or  Apple App Store. If your app is not in app store, please contact our operation team.
  * Apple App Store URL format: https://apps.apple.com/region/app/app-name/idstore-id
  * Google Play URL format: https://play.google.com/store/apps/details?id={xxxx}
* **Website:** Please fill in  official website address of your app and we will verify app-ads.txt from that website.
* If the Bundle ID already exists, and you can prove that you are the rightful owner of the package name, please contact your business development manager or contact us via sunny.yang@zmaticoo.com.

### Explanation of App Status  <a href="#fwi1w" id="fwi1w"></a>

**Live:** Ads are being delivered, and the ad platform will generate relevant data.&#x20;

**Verifying:** The app is under review. You will receive the results via mail. Please don't forget to check your mail.&#x20;

**Verification failed:** Your app has been rejected due to incorrect information.&#x20;

**Stopped:** Suspended apps are unavailable for advertising.&#x20;

**Abnormal stop:** Your app has been aborted due to violations of Maticoo's business specifications. More details will be provided in the site message.&#x20;

### How to Suspend Ads  <a href="#wroyp" id="wroyp"></a>

You may suspend your ads by following the steps in the picture below:&#x20;

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

* Open: Ads can be requested normally, and will be restored to the state before closing after activation.
* Close: It is not possible to request ads. After closing the application, the ad placement is also closed at the same time, and the historical revenue will not be affected.

Please note that once the app is "stopped", all ad placements associated with the app no longer get ad delivery. This action is irreversible.&#x20;

## How do I create an ad placement?  <a href="#xdp1j" id="xdp1j"></a>

### Creating a new ad placment

1. You can create a new ad placement via 【Application】 > 【Ad placements】> 【Add Ad Placements】

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

2. Select the corresponding ad unit for each ad placement.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

### Supported Ad Formats

#### Banner Ads&#x20;

Banner Ads are a basic ad format that is displayed at the top or bottom of a screen and can be automatically refreshed(The default refresh period is 30s).

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

* Ad Placement Size: select a size for the ad placement. zMaticoo will adjust the appropriate ad creatives according to the size of the ad placement.
* Price: select a pricing type for this ad placement. See [pricing section](user-guide.md#pricing-type).

#### Rewarded Video Ads

Rewarded video ads provide rewards to the users who have watched a short video, interacted with playable content, or completed a survey.&#x20;

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

* Price: select a pricing type for this ad placement. See [pricing section](user-guide.md#pricing-type).

#### Interactive Ads

Interactive ads allow users to participate in the marketing process without perception through gamification. **Contact our operation team before creating this ad placement.**

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

#### Interstitial Ads

Interstitial ads are a full-page ad format that appears at natural breaks and transitions. When an app shows an interstitial ad, the user has the choice to either tap on the ad and continue to its destination or close it and return to the app. Intersitial ad supports image, video.

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

* Creative Type: select a creative type. The default option is 【Video and Image】.
* Ad Show: set when to show the 【Skip】 button in the upper righ corner of the screen. The default time is 5 seconds, but you can set 3\~10s.
* Price: select a pricing type for this ad placement. See [pricing section](user-guide.md#pricing-type).

#### Native Ads

Native Ads can be customized to fit the style and design of an app, as well as to blend into app content. Native Ads support video ad types.

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

#### Splash Ads

Spash ads are displayed immediately after an app is launched, even before the home screen of the app is displayed.

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

* Create type: select a creative type. The default option is 【Video and Image】.
* Countdown times: control the maximum display time of the ad. When the time is up, the ad will automatically close.
* Allow Skip: whether to allow skip button to be displayed, when selecting the yes option, you should set the ad show time below.
* Ad Show: set when to show the 【Skip】 button in the upper righ corner of the screen. This time must less than countdown times. If you set 0 second, it means the 【Skip】 button always show.
* Price: select a pricing type for this ad placement. See [pricing section](user-guide.md#pricing-type).

### Pricing Type

zMaticoo supports two pricing types, that are 【In-app Bidding】 and 【Flat eCPM】.

In-app Bidding: If the pricing type of the ad placement is In-app Bidding, zMaticoo will bid for each impression in real time.

Flat eCPM: If the pricing type of the ad placement is Flat eCPM, you set a price floor for this placement. Bids below this price will be automatically ignored.

