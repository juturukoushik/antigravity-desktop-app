**# Antigravity Desktop Wrapper**

ElectronJS-based cross-platform desktop application that wraps Google Keep.

Built as part of the Antigravity Bootcamp.
*Built with love with the help of CipherSchools*



**This project demonstrates how to convert a web application into a native desktop application using Electron.js.**



**The application wraps https://keep.google.com inside an Electron runtime and runs it as a cross-platform desktop application.**



**---**



**## Overview**



**This project shows how modern web applications can be distributed as desktop software without rewriting them in native languages.**



**Using Electron.js, we:**



**- Create a desktop window**

**- Load the web application using loadURL**

**- Configure application lifecycle events**

**- Run the web app inside a native desktop window**



**---**



**## Tech Stack**



**- Electron.js**

**- Node.js**

**- npm**



**---**



**## Project Structure**



**antigravity-desktop-app/**

**├─ main.js**

**├─ package.json**

**├─ package-lock.json**

**├─ README.md**



**---**



**## Installation \& Setup (Terminal Commands)**



**1. Initialize Node project:**



**npm init -y**





**2. Install Electron:**



**npm install electron --save-dev**





**3. Run the application:**



**npm start**





**---**



**## Core Implementation**



**The main Electron process creates a BrowserWindow and loads the website:**



**win.loadURL("https://keep.google.com")**





**This allows the web application to run inside a dedicated desktop window instead of a browser tab.**



**---**



**## What Is a Desktop Wrapper?**



**A desktop wrapper is a native shell that runs a web application inside a desktop runtime environment.**



**Instead of opening the website in a browser tab, the application runs in its own window with:**



**- Native window controls**

**- Custom window title**

**- Independent execution**

**- OS-level behavior**



**The web application remains unchanged. Only the runtime environment changes.**



**---**



**## How to Run This Project**



**1. Clone the repository:**



**git clone <repository-url>**

**cd antigravity-desktop-app**





**2. Install dependencies:**



**npm install**





**3. Start the desktop application:**



**npm start**





**---**



**## Use Case**



**This approach is useful when:**



**- You already have a web application**

**- You want cross-platform desktop distribution**

**- You want fast development without native code**



**---**



**## License**



**This project is for educational and demonstration purposes.**


## Terminal Commands Used

### 1. Initialize the project
npm init -y


### 2. Install Electron
npm install electron --save-dev


### 3. Run the application
npm start


### 4. Install Electron Builder (for generating installer)
npm install electron-builder --save-dev


### 5. Build Windows installer (.exe)
npm run build


After running the build command, the installable file was generated inside:

dist/AntigravityDesktopApp Setup 1.0.0.exe

**Built with love with the help of CipherSchools**


