---
layout: post
title:  "Back from holidays: Configure DevSpace"
date:   2015-03-10 13:54:48
categories: third post
---

Hello Readers! 

It has been a long time since we updated our blog. The reason being we have our mid semester break and the team members were spending some quality time with there family members. So now without furthur ado, we have this blog post where we tell how to setup the development environment. 

Developing any software need a proper dev environment to work upon. Its one of the quintessential part of developing any software.
Here in this post, we discuss how we setup our development environment.

<h1>Installing and Configuring Support Tools</h1>

For being an Android App Developer, you need to install and configure few tools including software development kits (SDKs) : 

* **Java JDK** : Lays the foundation for the Android SDK. [JAVA]
* **Android SDK** : Provides access to Android Libraries and allow you to develop for Android.
* **Integrated Developement Environment (IDE)** : Brings together JAVA, Android SDK and Android Development Tools (ADT) and provides tools for you to write android programs.

<h3>Getting the Java Development Kit</h3>

Download and install the lastest JDK available from [Oracle Website][oracle].

We downloaded JAVA platform (8u40) including jdk1.8_40 and jre1.8_40.

Set up JAVA_HOME as environment variable to root directory of your Java JDK : **C:\Program Files\Java\jdk1.8_40**

That’s all there is to it. You have the JDK installed and are ready to move to the next phase. 

<h3>ANDROID SDK and IDE</h3>

Eclipse was used to be standard IDE for Android Development before Google launched their official Android IDE: <b>Android Studio</b>.

Android Studio is an intelligent code editor capable of advanced code completion, refactoring, and code analysis. It is built on IntelliJ IDEA Community Edition, the popular Java IDE by JetBrains.

Android Studio : 

* Flexible [Gradle-based][gradle] build system.
* Build variants and multiple APK generation.
* Expanded template support for Google Services and various device types.
* Rich layout editor with support for theme editing.
* Lint tools to catch performance, usability, version compatibility, and other problems.
* ProGuard and app-signing capabilities.
* Built-in support for Google Cloud Platform, making it easy to integrate Google Cloud Messaging and App Engine.

For more details about features available in Android Studio, read the guide to [Android Studio Basics][studio].

Download and setup Android Studio from the [developers website][devstudio]. Android Studio package includes : 

* Android Studio IDE
* Android SDK tools
* Android 5.0 (Lollipop) Platform
* Android 5.0 emulator system image with Google APIs

For downloading specific SDK for Android, open Android SDK manager from Android Studio and download required packages from the list of API levels.

Furthur details for setting up Android Studio and SDK are given at the [developers website][devstudio].

<h4>Setting up Emulator</h4>

Best way to develop apps, is to run on actual physical device. But for those who dont have an android device and still want to develop applications : Android Emulator is to their rescue.

The Android SDK includes a mobile device emulator — a virtual mobile device that runs on your computer. The emulator lets you develop and test Android applications without using a physical device.
But as the Android SDK emulator is very slow in emulation, we install third party emulator: **Genymotion**.
Genymotion is a fast and easy-to-use Android emulator to run and test your Android apps.

* Standard and integrated
* Genymotion plugins - Plugins for Eclipse and Android Studio.
* Compatible with all Android SDK tools: InstrumentationTestRunner, Hierarchy Viewer, Monkey, MonkeyRunner...
* Built from AOSP, optimized for speed, and validated against Compatibility Test Suite.

To download Genymotion: follow the steps to install on [https://www.genymotion.com/][genymotion].


With all these tools configured, we have our dev enviroment all setup.
Let's begin coding. 

[developer-hw-requirement]: http://developer.android.com/sdk/requirements.html
[oracle]: http://www.oracle.com/technetwork/java/javase/downloads/index.html
[gradle]: http://gradle.org/
[studio]: http://developer.android.com/tools/studio/index.html
[devstudio]: http://developer.android.com/sdk/index.html
[genymotion]: https://www.genymotion.com/