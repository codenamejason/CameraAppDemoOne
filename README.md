Camera
====================
<a href="https://platform.telerik.com/#appbuilder/clone/https%3A%2F%2Fgithub.com%2FIcenium%2Fsample-camera" target="_blank"><img src="http://docs.telerik.com/platform/samples/images/try-in-appbuilder.png" alt="Try in the Platform" title="Try in the Platform" /></a>  

<a id="top"></a>
* [Overview](#overview)
* [Screenshots](#screenshots)
* [Test the Sample](#test-the-sample)
* [Limitations](#limitations)

# Overview

This sample shows you how to use the Camera core plugin to access the camera and the image gallery of the mobile device.

> *Supported mobile platforms:* iOS 7.1+, Android 4.4+, Windows Phone 8.1+
>
> *Developed with:* Windows Phone SDK 8.1, Apache Cordova 4.0.0

[Back to Top](#top)

# Screenshots

Platform | Home 
---|---
All | ![](screenshots/home.jpg)

[Back to Top](#top)

# Test the Sample

Apart from exploring the sample code base in GitHub, you can also clone and run the sample in your preferred AppBuilder client.

## In-Browser

With the AppBuilder in-browser client, you can develop hybrid and NativeScript cross-platform mobile apps from your browser. You can use the in-browser client at [https://platform.telerik.com](https://platform.telerik.com).

### Clone the sample

1. Click the button at the top of this document.
1. Provide your login credentials, if prompted.

### Run the sample

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Deploy on device via QR code.][QR code]

[Back to Top](#top)

## Windows

With the AppBuilder Windows client, you can develop hybrid and NativeScript cross-platform mobile apps from your Windows desktop. You can download and install the Windows client from [http://www.telerik.com/appbuilder/windows-client](http://www.telerik.com/appbuilder/windows-client).

### Clone the sample

1. Verify that the AppBuilder Windows client is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. In the dashboard, click **Samples** and select **Hybrid**.
1. From the **Workspace** drop-down menu, select the workspace in which you want to develop your application.
1. Select **Core APIs**.
1. Select **Camera**.
1. (Optional) Rename the project.
1. Click **Clone**.

### Run the sample

With the AppBuilder Windows client, you can quickly test your apps on device, in the device simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## Visual Studio

With the AppBuilder extension for Visual Studio, you can develop hybrid and NativeScript cross-platform mobile apps from Microsoft Visual Studio. You can download and install the extension from [http://www.telerik.com/appbuilder/visual-studio-extension](http://www.telerik.com/appbuilder/visual-studio-extension).

### Clone the sample

1. Verify that the AppBuilder extension for Visual Studio is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. Select **AppBuilder** &#8594; **Get Sample**.
1. Select **Hybrid**.
1. Select **Core APIs**.
1. Select **Camera**.
1. (Optional) Rename the project.
1. Click **Get**.

The extension for Visual Studio copies the sample files locally. The extension creates a new solution and project and loads them.

### Run the sample

With the AppBuilder extension for Visual Studio, you can quickly test your apps on device, in the device simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## CLI

With the AppBuilder command-line interface, you can develop hybrid and NativeScript cross-platform mobile apps from the command line. You can learn how to add the AppBuilder commands to your command line from [http://www.telerik.com/appbuilder/command-line-interface](http://www.telerik.com/appbuilder/command-line-interface).

### Clone the sample

1. Verify that a command prompt is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. To list the available samples, run the following command.

	```bash
	appbuilder sample
	```
1. Run the clone command for the sample as listed by `appbuilder sample`.
	
	```bash
	appbuilder sample clone camera
	```

The AppBuilder command-line interface shows the following message: `Successfully initialized project in the folder!`

### Run the sample

With the AppBuilder command-line interface, you can quickly test your apps on device or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

# Limitations

* You can run this sample in the device simulator but the Camera API is not fully supported there. In the simulator, you can only get pictures from your file system.
* On Android devices, **Photo Library** and **Photo Album** show the same photo album.
* On Android devices, you cannot use **Take Editable Photo**.

[Back to Top](#top)

[device simulator]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-apps-in-simulator/launch-simulator
[companion]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/run-companion/using-appbuilder-companion-app
[QR code]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/deploy-remote
[USB deploy]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/running-on-connected-devices/deploy-connected
[emulators]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-in-emulators/native-emulators