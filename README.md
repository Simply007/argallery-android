# Kentico Cloud Art Gallery Application for Android

[![Forums](https://img.shields.io/badge/chat-on%20forums-orange.svg)](https://forums.kenticocloud.com) 

Implementation of an art gallery application for Android written in Kotlin that utilizes Kentico Cloud CMS for content management. 
Register your account for free at https://app.kenticocloud.com.

With the ARCore platform, the application supports Augmented Reality and is able to create a virtual gallery within real environment.
Examples of how the app work can be seen [here](https://is.muni.cz/th/yabmm/videos.zip).

![list](./screenshots/argalleryList.png)
![detail](./screenshots/argalleryDetail.png)
![ar](./screenshots/argalleryWall.png)

## Application Installation
1. Install [Android Studio](https://developer.android.com/studio/) and the latest Android SDK tools. 
2. Clone or download the repository into a chosen folder. 
3. Open the project in the IDE, let it install all the necessary libraries and tools. 
4. Building the project in Android Studio creates an `.apk` file, located in `app\build\outputs\apk\debug`.
5. The file can be used to install the application on a mobile device, but be sure to have one that [supports ARCore platform](https://developers.google.com/ar/discover/supported-devices).

## Content Administration
1. Navigate to https://app.kenticocloud.com in your browser.
2. Sign in with your credentials.
3. Manage content in the content administration interface of your sample project.

You can learn more about content editing with Kentico Cloud in the [documentation](https://developer.kenticocloud.com/docs).

## Content Delivery
You can retrieve content either through the Kentico Cloud Delivery SDKs or the Kentico Cloud Delivery API.

This project is utilizing [Delivery JavaRX (Android) SDK](https://github.com/Kentico/KenticoCloudDeliveryJavaRxSDK) for content retrieval.

1. In order to utilize your own Kentico Cloud project instead of the default one, you need to change the `KENTICO_CLOUD_PROJECT_ID` constant in the `AppConfig` file to the ID of your own project.
2. The project ID can be found on Kentico Cloud by navigating to *Project Settings* and then to *API Keys*.


![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/argallery-android?pixel)

## Looking for iOS?
[![Apple iOS](./screenshots/apple.jpg) Click here](https://github.com/Kentico/argallery-ios)
