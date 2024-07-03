---
title: How to Show Wi-Fi Password on Huawei P60
date: 2024-06-16T17:52:40.022Z
updated: 2024-06-17T17:52:40.022Z
tags: 
  - unlock
  - remove screen lock
categories:
  - android
description: This article describes How to Show Wi-Fi Password on Huawei P60
excerpt: This article describes How to Show Wi-Fi Password on Huawei P60
keywords: samfw frp tool,how to lock apps on android device,Huawei P60 locked out of android phone,Huawei P60 how to remove previously synced google account from android,Huawei P60 disable lock screen,Huawei P60 forgot pattern lock,bypass android device face lock,android device manager unlock,Huawei P60 unlock phone forgot password,Huawei P60 bypass knox enrollment service
thumbnail: https://thmb.techidaily.com/8e684e3736085a42393dd155a637e8f217c26c390b45353b04f9ee1e79b6412e.jpg
---

## How to Show Wi-Fi Password on Huawei P60

Since the invention of Android OS in 2008 by Andy Rubin, our world has faced a dramatic change. Android seems to be controlling a considerably high portion of our life. We have bought many gadgets that use this amazing OS and most of which are phones. But how much can you do with your Android phone? Developers are always making it more interesting to use this interface.

Most of the time, we use Android phones, we get faced with the need to access the internet. The Wi-Fi capability of these Android gadgets makes it super easy for us to surf the web. Throughout using Wi-Fi, we connect to a number of them. This could be at school, a sub-way café, the gym, buses, hospitals, hotels, towns, and the list is endless. A password secures most of this. Needless to say, our brain is weak to store all these passwords for future use, especially if you would want to connect with a different gadget you have recently bought or even your laptop. In this article, we will introduce you to how to find wifi password on rooted and also unrooted Android devices.

<iframe allowfullscreen="allowfullscreen" frameborder="0" src="https://www.youtube.com/embed/78mNMIr_wpI"></iframe>

## Part 1: Show Wifi Password on Rooted Android Device

### What is Rooting?

First of all, what does rooting mean? You have probably used a Windows computer or even Linux. For the case of Windows, when installing a new program or software, it always prompts a dialog box saying, "Administrator permission required to run this program." If you don't have the administrator permission, you won't install the program. In Android, this is called rooting. In simple terms, it means having the root permission to your phone. Some Android apps will require you the root permission, e.g., flashing your ROM. In this part, we will explain how you can show the Wi-Fi password on your Android with root.

To find the Wi-Fi passwords on your Android phone, you need to have an app to explore files which also supports a root user. In this case, ES FileExplorer or Root Explorer will come in handy. However, it turns out that the latter is offered at $3. Let's use the free ES File Explorer.

![android show wifi password](https://images.wondershare.com/drfone/others/14556285763404.jpg)

### Steps of getting Wi-Fi password on Android with root

In only four steps, we, at this moment, learn how we can find the password of a Wi-Fi on an Android phone.

Step 1: Install the ES File Explorer

Download the ES File Explorer from your play store, install it, and open it.

![android show wifi password](https://images.wondershare.com/drfone/others/14556286507084.jpg)

Step 2: Enable Root Explorer

The root explorer needs to be enabled so that you can reach the root folders of the Wi-Fi passwords you need. By default, the root feature in this ES explorer is not enabled. To enable it, just tap on the list menu on the top left corner.:

![android show wifi password](https://images.wondershare.com/drfone/others/14556292611536.jpg)

This will drop down a list of controls. Scroll down and find the **Root Explorer** option and enable it.

![android show wifi password](https://images.wondershare.com/drfone/others/14556293052566.jpg)

Step 3: Get the passwords' file.

Go back to ES file explorer, and this time, find the folder named **data**.

![android show wifi password](https://images.wondershare.com/drfone/others/14556293412707.jpg)

When this folder opens, find another one named **misc**. Open it and find another one named **wifi**. Here, find a file named **wpa\_supplicant.conf**.

![android show wifi password](https://images.wondershare.com/drfone/others/14556293762552.jpg)

Step 4: Retrieve the wifi password on Android

Make sure that you don't edit anything in the file. You might mess up with important data and fail to access the Wi-Fi(s) in the future.

![android show wifi password](https://images.wondershare.com/drfone/others/14556294042257.jpg)

As you can see above, we have found the Wi-Fi passwords on the android device. On each network profile, we have the name of the network represented by _name (ssid="{the name}")_, the network's password represented by _psk_, the network's access point represented by _key\_mgmt=WPA-PSK_ and its priority represented by _priority_.

## Part 2: Show Wifi Password on Android without Root

What if I don't have root access to my Android, can I still see Android Wi-Fi password? The short answer is yes. However, this is a bit involving but simple. You don't need to be a computer guru to do it, but you need to have a computer and some internet access of course. The key thing is to find a way through which we can fetch the password file from the phone without using a root access protocol in the Android. This is made possible by some little programming insight using the Windows Command prompt.

### Steps to show Wi-Fi password on Android without root

Step 1: Access the Developer authority

To access the files that Android uses to run passwords, you must first become a developer. This is very simple.

Get your Android phone and go to settings. Scroll down and find "About phone." Tap on it and scroll down again to find Build number.

![android show wifi password](https://images.wondershare.com/drfone/others/14556302638925.jpg)

Tap on this "build number" 5 to 6 times until a message pops up, saying, "You are now a developer".

![android show wifi password](https://images.wondershare.com/drfone/others/14556303263992.jpg)

Step 2: Enable the debugging.

Go back to Settings. Scroll down for developer options. Turn on the button for "Android/USB debugging".

![android show wifi password](https://images.wondershare.com/drfone/others/14556308665697.jpg)

Step 3: Install ADB drivers.

Now, open your Windows desktop. Download and install ADB drivers. (Use this download link [adbdriver.com](http://adbdriver.com/)). You need to download and install platform tools (minimal ADB and fastboot) from [http://forum.xda-developers.com/...](http://forum.xda-developers.com/showthread.php?t=2317790) Now open the folder where you've installed the above tools. By default, it is in the Local disc _C\\windows\\system32\\platform\_tools_ location. However, you might want to locate them by searching on the windows search engine. You have to hold the Shift key and right-click inside the folder to click on"Open Command Window Here."

![android show wifi password](https://images.wondershare.com/drfone/others/14556329561742.jpg)

Step 4: Test the ADB

Here, we would like to test whether the ABD is working properly. To do this, connect your phone to the PC using a USB. In the command prompt, type **adb services** and then press enter. If it's working properly, you should see a device on this list.

![android show wifi password](https://images.wondershare.com/drfone/others/14556329984622.jpg)

Step 5: Find the Android wifi password.

Now, it is time to type the given command in the command prompt and type: _adb pull /data/misc/wifi/wpa\_supplicant.conf c:/wpa\_supplicant.conf_. This will fetch the file from your phone to the local disc C drive of the PC.

Step 6: Get the wifi passwords.

Lastly, open the file with a notepad, and there you go.

![android show wifi password](https://images.wondershare.com/drfone/others/14556331232772.jpg)

Now you learned how to show the wifi password on your Android device.

## 6 Solutions to Unlock Huawei Phones If You Forgot Password, PIN, Pattern

Too many times, we forget the passcode of our smartphones, only to regret it later. Don't worry if you are facing the same issue. It happens to all of us at times. Fortunately, there are many ways to unlock an Android device even when you have **forgotten its password/pin/pattern lock**. This guide will teach you how to unlock Huawei phones if you forgot the password in five different ways. Read on and choose your preferred option if you forgot the password on your Huawei phone and move past every setback you face.

<iframe width="560" height="315" src="https://www.youtube.com/embed/68FqgS6Ym8E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>


## Solution 1: Unlock Huawei Phone using Dr.Fone - Screen Unlock (5 mins solution)

Among all the solutions we are going to introduce in this article, this is the easiest one. [Dr.Fone - Screen Unlock (Android)](https://tools.techidaily.com/wondershare-dr-fone-unlock-android-screen/) can help you remove the lock screen of [some Huawei and Samsung devices](https://drfone.wondershare.com/reference/android-lock-screen-removal.html) without any data loss. After the lock screen is removed, the phone will work like it's never been locked before, and all your data are there. Besides, you can use this tool to bypass the passcode on other Android phones, such as Huawei, Lenovo, Oneplus, etc. The only defect of Dr.Fone is that it will erase all the data beyond Samsung and Huawei after unlocking.

![arrow](https://drfone.wondershare.com/style/images/arrow_up.png)

### [Dr.Fone - Screen Unlock (Android)](https://tools.techidaily.com/wondershare-dr-fone-unlock-android-screen/)

Get into the Locked Huawei Phone within Minutes

- Available for most Huawei series, like LG/LG2/LG3/G4, etc.
- Except for Huawei phones, it unlocks 20,000+ models of Android phones & tablets.
- Everybody can handle it without any technical background.
- Offer customized removal solutions to promise good success rate.

**4,008,669** people have downloaded it

### How to unlock an Huawei phone with Dr.Fone - Screen Unlock (Android)?

Step 1. Launch Dr.Fone.

Download Dr.Fone from the download buttons above. Install and launch it on your computer. Then select the "**Screen Unlock**" function.

![unlock lg phone - launch drfone](https://images.wondershare.com/drfone/guide/drfone-home.png)

Step 2. Connect your phone.

Connect your Huawei phone to the computer using a USB cable. Click on **Unlock Android Screen** on Dr.Fone.

![unlock lg phone - connect phone](https://images.wondershare.com/drfone/guide/android-screen-unlock-3.png)

Step 3. Select the phone model.

Currently, Dr.Fone supports removing lock screens on some Huawei and Samsung devices without data loss. Select the correct phone model information from the dropdown list.

![unlock lg phone - select phone model](https://images.wondershare.com/drfone/guide/screen-unlock-any-android-device-2.png)

Step 4. Boot the phone in download mode.

- Disconnect your Huawei phone and power it off.
- Press the Power Up button. While you are holding the Power Up button, plug in the USB cable.
- Keep pressing the Power Up button until the Download Mode appears.

![unlock lg phone - boot in download mode](https://images.wondershare.com/drfone/guide/android-screen-unlock-without-data-loss-4.png)

Step 5. Remove the lock screen.

After your phone boot in download mode, click on Remove to start to remove the lock screen. This process only takes a few minutes. Then your phone will restart in normal mode without any lock screen.

![unlock lg phone - remove lock screen](https://images.wondershare.com/drfone/guide/screen-unlock-any-android-device-6.png)

For more detailed steps, please go to our guide on [unlocking Android phones with/without data loss](https://drfone.wondershare.com/guide/android-lock-screen-removal.html).

## Solution 2: Unlock the Huawei Phone Using Android Device Manager (Need a Google account)

This is probably the most convenient solution to set up a new lock for your Huawei device. With Android Device Manager, you can locate your device, ring it, erase its data, and even change its lock remotely. All you got to do is log in to the Huawei P60 device Manager account using the credentials of your Google Account. Needless to say, your Huawei phone should be linked to your Google Account. Learn how to unlock the Huawei phone if forgot your password using Android Device Manager.

- **Step 1.** Start by logging in to [Android Device Manager](https://www.google.co.in/android/devicemanager) by entering the credentials of your respective Google Account that is configured with your phone.

![unlock lg forgot password - login android device manager](https://images.wondershare.com/drfone/article/2017/03/14892201986480.jpg)

- **Step 2.** Select your device's icon to get access to various features like ring, lock, erase, and more. Out of all the provided options, click on “**lock**” to change the security lock of your device.

![unlock lg forgot password - select device](https://images.wondershare.com/drfone/article/2017/03/14892202439511.jpg)

- **Step 3.** Now, a new pop-up window will open. Here, provide the new password for your device, confirm it, and click on the “lock” button again to save these changes.

![unlock lg forgot password - lock with new password](https://images.wondershare.com/drfone/article/2017/03/14892202692339.jpg)

That's it! Your phone will reset its password, and you would be able to move past any problem related to forgetting the password on the Huawei phone using [Android Device Manager unlock](https://drfone.wondershare.com/unlock/android-device-manager-unlock.html).

## Solution 3: Unlock the Huawei Phone Using Google Login (only Android 4.4 and below)

If your Huawei device runs on Android 4.4 and previous versions, then you can easily move past the password/pattern lock without any trouble. The provision is not available on devices, which run on newer versions of Android. Nevertheless, for all the Huawei P60 devices running on older versions than Android 4.4, this is undoubtedly the easiest way to set a new passcode. Follow these steps to learn how to unlock your Huawei phone if you forgot your password using your Google credentials.

- **Step 1.** Try bypassing the pattern lock at least 5 times. After all the failed attempts, you will get the option to either make an emergency call or choose the option of “**Forget pattern**”.

![unlock lg forgot password - forgot pattern](https://images.wondershare.com/drfone/article/2017/03/14892203178747.jpg)

- **Step 2.** Select the “Forget pattern” option and provide the correct credentials of your Google account to unlock your phone.

![unlock lg forgot password - log in google account](https://images.wondershare.com/drfone/article/2017/03/14892203377058.jpg)

## Solution 4: Unlock the Huawei Phone Using Custom Recovery (SD card needed)

If your phone has a removable SD card, you can also try this technique to disable the pattern/password on your device. Though, you need to have some custom recovery installed on your device for this method. You can always go for TWRP (Team Win Recovery Project) and flash it on your device.

TWRP: <https://twrp.me/>

Also, since you can't move anything to your device when it is locked, you need to do the same using its SD card. After ensuring that you have met all the basic prerequisites, follow these steps and learn how to unlock the Huawei phone's forgotten password using a custom recovery.

- **Step 1.** Download a [Pattern Password Disable](http://forum.xda-developers.com/attachment.php?attachmentid=2532214&d=1390399283) application and save its ZIP file on your computer. Now, insert your SD card into your system and move the recently downloaded file to it.

- **Step 2.** Reboot your phone into recovery mode. For instance, the TWRP recovery mode can be turned on by simultaneously pressing the Power, Home, and Volume Up button. You would get different options on your screen after entering the custom recovery mode. Tap on “Install” and browse the Pattern Password Disable application file.

![unlock lg forgot password - team win recovery project](https://images.wondershare.com/drfone/article/2017/03/14892204165153.jpg)

- **Step 3.** Install the above-mentioned application and wait for a few minutes. Afterward, restart your Huawei phone. Ideally, your phone will be restarted without any lock screen. If you get a lock screen, you can bypass it by entering any random digits.

## Solution 5: Factory Reset Huawei Phone in Recovery Mode (erases all phone data)

If none of the above-mentioned alternatives work, then you can also try to factory reset your device. This will erase every kind of data from your device and make it look brand new by resetting it. Though, you can easily resolve the forgot password on the Huawei phone with it. Therefore, before proceeding, you need to be familiar with all the repercussions of performing a factory reset. All you got to do is follow these steps.

- **Step 1.** Put your Huawei phone on its recovery mode with correct key combinations. To do this, firstly, turn your device off and let it rest for a few seconds. Now, press the Power and Volume Down key at the same time. Keep pressing them until you see LG's logo on the screen. Release the buttons for a few seconds and press them again at the same time. Again, keep pressing the buttons until you see the recovery mode menu. This technique works with most Huawei devices, but it can differ slightly from one model to another.

- **Step 2.** Choose “Wipe Data/Factory Reset.” You can use the Volume up and down key to navigate the options and the power/home key to select anything. Use these keys and select the “Wipe Data/Factory Reset” option. You might get another pop-up asking to delete all user data. Just agree it reset your device. Sit back and relax as your device will perform a hard reset.

![unlock lg forgot password - enter in recovery mode](https://images.wondershare.com/drfone/article/2017/03/14892204518630.jpg)

- **Step 3.** Select the “Reboot system now” option to restart it. Your phone will be restarted without any lock screen.

![unlock lg forgot password - reboot system](https://images.wondershare.com/drfone/article/2017/03/14892204671940.jpg)

After following these steps, you can easily overcome how to unlock the Huawei phone forgot password issue.

## Solution 6: Unlock Huawei Phone Using ADB Command (need USB debugging enabled)

This might be a little complicated initially, but if you don't want to follow either of the above-mentioned techniques to unlock your device, you can go with this alternative. Before proceeding, make sure that you have ADB (Android Debug Bridge) installed on your computer. If you don't have it, then you can download Android SDK right [here](https://developer.android.com/studio/index.html).

Additionally, it would help if you turned on the USB Debugging feature on your phone before you forgot the password. If USB debugging is not turned on before, then this method will not work for you.

After making your device ready and downloading all the essential software on your computer, follow these steps to learn how to unlock your Huawei phone if you forgot the password.

- **Step 1.** Connect your device to the computer with a USB cable and open the command prompt when it is successfully connected. If you get a pop-up message regarding USB Debugging permission on your device, simply agree to it and continue.

- **Step 2.** Now, please provide the following code on the command prompt and reboot your device when it is processed. If you want, you can also tweak the code a little and provide a new lock pin.

- _ADB_ _shell_
- _cd /data/data/com.android.providers.settings/databases_
- _sqlite3 settings.__db_
- _update system set value=0 where name='lock\_pattern\_autolock';_
- _update system set value=0 where name='lockscreen__.lockedoutpermanently';_
- _.quit_

![unlock lg forgot password - command code](https://images.wondershare.com/drfone/article/2017/03/14892205231542.jpg)

- **Step 3.** If the above code doesn't work, try providing the code “ADB _shell rm /data/system/gesture. the key_” to it and follow the same drill.

![unlock lg forgot password - code](https://images.wondershare.com/drfone/article/2017/03/14892205424871.jpg)

- **Step 4.** After restarting your device, if you still get a lock screen, then give a random password to bypass it.

## Conclusion

You can choose a preferred option and rectify the issue whenever you [forgot the password on the Huawei phone](https://tools.techidaily.com/wondershare-dr-fone-unlock-android-screen/). Make sure that you meet all the requirements and go through the respective tutorial to attain fruitful results.

## How to Unlock Huawei P60  PIN Code/Pattern Lock/Password

_I have forgotten the pattern, PIN, or password needed to unlock my Huawei P60  smartphone. What should I do?_

If you have a Huawei P60  phone and have forgotten the screen unlock PIN code, pattern lock, or password, you can still access it using some tried and tested tricks and hacks. This article will discuss 5 different ways on how to unlock **Huawei P60  smartphone**. Some methods might work without erasing your data, while others, like factory resetting, may erase all content from your phone. Regardless of which method you use, you will be able to unlock your phone! So, let’s get started!

## 1\. How to Unlock Huawei P60  With Google Find My Huawei P60?

A way to unlock the Huawei P60  phone is via Google Find My Device feature. While this method can help unlock your phone, it erases all content from it.

For this method, you need a PC and your Google account details. Here are the steps for it:

**Step 1:** Open your browser and go to [Google Find My Device](https://www.google.com/android/find) on your PC.

![google account verification](https://images.wondershare.com/drfone/article/2022/05/google-account-verification.jpg)

**Step 2:** Log in to the Google account you used to set up your Huawei P60  phone.

**Step 3:** It will show you 3 options: Play Sound, Secure Device, and Erase Device.

![find my device](https://images.wondershare.com/drfone/article/2022/05/google-find-my-device.jpg)

 And then select “**Erase Device.**”

![select erase data](https://images.wondershare.com/drfone/article/2022/05/select-erase-device.jpg)

Selecting this option will erase all content from your device, including screen unlock PIN, password, and pattern.

**Step 4:** Now, you can access your phone without an unlock PIN or pattern and set a new one.

Use this method only if your phone is backed up so you can restore all your data later.

## 2\. How to Unlock Android device Using Lock Remove Tool?

Another foolproof method on how to unlock Android pattern lock is by using a lock removal tool like [Dr.Fone - Screen Unlock (Android)](https://tools.techidaily.com/wondershare-dr-fone-unlock-android-screen/).

<iframe allowfullscreen="allowfullscreen" frameborder="0" src="https://www.youtube.com/embed/QWpE8NykOWc"></iframe>

![Safe download](https://images.wondershare.com/drfone/article/2022/05/security.svg)safe & secure

Dr.Fone - Screen Unlock is a screen unlock tool that can unlock your Android phone if you forget its screen unlock PIN, password, or pattern in just 5 minutes. It has a simple operation that requires just a few clicks to unlock your phone screen. Plus, this method is reliable, secure, and has a high success rate. However, there’s a possibility that it might not work with older phone models.

![arrow](https://drfone.wondershare.com/style/images/arrow_up.png)

### [Dr.Fone - Screen Unlock (Android)](https://tools.techidaily.com/wondershare-dr-fone-unlock-android-screen/)

Unlock Android PIN Code/Pattern Lock/Password within Minutes

- Remove all Android screen locks (PIN/pattern/fingerprints/face ID) in minutes.
- Unlock 20,000+ models of Android phones & tablets.
- Everybody can handle it without any technical background.
- Save you from ending up with a locked phone after too many pattern attempts.

**4,008,669** people have downloaded it

Here are the steps to unlock Android phone using Dr.Fone - Screen Unlock (Android):

**Step 1:** Launch Dr.Fone on your PC and select the “Screen Unlock” option from the main page.

**Step 2:** Connect your phone to your PC with a USB cable. Now click on the "Android" > "Unlock Android Screen" option.

![connect device to remove android lock screen](https://images.wondershare.com/drfone/guide/android-screen-unlock-3.png)

**Step 3:** A device brand will appear. Select your phone’s brand, i.e., Samsung.

![select device model](https://images.wondershare.com/drfone/guide/screen-unlock-any-android-device-2.png)

**Step 4:** Now, follow the instructions as you see to unlock your Android device.

![begin to remove android lock screen](https://images.wondershare.com/drfone/guide/unlock-android-screen-google.png)

Your phone is now unlocked, and you can access it without entering a PIN, password, or pattern.

![android lock screen bypassed](https://images.wondershare.com/drfone/guide/screen-unlock-any-android-device-6.png)

Now, if you don’t remember your Google account details and don’t have access to a PC to use a screen unlock tool, you can unlock Android phone using the conventional way.


## How to Unlock Huawei P60  with Google Account?

Almost all Android smartphones, including Huawei P60 , require you to enter your Google account details when setting up your phone for the first time. This includes the email, password, and security question. These details come in handy later on in situations where your phone is lost or stolen or if you’re switching to another phone. However, they can also help with basic issues like unlocking your phone in case you forget your Huawei P60  screen unlock PIN, pattern, or password.

You can unlock your Huawei P60  phone with Google Account in the following two ways:

- Using Google account details
- Using Google security question

![unlock sony xperia](https://images.wondershare.com/drfone/article/2022/05/how-to-unlock-sony-xperia.png)

### Using Google Account Details

Almost all Android smartphones, including Huawei P60 , require you to enter your Google account details when setting up your phone for the first time. This account comes in handy later on in situations where your phone is lost or stolen or if you’re switching to another phone. However, it can also help with basic issues like unlocking your phone in case you forget your Huawei P60  screen unlock PIN, pattern, or password. But to use this method successfully, you need to remember the email address bound to the Huawei P60 device and its password.

Here's how to unlock the Huawei P60  pattern lock without losing data using your Google account:

- **Step 1:** Enter the incorrect PIN, pattern, or password 5 times, and click on “Forgot Password” or “Forgot Pattern.”
- **Step 2:** The interface will then ask you to enter your Google account details as an alternate option. Enter the Google account details you used when setting up your Huawei P60  phone.
- **Step 3:** This will unlock your phone. You can now reset the screen unlock PIN, password, or pattern.

If you don't remember your Google account details, you can still unlock your Huawei P60  phone using a third-party tool.

### Using Security Question

Another way to unlock your Huawei P60  phone using Google is by answering the security question. When we set up our Google account, we usually choose a security question and an answer. This comes in handy if you want to recover your Google account, reset the password, or if you want to unlock your phone's screen.

For the latter, here are the steps:

- **Step 1:** Enter the incorrect PIN or pattern to unlock your screen several times till you see the “Forgot Pattern” or “Forgot Password” option. Click on it.
- **Step 2:** Now select the “Answer Security Question” option and type in the answer.
- **Step 3:** Click on “Unlock” after which you will be asked if you want to set a new PIN or pattern. Select “Yes.”
- **Step 4:** Your Huawei P60  phone will be unlocked, and you can set a new PIN or pattern for your screen.

## How to Unlock Huawei P60  by Hard Reset?

Hard resetting your smartphone usually solves everything! Hence, it can also help you unlock your Huawei P60  phone; however, using this method will erase all the data on your phone. So, if you still want to unlock Huawei P60  phone using this method, only do so if you have backed up your device and have no other way to unlock your phone. This includes forgetting your Google account details or not having access to a PC to download and use Dr Fone - Screen Unlock (Android).

Here are the steps for it:

- **Step 1:** Power off your Huawei P60  phone.
- **Step 2:** Press and hold the power and volume down button until the Sony screen appears.
- **Step 3:** The “System Recovery” menu will appear. Use the volume up and down button to scroll to the “Factory Reset” option. Use the power button to select this option.
- **Step 4:** Select “Yes” when asked for confirmation.

Your Huawei P60  phone will be hard reset, and all the locks will be removed. When you turn it on again, you will have to set it up like a new phone using your Google account details.

## How to Unlock Huawei P60  with Huawei  Companion?

If you've forgotten the screen lock of your Huawei P60  device, you can use Sony's official software, Huawei  Companion, to unlock your device. Huawei  Companion is a reliable method that can help you regain access to your Huawei  without data loss. Here's how to unlock your Huawei P60  using Huawei  Companion:

**Step 1:** Install and launch Huawei P60  Companion from the official website and click “Support Zone.” Move to the "Phone/Tablet Software Update" option on the next screen and tap "Start."

![press the start button](https://images.wondershare.com/drfone/article/2023/10/unlock-sony-xperia-pin-code-1.jpg)

**Step 2:** Now, plug in your laptop to power, as the process will take some time, and choose "repair my phone/tablet." Here, agree to the warning that you will lose your data and click “Next” to proceed.

![tap repair my phone tablet](https://images.wondershare.com/drfone/article/2023/10/unlock-sony-xperia-pin-code-2.jpg)

**Step 3:** Allow the program to download files to prepare for the update process and choose your Huawei P60  model. Click “Next” and connect your Huawei P60  to the PC. Ensure that the phone is turned off, and press and hold the "Volume Down" button when connecting the cable to the phone.

![preparing the computer](https://images.wondershare.com/drfone/article/2023/10/unlock-sony-xperia-pin-code-3.jpg)

**Step 4:** Once correctly connected to the PC, the program will download the necessary software and upload it to your device. After completing the process, you can unplug the Huawei P60 device and turn it on.

![updating the xiaomi device](https://images.wondershare.com/drfone/article/2023/10/unlock-sony-xperia-pin-code-4.jpg)

## How to Remove Operator Lock on Huawei P60 ?

An operator lock, also called a carrier lock, constitutes a limitation imposed on a mobile phone by a network provider. This measure is implemented to guarantee that the Huawei P60 device exclusively functions with the services provided by that specific carrier. If you wish to remove the operator lock from your Huawei P60  device, you'll need to follow specific steps and meet certain criteria. Here's how to remove the operator lock on a Huawei P60 :

**Step 1:** Begin by checking whether your device can be unlocked or not from its network carrier restrictions. To do that, you need to dial the code “\*#\*#7378423#\*#\*” on your device, tap “Service Info” and select “SIM Lock.”

![dial the provided number](https://images.wondershare.com/drfone/article/2023/10/unlock-sony-xperia-pin-code-5.jpg)

**Step 2:** Carefully check the information provided on the screen. If there is "X" before the "Network" option and the number in front of it is larger than 0, it means your device can be unlocked. If the number in front of "Network" is 0, your device can't be unlocked as it is hard-locked.

![check the network status](https://images.wondershare.com/drfone/article/2023/10/unlock-sony-xperia-pin-code-6.jpg)

**Step 3:** The next step involves getting your device’s IMEI number. To accomplish this task, simply input "\*#06#" on your device. Once you have the IMEI number, use a reliable service from the internet to the unlocking code. Insert the SIM card of another network and provide the code you gained to unlock your Huawei P60  device.

![enter the sim unlock code](https://images.wondershare.com/drfone/article/2023/10/unlock-sony-xperia-pin-code-7.jpg)

## Bonus Tip: How to Unlock Bootloader?

Unlocking the bootloader on your Android device provides significant advantages. These actions encompass obtaining root access, installing custom ROMs, configuring custom recoveries, and carrying out advanced procedures. Here's an essential guide on unlocking the bootloader of your Sony device while keeping all precautions in mind:

**Step 1:** To start with the process, verify the bootloader status for your Sony smartphone. On opening the "Dialer" app, dial the number "\*#\*#7378423#\*#\*" and access the "Rooting Status" option within the "Service Provider" settings.

**Step 2:** If the bootloader status displays "Yes," ensure that the Sony USB drivers and ADB tools are installed on your computer. Enable "USB Debugging" and "OEM Unlocking" on your smartphone and switch it off.

**Step 3:** Connect the Huawei P60  smartphone with a USB cable and press the "Power + Volume Up" keys for a few seconds. Open the Windows computer and access the "Devices and Printers" directory. Right-click on the "fastboot driver" file, select "Update," and select the location of the "android\_winbus.inf" file. Verify the fastboot connectivity through the CMD command.

**Step 4:** Open the official “Sony Unlocking Site” and add in the IMEI number. On acknowledging, use the commands as follows: `adb reboot bootloader`

Unlock the bootloader with the following command: `fastboot oem unlock 0x<insert your unlock code`

Verify the bootloader is unlocked and use the command to reboot the system; if not done automatically: `fastboot reboot`

## Conclusion

Forgetting your Huawei P60  screen unlock password, PIN, or pattern is quite common. For such instances, there are several methods that you can use to unlock your screen, 5 of which we have discussed in this article.

If you’re looking for ways that are time-effective and reliable, you can use your Google account or other ways to unlock Huawei P60  and set a new screen lock. However, with these methods, you can lose your data, so we only recommend using them if your device is backed up.




<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-tutorial-to-bypass-your-samsung-galaxy-f04-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Samsung Galaxy F04 Face Lock?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-vivo-t2-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Vivo T2 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-samsung-galaxy-s24-ultra-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Samsung Galaxy S24 Ultra Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-samsung-galaxy-s23-fe-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Samsung Galaxy S23 FE? Try These Fixes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-vivo-s17-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Vivo S17 Pattern Lock Screen</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-oppo-reno-11f-5g-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Oppo Reno 11F 5G</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-vivo-v29-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Vivo V29 Phone Pattern Lock</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-samsung-galaxy-f54-5g-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Samsung Galaxy F54 5G</u></a></li>
<li><a href="https://android-unlock.techidaily.com/lock-your-samsung-galaxy-a24-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Samsung Galaxy A24 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-5-easy-ways-to-multiply-your-youtube-follower-base/"><u>[New] In 2024, 5 Easy Ways to Multiply Your YouTube Follower Base</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-advanced-techniques-for-mov-file-editing-in-win-11-for-2024/"><u>[New] Advanced Techniques for MOV File Editing in Win 11 for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/proxy-perfection-top-video-editing-software-for-4k-creators/"><u>Proxy Perfection Top Video Editing Software for 4K Creators</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-dont-miss-out-the-creme-de-la-creativite-in-tiktok-top-10/"><u>[Updated] 2024 Approved  Don't Miss Out  The Crème De La Créativité in TikTok (Top 10)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-easy-recording-tips-for-your-hp-laptops-camera/"><u>[Updated] Easy Recording Tips for Your HP Laptop's Camera</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-from-your-apple-iphone-13-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID From your Apple iPhone 13 without Security Questions?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-are-you-new-to-video-editing-and-youre-looking-for-the-best-software-to-use-here-is-a-list-of-the-best-free-video-editing-software-for-beg/"><u>New 2024 Approved Are You New to Video Editing and Youre Looking for the Best Software to Use? Here Is a List of the Best Free Video Editing Software for Beginners</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-unmatched-virtual-speedway-showdowns-top-5-list/"><u>[New] Unmatched Virtual Speedway Showdowns  Top 5 List</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/aspect-ratio-conversion-in-final-cut-pro-a-quick-and-easy-guide-for-2024/"><u>Aspect Ratio Conversion in Final Cut Pro A Quick and Easy Guide for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-what-are-the-laws-around-saving-youtube-videos-for-offline-use/"><u>In 2024, What Are the Laws Around Saving YouTube Videos for Offline Use?</u></a></li>
</ul></div>
