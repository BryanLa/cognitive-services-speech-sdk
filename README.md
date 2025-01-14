---
topic: sample
languages:
  - cpp
  - csharp
  - java
  - javascript
  - nodejs
  - objc
  - python
name: Speech SDK Samples
description: |
  Learn how to use the Microsoft Cognitive Services Speech SDK to add speech-enabled features to your applications.
products:
  - azure-cognitive-services
---

# Sample Repository for the Microsoft Cognitive Services Speech SDK

This project hosts the **samples** for the Microsoft Cognitive Services Speech SDK. To find out more about the Microsoft Cognitive Services Speech SDK itself, please visit the [SDK documentation site](https://aka.ms/csspeech).

## News

Please check [here](https://aka.ms/csspeech/whatsnew) for release notes and older releases.

* Speech SDK Release 1.6.0

  June 2019 we released version 1.6.0 of the Speech SDK.

* Speech SDK Release 1.5.1

  Middle of May 2019 we released version 1.5.1 of the Speech SDK.

* Speech SDK Release 1.5.0

  Beginning of May 2019 we released version 1.5.0 of the Speech SDK.

* Speech SDK Release 1.4.0

  Beginning of April 2019 we released version 1.4.0 of the Speech SDK.

* Speech SDK Release 1.3.1

  End of February 2019 we released version 1.3.1 of the Speech SDK.

## Features

This repository hosts samples that help you to get started with several features of the SDK.
In addition more complex scenarios are included to give you a head-start on using speech technology in your application.

We tested the samples with the latest released version of the SDK (1.5.0) on Windows 10, Linux (Ubuntu 16.04, Ubuntu 18.04, Debian 9), Android devices (API 23: Android 6.0 Marshmallow or higher), and iOS 11.4 devices.

## Getting Started

The [SDK documentation](https://aka.ms/csspeech) has extensive sections about getting started, setting up the SDK, as well as the process to acquire the required subscription keys. You will need subscription keys to run the samples on your machines, you therefore should follow the instructions on these pages before continuing.

## Get the samples

* The easiest way to use these samples without using Git is to download the current version as a [ZIP file](https://github.com/Azure-Samples/cognitive-services-speech-sdk/archive/master.zip).

  * On Windows, before you unzip the archive, right-click it, select **Properties**, and then select **Unblock**.
  * Be sure to unzip the entire archive, and not just individual samples.

* Clone this sample repository using a Git client.

## Build and run the samples

> **Note: the samples make use of the Microsoft Cognitive Services Speech SDK.
> By downloading the Microsoft Cognitive Services Speech SDK, you acknowledge its license, see [Speech SDK license agreement](https://aka.ms/csspeech/license201809).**

Please see the description of each individual sample for instructions on how to build and run it.

### Speech recognition quickstarts

The following quickstarts demonstrate how to perform one-shot speech recognition using a microphone.
If you want to build them from scratch, please follow the articles in the Quickstart section on our [documentation page](https://aka.ms/csspeech).

| Quickstart | Platform | Description |
| ---------- | -------- | ----------- |
| [Quickstart C++ for Linux](./quickstart/cpp-linux/) | Linux | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart C++ for Windows](./quickstart/cpp-windows/) | Windows  | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart C# .NET for Windows](./quickstart/csharp-dotnet-windows/) | Windows | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart C# .NET Core](./quickstart/csharp-dotnetcore/) | Windows, Linux, macOS | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart C# UWP for Windows](./quickstart/csharp-uwp/) | Windows | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart C# Unity (Windows or Android)](./quickstart/csharp-unity/) | Windows, Android | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart for Android](./quickstart/java-android/) | Android  | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart Java JRE](./quickstart/java-jre/) | Windows, Linux, macOS | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart JavaScript](./quickstart/js-browser/) | Web | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart Node.js](./quickstart/js-node/) | Node.js | Demonstrates one-shot speech recognition from a file. |
| [Quickstart Python](./quickstart/python/) | Windows, Linux, macOS | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart Objective-C](./quickstart/objectivec-ios/) | iOS | Demonstrates one-shot speech recognition from a file with recorded speech. |
| [Quickstart Swift](./quickstart/swift-ios/) | iOS | Demonstrates one-shot speech recognition from a microphone. |
| [Quickstart Objective-C](./quickstart/objectivec-macos/) | macOS | Demonstrates one-shot speech recognition from a microphone. |

### Speech translation quickstarts

The following quickstarts demonstrate how to perform one-shot speech translation using a microphone.
If you want to build them from scratch, please follow the articles in the Quickstart section on our [documentation page](https://aka.ms/csspeech).

| Quickstart | Platform | Description |
| ---------- | -------- | ----------- |
| [Quickstart C++ for Windows](./quickstart/speech-translation/cpp-windows/) | Windows | Demonstrates one-shot speech translation/transcription from a microphone. |
| [Quickstart C# .NET Framework for Windows](./quickstart/speech-translation/csharp-dotnet-windows/) | Windows | Demonstrates one-shot speech translation/transcription from a microphone. |
| [Quickstart C# .NET Core](./quickstart/speech-translation/csharp-dotnetcore/) | Windows, Linux, macOS | Demonstrates one-shot speech translation/transcription from a microphone. |
| [Quickstart C# UWP for Windows](./quickstart/speech-translation/csharp-uwp/) | Windows | Demonstrates one-shot speech translation/transcription from a microphone. |
| [Quickstart Java JRE](./quickstart/speech-translation/java-jre/) | Windows, Linux, macOS | Demonstrates one-shot speech translation/transcription from a microphone. |

### Speech synthesis quickstarts

The following quickstarts demonstrate how to perform one-shot speech synthesis to a speaker.
If you want to build them from scratch, please follow the articles in the Quickstart section on our [documentation page](https://aka.ms/csspeech).

| Quickstart | Platform | Description |
| ---------- | -------- | ----------- |
| [Quickstart C++ for Linux](./quickstart/text-to-speech/cpp-linux/) | Linux | Demonstrates one-shot speech synthesis to the default speaker. |
| [Quickstart C++ for Windows](./quickstart/text-to-speech/cpp-windows/) | Windows  | Demonstrates one-shot speech synthesis to the default speaker. |
| [Quickstart C# .NET for Windows](./quickstart/text-to-speech/csharp-dotnet-windows/) | Windows | Demonstrates one-shot speech synthesis to the default speaker. |
| [Quickstart C# UWP for Windows](./quickstart/text-to-speech/csharp-uwp/) | Windows | Demonstrates one-shot speech synthesis to the default speaker. |
| [Quickstart C# .NET Core](./quickstart/text-to-speech/csharp-dotnetcore/) | Windows, Linux | Demonstrates one-shot speech synthesis to the default speaker. |

### Voice-first virtual assistants quickstarts

The following quickstarts demonstrate how to create a custom voice-first virtual assistant (Preview).
The applications will connect to a previously authored bot configured to use the Direct Line Speech channel, send a voice request, and return a voice response activity (if configured).
If you want to build these quickstarts from scratch, please follow the articles in the Quickstart section on our [documentation page](https://aka.ms/csspeech).

| Quickstart | Platform | Description |
| ---------- | -------- | ----------- |
| [Quickstart Java JRE](./quickstart/virtual-assistant/java-jre) | Windows, Linux, macOS | Demonstrates speech recognition through the DialogServiceConnector and receiving activity responses. |
| [Quickstart C# UWP for Windows](./quickstart/virtual-assistant/csharp-uwp/) | Windows | Demonstrates speech recognition through the DialogServiceConnector and receiving activity responses. |

### Samples

The following samples demonstrate additional capabilities of the Speech SDK, such additional modes of speech recognition as well as intent recognition and translation:

| Sample                                                                                                      | Platform | Description                                                          |
| ---                                                                                                         | ---      | ---                                                                  |
| [C++ Console app for Windows](./samples/cpp/windows/console)                                                | Windows  | Demonstrates speech recognition, speech synthesis, intent recognition, conversation transcription and translation |
| [C++ Speech Recognition from MP3/Opus file (Linux only)](./samples/cpp/linux/compressed-audio-input)        | Linux    | Demonstrates speech recognition from an MP3/Opus file |
| [C# Console app for .NET Framework on Windows](./samples/csharp/dotnet-windows/console)                     | Windows  | Demonstrates speech recognition, speech synthesis, intent recognition, and translation |
| [C# Console app for .NET Core (Windows or Linux)](./samples/csharp/dotnetcore/console)                      | Windows, Linux, macOS  | Demonstrates speech recognition, speech synthesis, intent recognition, and translation |
| [Java Console app for JRE](./samples/java/jre/console)                                                      | Windows, Linux, macOS | Demonstrates speech recognition, intent recognition, and translation |
| [Python Console app](./samples/python/console)                                                              | Windows, Linux, macOS  | Demonstrates speech recognition, intent recognition, and translation |
| [Speech-to-text WPF sample for .NET Framework on Windows](./samples/csharp/dotnet-windows/speechtotext-wpf) | Windows  | Demonstrates speech recognition |
| [Translation WPF sample for .NET Framework on Windows](./samples/csharp/dotnet-windows/translation-wpf)     | Windows  | Demonstrates translation |
| [Speech-to-text UWP sample](./samples/csharp/uwp/speechtotext-uwp)                                          | Windows  | Demonstrates speech recognition |
| [Text-to-speech UWP sample](./samples/csharp/uwp/texttospeech-uwp)                                          | Windows  | Demonstrates speech synthesis |
| [Speech recognition sample for Android](./samples/java/android/sdkdemo)                                     | Android  | Demonstrates speech and intent recognition |
| [Speech recognition and translation sample for the browser, using JavaScript](./samples/js/browser)         | Web      | Demonstrates speech recognition, intent recognition, and translation |
| [Speech recognition and translation sample using JavaScript and Node.js](./samples/js/node)                 | Node.js  | Demonstrates speech recognition, intent recognition, and translation |
| [Speech recognition sample for iOS using a connection object](./samples/objective-c/ios/README.md#connection-object-sample)  | iOS      | Demonstrates speech recognition |
| [Extended speech recognition sample for iOS](./samples/objective-c/ios/README.md#example-app-with-various-samples)           | iOS      | Demonstrates speech recognition using streams etc.|
| [C# UWP DialogServiceConnector sample for Windows](./samples/virtual-assistant/csharp-uwp/) | Windows | Demonstrates speech recognition through the DialogServiceConnector and receiving activity responses. |
| [C# Unity sample for Windows or Android](./samples/unity/speechrecognizer/) | Windows, Android |  Demonstrates speech recognition, intent recognition, and translation for Unity |
| [C# Unity SpeechBotConnector sample for Windows](./samples/virtual-assistant/csharp-unity/) | Windows, Android | Demonstrates speech recognition through the SpeechBotConnector and receiving activity responses. |


Samples for using the Speech Service REST API (no Speech SDK installation required):

| Sample                                  | Description |
| ---                                     | --- |
| [Batch transcription](./samples/batch)  | Demonstrates usage of batch transcription from different programming languages |

## Resources

- [Microsoft Cognitive Services Speech Service and SDK Documentation](https://aka.ms/csspeech)
