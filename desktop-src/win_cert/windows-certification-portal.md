---
title: Certify your desktop application
description: Follow these steps to get your desktop app certified for Windows 7, Windows 8, Windows 8.1, and Windows 10.If you wish to convert your desktop app to be compatible with the Universal Windows Platform and Windows Store, you will use the Windows Desktop Bridge, in which case you should follow the Desktop Bridge guidance for certification steps.If you are developing and certifying a UWP app from the start, see Guidance for Windows App Certification in UWP for info on certification.
ms.assetid: d77d9f1c-1738-4f44-a351-1985ffc21707
ms.topic: article
ms.date: 05/31/2018
---

# Certify your desktop application

Follow these steps to get your desktop app certified for Windows 7, Windows 8, Windows 8.1, and Windows 10.

If you wish to convert your desktop app to be compatible with the Universal Windows Platform and Windows Store, you will use the [Windows Desktop Bridge](https://developer.microsoft.com/windows/bridges/desktop), in which case you should follow the [Desktop Bridge](https://docs.microsoft.com/windows/uwp/porting/desktop-to-uwp-root) guidance for certification steps.

If you are developing and certifying a UWP app from the start, see [Guidance for Windows App Certification in UWP](https://docs.microsoft.com/windows/uwp/debug-test-perf/windows-app-certification-kit) for info on certification.

## Step 1: Prepare for certification



| Topic                                                                                       | Description                                                                                    |
|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [What are the benefits?](what-are-the-benefits-.md)<br/>                             | Certifying your desktop app provides several benefits for you and your customers.              |
| [Read the requirements](certification-requirements-for-windows-desktop-apps.md)<br/> | Review the technical requirements and eligibility qualifications that a desktop app must meet. |



 

## Step 2: Test your app with the Windows App Certification Kit



| Topic                                                          | Description                                                                                                                                                                           |
|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Get the Kit](https://developer.microsoft.com/windows/downloads/app-certification-kit/) | To certify your app, you have to install and run the Windows App Certification Kit (included in the Windows SDK).                                                                     |
| [Using the Kit](using-the-windows-app-certification-kit.md)   | Before you can submit your app, you must test it for readiness. You can also download a copy of the [app certification white paper](https://www.microsoft.com/en-us/download/details.aspx?id=27414). |
| [Review test details](windows-app-certification-kit-tests.md) | Get the list of the tests your app needs to pass to qualify for compatibility with the latest Windows operating system.                                                               |



 

Note: Filter drivers must also pass the [Hardware Certification Kit](http://download.microsoft.com/download/1/8/B/18BC088A-537D-4386-9334-687747A602E6/hlk/hlksetup.exe). (See [Certification requirements for Windows desktop apps, section 6.2](certification-requirements-for-windows-desktop-apps.md).)

## Step 3: Use the Windows Certification Dashboard

To submit your app for certification, you'll need to log in or register a company account on the [Windows Certification Dashboard](https://docs.microsoft.com/previous-versions/hh833792(v=msdn.10)?redirectedfrom=MSDN). Once you do, not only will you be able to get your app certified, but you'll also gain access to tools to review and manage your app at all stages of the process.



| Topic                                                                                                                   | Description                                                                                                                                        |
|-------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| [Set up your account](https://docs.microsoft.com/windows-hardware/drivers/dashboard/)                 | If your company isn't already registered, you must register it through the Windows Certification Dashboard.                                        |
| [Get a code signing certificate](https://docs.microsoft.com/windows-hardware/drivers/dashboard/)      | Before you can establish a Windows Certification Dashboard account, you need to get a code signing certificate to secure your digital information. |
| [Test locally and upload the results](https://docs.microsoft.com/windows-hardware/drivers/dashboard/) | After your run the Windows App Certification Kit tests, upload the results to the Windows Certification Dashboard.                                 |
| [Manage your submission](https://docs.microsoft.com/windows-hardware/drivers/dashboard/)              | After you submit your app for certification, you can review your submission through the Windows Certification Dashboard.                           |



 

## Step 4: Promote your desktop app



| Topic                                                                      | Description                                                                                                               |
|----------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| [Check app compatibility](https://docs.microsoft.com/windows/compatibility/windows-8-1-introduction?redirectedfrom=MSDN) | If you are building an app for Windows 8.1, investigate compatibility concerns.                                           |
| [Use the logo with your app](windows-7-certification.md)                  | Display the logo on packaging and in ads and other promotional materials according to the guidelines. For Windows 7 only. |



 

## See also:

[App compatibility forum](https://social.msdn.microsoft.com/Forums/windowsdesktop/en-US/home?forum=windowscompatibility): Find support from the community about compatibility and logo certification.

[Windows SDK blog](https://blogs.msdn.com/b/winsdk/archive/tags/certification/): Find tips and news related to app certification.

[Windows Server forum]( https://social.technet.microsoft.com/Forums/windowsserver/en-US/home?forum=WSAppCompat): Visit the Certification forum to get answers.

[Compatibility cookbook](https://docs.microsoft.com/windows/desktop/w8cookbook/windows-8-and-windows-server-8-compatibility-cookbook-portal): Get info about what's new or changed in the latest version of Windows.

 

 





