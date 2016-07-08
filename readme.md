## USB3Vision camera adapter/driver for Micro-manager 1.4

This hardware adapter allows cameras compliant with the USB3Vision standard to be used with Micro-manager 1.4.

The compiled adapter included under '/release/Win-32/' is compatible only with Micro-manager 1.4.22, 32-bit.

You may be able to build this adapter for other versions of Micro-manager 1.4.xx using the source C++ project files in '/source/'.

This adapter is largely based on the GigECamera adapter which interfaces with the JAI vision SDK. The GigECamera adapter only works with JAI SDK 1.4.1. However, the newer JAI SDK 2.1.6 can also interface with USB3Vision cameras, in addition to GigEVision cameras. This adapter features a handful of API updates which allow interfacing with the newer SDK from JAI, Inc.

The JAI SDK is available from their website here. You should download the SDK which matches your version of Windows (32- or 64-bit).
http://www.jai.com/en/support/jai_sdk_and_control_tool

This has been tested only with the following USB3Vision camera from Point Grey:
https://www.ptgrey.com/grasshopper3-6-mp-mono-usb3-vision-sony-icx694-camera


## Troubleshooting:
Before you get too excited, verify that your camera is operable using the JAI Control tool, which is included with the JAI SDK. It has very nice documentation here:
http://www.jai.com/SiteCollectionDocuments/Camera_Solutions_Manuals/JAI-SDK-Getting-Started-Guide_revL.pdf