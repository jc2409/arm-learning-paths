---
title: Development environment
weight: 3

### FIXED, DO NOT MODIFY
layout: learningpathall
---

## Install dependencies

In this learning path, you will compile an Android application, so you first need to download and install the latest version of [Android Studio](https://developer.android.com/studio) on your development machine.

You then need to install the following tools:
- `cmake`, the software build system
- `git`, the version control system for cloning the Voice Assistant codebase
- `adb`, the Android Debug Bridge, a command-line tool to communicate with a device and perform various commands on it

These tools can be installed by running the following command (depending on your machine's OS):

{{< tabpane code=true >}}
  {{< tab header="Linux/Ubuntu" language="bash">}}
sudo apt update
sudo apt install git adb cmake -y
  {{< /tab >}}
  {{< tab header="macOS" language="bash">}}
brew install git android-platform-tools cmake
  {{< /tab >}}
{{< /tabpane >}}
