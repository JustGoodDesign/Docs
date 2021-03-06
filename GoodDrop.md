GOOD DROP
===

[Good Drop](http://www.justgooddesign.com/products/unity3d/good-drop/) is a product of [Good Products](README.md) available in the [Unity Asset Store](https://www.assetstore.unity3d.com/#/content/5424).


#Authors#

[Jesse Graupmann](https://plus.google.com/113634720692058569075) | [Just Good Design](http://www.justgooddesign.com/)

<a target=_blank href="https://github.com/tgraupmann/TAGENIGMA-Docs">[Tim Graupmann]</a>


#Audience#

The core audience is intended for users with Android devices.

End users can use Good Drop without needing to write script or program.

Programmers can make use of the programming interfaces to extend functionality.


#Compatibility#

This project is targeted for Unity 3.5.7 or better.


#What is in Good Drop?#

With Good Drop you can distribute, install, run, uninstall, copy Android Packages to connected devices,

to wireless devices locally, and to devices over the Internet.

##Good Drop Panel##

The Good Drop panel can be accessed from the Window->Just Good Design->Good Drop menu item.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788463715.png?1373238943"/>

The Settings menu items handle the device cache, import, and export.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788466787.png?1373240063"/>

##Sub Menus##

###File Sub Menu###

In the file submenu you have a file list of recent apks that you've been working with.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788466259.png?1373239878"/>

###Device Sub Menu###

The device sub menu allows you to refresh the displayed list of connected Android devices.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788468551.png?1373240732"/>

###ADB Sub Menu###

The ADB gives you access to GUI that wraps the Android Debugger. Set the Android SDK path and then the menu can update to the latest adb. With adb you can start/stop the adb server and open an interactive shell. Open the ADB help for the full list of adb options.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788469064.png?1373240924"/>

###Split Sub Menu###

By default, the Good Drop panel opens with the split option off. This causes the files and devices sections to display in tabs.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788464225.png?1373239135"/>

Selecting the split option will cause the files and devices sections to display in the same panel.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788464662.png?1373239303"/>

###Help Sub Menu###

From the Help sub menu, there are quick links to the Good Drop documentation and helper links to Android documentation.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788469590.png?1373241136"/>

##Devices Tab##

Connected devices display in the devices tab. Devices can be connected via usb and wireless adb. The wireless subpanel can connect to Android devices in wireless mode using their IP address and port. Connected devices can be selected for use in the deploy tab.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788474831.png?1373243173"/>

###Device Info###

Each device has a popout which gives access to the device info which can be copied to the clipboard using the menu item.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788476660.png?1373243837"/>

###Refresh Packages###

From the device popup, the Refresh Packages gets a list of all the packages installed on the selected device.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788477414.png?1373244119"/>

###Download Packages###

When the package list has been refreshed, there is a menu item available to download each package. The menu item will open a File Save Dialog where the APK will be downloaded.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788478861.png?1373244663"/>

###Process Memory###

On the devices tab, using the popup the memory information for the bundle identifier is available by selecting the menu item.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788480736.png?1373245343"/>

###Remote Key Input###

From the Remote Key Input sub panel, the drop down sets the device focus. With the text field selected, keyboard presses are forwarded to the selected Android device.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788482947.png?1373246145"/>

Click the Buttons expander to show the available buttons to send to the remote Android device. Click the expanded buttons to send the KeyEvent to the remote Android device.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788483659.png?1373246388"/>

##Deploy Tab##

The deploy tab provides quick selection and remote deployment of Android packages. The panel supports drag/drop functionality from Windows Explorer and Mac Finder. APKs can also be added from the file menu. Additionally packages can be added with the "+" add button, and the "\" folder option will select an entire folder of packages. The run command will be applied to the selected devices on the devices tab. The run command is also affected by the selected packages on the deploy tab. The informational section displays the number of selected devices, the number of selected files, and the content size that will be sent during install to those devices. There are several run commands available: "Install and Run", "Install", "Uninstall", "Run", and "Kill Processes".

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788484768.png?1373246760"/>

Each package in the deploy tab has an open details popout where you can access the apk details and content.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788541091.png?1373265077"/>

###Time###

Deploying Android packages to devices can take several minutes depending on the file size that you are sending across. Keep an eye on the ADB info which can indicate sending gigabytes across USB can take some time.

<img src="http://d3j5vwomefv46c.cloudfront.net/photos/large/788503247.png?1373252884"/>

#Q & A#

You can send comments/questions to unity@justgooddesign.com and please rate this package.
