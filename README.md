<h1 align="center">VibeDroid</h1>

<p align="center">
  <strong>AI chat. Real tools. Your Android workspace.</strong><br>
  Conversations, coding agents, files, math, and a Linux shell — on your phone.
</p>

<p align="center">
  <a href="https://github.com/hads-git/Vibedroid-apk/releases/latest/download/VibeDroid.apk">
    <img src="https://img.shields.io/badge/Download-Android_APK-f5f5f5?style=for-the-badge&amp;logo=android&amp;logoColor=ffffff&amp;labelColor=171717" alt="Download the latest Android APK">
  </a>
</p>

<p align="center">
  <a href="https://vibedroid.hadsai.com/">Website</a>
  &nbsp; · &nbsp;
  <a href="https://docs.hadsai.com/docs/setup/#vibedroid">Setup guide</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/hads-git/Vibedroid-apk/releases">Release notes</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/hads-git/Vibedroid-apk/issues">Report an issue</a>
</p>

<p align="center">
  <a href="https://github.com/hads-git/Vibedroid-apk/stargazers"><img src="https://img.shields.io/github/stars/hads-git/Vibedroid-apk?style=flat&amp;label=Stars&amp;color=444444&amp;labelColor=171717" alt="GitHub stars"></a>
  <a href="https://github.com/hads-git/Vibedroid-apk/releases"><img src="https://img.shields.io/github/downloads/hads-git/Vibedroid-apk/total?style=flat&amp;label=Downloads&amp;color=444444&amp;labelColor=171717" alt="Total GitHub release asset downloads"></a>
  <a href="https://github.com/hads-git/Vibedroid-apk/releases/latest"><img src="https://img.shields.io/github/v/release/hads-git/Vibedroid-apk?style=flat&amp;label=Release&amp;color=444444&amp;labelColor=171717" alt="Latest GitHub release"></a>
  <a href="https://github.com/hads-git/Vibedroid-apk/forks"><img src="https://img.shields.io/github/forks/hads-git/Vibedroid-apk?style=flat&amp;label=Forks&amp;color=444444&amp;labelColor=171717" alt="GitHub forks"></a>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/890619ec-ab2d-4612-9a75-2782e6fcf272" width="760" alt="The VibeDroid logo appears with a bending mesh, blur, and animated monochrome particles">
</p>

<p align="center"><sub>Native Android · Android 8.0+ · ARM64 · Bring your API key</sub></p>

---

## Your workspace, wherever you are

VibeDroid brings AI conversations and a coding workspace together in a native Android app. Connect a compatible API provider, work with your project files, and follow delegated agents in their own chats.

### New in 0.2.7

Model, permission-mode and reasoning controls now expand directly inside the composer. API **Auto** selects a compatible protocol where model/server information is available; manual formats remain available for custom setups.

- More reliable Claude streaming, extended-thinking settings and recovery from interrupted replies.
- Distinct agent colors, rotating activity indicators and clearer task details.
- Text/code, photo and PDF attachments, plus image previews before and after sending.
- Cross-chat review notifications, working hyperlinks and improved built-in search.

See the [complete 0.2.7 release notes](https://github.com/hads-git/Vibedroid-apk/releases/tag/v0.2.7). This version also upgrades local 0.2.6 test builds.

<p align="center">
  <img src="https://github.com/user-attachments/assets/d93bf460-a8f2-469a-b347-74a3cf69f349" width="1200" alt="VibeDroid showing a function plot, a coding conversation with tool results, and delegated agent tasks">
</p>

<p align="center"><sub>Interface previews use demonstration conversations and model names.</sub></p>

| Feature | What you can do |
| --- | --- |
| **Chat & history** | Keep conversations in a sidebar, revisit local history, and reopen pending questions with your drafted answers intact. |
| **Coding workspace** | Browse and edit project files, see the command currently running in the built-in Linux shell, and stop an individual operation. |
| **Agent chats** | Continue using the main chat while delegated tasks run, follow their separate conversations, and revisit grouped finished agents. Requires a model that supports tools. |
| **Background work** | Keep active tasks running while the app is minimized or the screen is locked, with an ongoing service notification. |
| **Math & plots** | Read formatted equations, fractions, code, and supported function plots in the conversation. |
| **Attachments & images** | Attach text/code, photos and PDFs; preview images before sending and in the chat with fullscreen zoom and pan. PDF previews cover up to the first four pages. |
| **Models & reasoning** | Expand the composer settings to choose a model, permission mode and supported effort level. API Auto selects a compatible protocol when known; manual Messages, Chat Completions and Responses remain available. |
| **Permission modes** | Choose Ask, Accept edits, Plan, or YOLO, and switch modes during a task to control how agent actions are approved. |
| **In-app updates** | Get a glass update banner, download the latest official APK, and install it with Android's confirmation. |

## Get started

**You need:** an ARM64 Android device running Android 8.0 or newer, internet access for model requests, and a valid provider API key. Model availability and API charges depend on your provider and account.

1. **Install the APK.** [Download the latest VibeDroid.apk](https://github.com/hads-git/Vibedroid-apk/releases/latest/download/VibeDroid.apk), open it on Android, and allow installation from that source if prompted.
2. **Prepare your workspace.** Tap **Start** and wait for the included Linux environment to prepare. On **File access**, grant shared-file access or choose **Use app folder**. A separate Termux installation is not required.
3. **Connect your provider.** Open the sidebar → **Settings** → **API**, leave **API format** on **Auto** (or choose the format required by a custom gateway), enter your **Base URL** and **API key**, and tap **Save connection**. HadsAI users can also import a key through **Profile**.
4. **Restart and chat.** Fully close and reopen VibeDroid. Open the settings button beside the attachment button in **Chat** to select an available model, effort and permission mode. Start with **Ask** mode.

> **After adding or changing your API key, fully close and reopen the app before sending a request.** `Saved on device` confirms local storage of your settings; a successful reply confirms the API connection.

For Claude through HadsAI, use `https://hadsai.com/v1` and your HadsAI API key. **Auto** selects Messages for known Claude models unless the server declares different support. If you previously saved an incorrect manual format, explicitly select **Auto** again to reset that model's saved route. Manual **Anthropic Messages** remains available.

**[Read the illustrated setup guide →](https://docs.hadsai.com/docs/setup/#vibedroid)**

## Releases & compatibility

Download the **VibeDroid.apk** asset from [GitHub Releases](https://github.com/hads-git/Vibedroid-apk/releases). The download button above always points to the latest standard release. GitHub supplies the APK checksum in the release asset metadata used by the in-app updater.

**From version 0.2.0**, VibeDroid checks GitHub for stable updates while the app is open. A glowing glass banner appears when a newer version is available. Tap **Download**, then **Install update**; Android confirms installation and may ask to allow VibeDroid to install apps. You can also use **Settings → App → Check for updates**. Downloads are checked against the published SHA-256, package version, device compatibility, and the installed app's signing certificate.

Install the latest APK manually if you are upgrading from 0.1.0, which does not contain the updater. Finish active chats and save open files before installing. Successful compatible upgrades preserve your local chats and settings.

Some early builds used different signing certificates. If Android rejects an update because of a signature conflict, preserve your local data and check the release's installation notes before changing the existing installation.

Conversations and agent history are stored on your device. Model requests use the API provider you configure.

Allow notifications on Android 13+ to see the running service and its **Stop** button. You can open the notification controls from **Settings → App → Background work**. Background work supports minimizing and screen lock; removing the app from recents or force-stopping it still interrupts active tasks.

**Share app activity**, under **Settings → App**, sends a limited native activity request while VibeDroid is open. Your Profile sign-in can link this activity to your account. No web page is rendered, and the request sends no chat content or model API key. Server-side analytics determines how activity is recorded and counted.

## Follow the project

If VibeDroid is useful to you, **[give the repository a star](https://github.com/hads-git/Vibedroid-apk)**. To receive release notifications, choose **Watch → Custom → Releases** on GitHub.

The badges at the top show GitHub stars, forks, the latest release, and total release-asset downloads. GitHub and Shields.io cache these values, so updates may take time. Downloads count file requests, including repeat downloads; they are not a count of unique users or app installations.

Found a problem? **[Open an issue](https://github.com/hads-git/Vibedroid-apk/issues/new)** with your app version, Android version, device model, and steps to reproduce it.

---

<p align="center">
  <a href="https://github.com/hads-git/Vibedroid-apk/releases/latest/download/VibeDroid.apk"><strong>Download VibeDroid</strong></a>
  &nbsp; · &nbsp;
  <a href="https://vibedroid.hadsai.com/">Website</a>
  &nbsp; · &nbsp;
  <a href="https://docs.hadsai.com/docs/setup/#vibedroid">Documentation</a>
</p>
