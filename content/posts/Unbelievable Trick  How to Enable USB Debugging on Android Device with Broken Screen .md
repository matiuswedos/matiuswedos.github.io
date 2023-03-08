---
title: "Unbelievable Trick: How to Enable USB Debugging on Android Device with Broken Screen!"
ShowToc: true 
date: "2023-03-03"
author: "Paula Hughes" 
tags: ["Android","Software Troubleshooting"]
---
## Introduction

Have you ever encountered a situation where you need to enable USB debugging on an Android device with a broken screen? This can be a real headache as you cannot access the device's settings to enable USB debugging. Fortunately, there is a trick that can help you out. In this blog post, we will discuss how to enable USB debugging on Android devices with broken screens.

## Definition of USB Debugging

USB debugging is a feature that is used to allow communication between an Android device and a computer. It allows the computer to access the internal functions of the device and to transfer data between the two. This is usually used by developers to test and debug applications.

## Reasons for Enabling USB Debugging on Android Devices

There are many reasons why you might want to enable USB debugging on an Android device. It can be used to transfer data between the device and a computer, to unlock the device, to access the recovery mode, to root the device, to flash custom ROMs, and more.

## Steps to Enable USB Debugging on Android Devices with Broken Screen

### Preparation

Before you can enable USB debugging on an Android device with a broken screen, you will need to prepare the following:

- A computer with a USB port
- A USB cable
- The Android SDK Platform-tools

### Using ADB Command Line Tool

Once you have the necessary tools, you can use the ADB command line tool to enable USB debugging on your Android device. To do this, connect your device to the computer using the USB cable and then open the command line tool. Type in the following command:

adb devices

This will display a list of connected devices. Select the device you want to enable USB debugging on and then type in the following command:

adb shell

This will open a shell window on your computer. Type in the following command:

setprop sys.usb.config adb

This will enable USB debugging on your Android device.

### Using SDK Platform-Tools

You can also use the SDK Platform-tools to enable USB debugging on your Android device. To do this, connect your device to the computer using the USB cable and then open the SDK Platform-tools. Select the device you want to enable USB debugging on and then type in the following command:

adb shell

This will open a shell window on your computer. Type in the following command:

setprop sys.usb.config adb

This will enable USB debugging on your Android device.

## Conclusion

### Summary of Steps

To enable USB debugging on an Android device with a broken screen, you will need to prepare a computer with a USB port, a USB cable, and the Android SDK Platform-tools. Then, you can use the ADB command line tool or the SDK Platform-tools to enable USB debugging on your device.

### Benefits of Enabling USB Debugging

Enabling USB debugging on an Android device can be very useful. It can be used to transfer data between the device and a computer, to unlock the device, to access the recovery mode, to root the device, to flash custom ROMs, and more.

{{< youtube 0usgePpr8_Y >}} 
If you have ever been in the unfortunate situation of having a broken Android device with a non-functional screen, you know how difficult it can be to access the device's settings. However, there is a simple and unbelievable trick that can be used to enable USB Debugging on an Android device with a broken screen. By using a combination of ADB and a USB OTG cable, you can access the device's settings and enable USB Debugging. This trick can be a lifesaver in situations where you need to access data stored on the device or repair the device itself. With this trick, you can now access your Android device with a broken screen and get the data you need.

## Frequently Asked Questions (FAQ) :
Q1: What is USB Debugging?

A1: USB Debugging is a mode that allows an Android device to communicate with a computer so that developers can access the device. It is used for development purposes and can be enabled in the Developer Options menu on the device.

Q2: How do I enable USB Debugging on an Android device with a broken screen?

A2: You can enable USB Debugging on an Android device with a broken screen by using ADB commands. ADB stands for Android Debug Bridge and it is a command line tool used for communication between a computer and an Android device.

Q3: What do I need to do to use ADB commands?

A3: To use ADB commands, you need to install the Android SDK (Software Development Kit) on your computer. You can download the SDK from the Android Developer website.

Q4: How do I send ADB commands to my Android device?

A4: You can send ADB commands to your Android device by connecting it to your computer with a USB cable and then using the command line tool.

Q5: Is there any other way to enable USB Debugging on an Android device with a broken screen?

A5: Yes, you can also use a third-party tool such as scrcpy to enable USB Debugging on an Android device with a broken screen.


