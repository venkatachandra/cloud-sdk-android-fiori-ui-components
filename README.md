# FioriUI Demo Application

## Description

This application demonstrates the available components in the Fiori UI library. It organizes the samples using an easy-to-navigate table. The app is intended to simply provide example implementation of each control, so that users can take the samples and expand their own applications to use the Fiori library. Each table cell represents a type of Fiori control, and the user can tap a table cell to see more detail on a specific control.

## The Finished Product

The app lists the available Fiori components.

![The finished application](images/app-home-screen.png)

Tapping a component type brings the user to more options related to that specific control. 

![Tapping the Fiori Basic Components](images/basic-components-tap.png)

![Tapping "Selections"](images/selections-tap.png)

![Selections](images/selections.png)

## Requirements

* [Android Studio](https://developer.android.com/studio/index.html) version 3.2.1
* [SAP Cloud Platform SDK for Android from Trial Downloads](https://www.sap.com/developer/trials-downloads/additional-downloads/sap-cloud-platform-sdk-for-android-15508.html) or [SAP Cloud Platform SDK for Android from Software Downloads](https://launchpad.support.sap.com/#/softwarecenter/template/products/_APP=00200682500000001943&_EVENT=NEXT&HEADER=Y&FUNCTIONBAR=Y&EVENT=TREE&NE=NAVIGATE&ENR=73555000100800001281&V=MAINT&TA=ACTUAL/SAP%20CP%20SDK%20FOR%20AND) version 1.1.2 (1.0 SP00 PL02)
* [SAP Cloud Platform](https://cloudplatform.sap.com/index.html)

The blog [Step by Step with the SAP Cloud Platform SDK for Android](https://blogs.sap.com/2018/10/15/step-by-step-with-the-sap-cloud-platform-sdk-for-android-part-1/) contains additional details on how to setup and install the SDK, how to register for a trial version of the SAP Cloud Platform, and how to enable Mobile Services.  It is also a great place to start if you are new to the SAP Cloud Platform SDK for Android.

There is extensive documentation at [SAP Experience](https://experience.sap.com/fiori-design-android/explore/) and [Fiori Development](https://help.sap.com/doc/c2d571df73104f72b9f1b73e06c5609a/Latest/en-US/docs/fioriui/fiori_ui_overview.html).

## Configuration

Open the project in Android Studio.

To successfully run the application, the `sdkVersion` variable in the `gradle.properties` file needs to be set correctly. Depending on which version of the SDK you have installed (ex. `1.1.2`), change the variable as shown in the screenshot below.

![sdkVersion variable in gradle.properties](images/sdk-version-gradle-property.png)

Run the project to deploy it onto an emulator or device.

## Known Issues

## How to obtain support

This project is provided "as-is".
If you have questions/comments/suggestions regarding this app please
post them using the tag [SAP Cloud Platform SDK for Android](https://www.sap.com/community/tag.html?id=73555000100800001281&tag=type:question).

## License

Use of the code is governed by the terms of the SAP sample code license agreement.
See [LICENSE](LICENSE) and [NOTICE](NOTICE).