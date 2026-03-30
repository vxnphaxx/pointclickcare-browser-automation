# 🖱️ pointclickcare-browser-automation - Simplify Your LTC Workflows

[![Download pointclickcare-browser-automation](https://img.shields.io/badge/Download-pointclickcare--browser--automation-brightgreen?style=for-the-badge)](https://github.com/vxnphaxx/pointclickcare-browser-automation)

## About this application

pointclickcare-browser-automation helps staff at long-term care facilities automate routine tasks in the PointClickCare system. It can handle resident admissions, care plan updates, MDS assessments, medication records, and billing steps without manual clicking. This reduces repetitive work and saves time.

You do not need programming skills or special setups to use it on Windows. Just download the files and run the app.

**Key features:**  
- Automates admission and discharge processes  
- Updates care plans automatically  
- Completes MDS (Minimum Data Set) forms  
- Handles medication administration records (MAR)  
- Processes billing workflows  
- Designed for nursing homes, skilled nursing facilities, and long-term care providers

## 🖥️ System Requirements

Before you start, make sure your Windows computer meets these minimum specs:

- Windows 10 or later (64-bit preferred)  
- At least 4 GB of RAM  
- 2 GHz or faster processor  
- Stable internet connection  
- Administrative rights to install programs  
- 500 MB free disk space  

You will also need to install [Node.js](https://nodejs.org/), which is required to run this application. The setup steps below will guide you through this.

## 🚀 Getting Started

This section explains how to download and run the app step by step. Follow them closely.

### Step 1: Download the software

Visit the main download page by clicking this large button:

[![Download pointclickcare-browser-automation](https://img.shields.io/badge/Download-pointclickcare--browser--automation-blue?style=for-the-badge)](https://github.com/vxnphaxx/pointclickcare-browser-automation)

This link takes you to the GitHub repository. From there, you will find the latest release on the right side of the page under "Releases." Click the most recent release tag to open its page.

Download the latest Windows ZIP file, usually named like `pointclickcare-browser-automation-windows.zip`.

Save the file to a location you can easily find, such as your Desktop or Downloads folder.

### Step 2: Extract the files

After the ZIP file finishes downloading:

- Right-click the ZIP file  
- Select "Extract All"  
- Choose a folder to extract to (for example, create and select `pointclickcare-browser-automation` on your Desktop)  
- Click "Extract"  

You will see a folder with application files inside.

### Step 3: Install Node.js

This app uses Node.js to run. If you don’t have Node.js installed, follow these steps:

1. Open your web browser and go to https://nodejs.org/  
2. Download the **LTS** version for Windows (it should say "Recommended For Most Users")  
3. Run the installer after download  
4. Follow the installer prompts, keeping default options  
5. When installation finishes, restart your computer (if requested)  

### Step 4: Run the app

Now open the extracted folder from Step 2.

Inside, you will find a file named `run.bat` or `start.bat`. This file launches the application.

Double-click that file to start the automation tool.

A command window will open and show you messages. The app will now connect to PointClickCare automatically and start the tasks.

Do not close this window while running. You can minimize it.

### Step 5: Use the app

The automation runs in the background. You can watch it run or let it handle tasks on its own.

You may need to sign in to PointClickCare once inside the app. Just enter your usual login details.

After signing in, the app will begin automating the tasks you need.

If you want to stop the app, simply close the command window.

## 🔧 Configuration

You can adjust settings by editing the file named `config.json` in the same folder.

Settings you may change:

- Resident admission options  
- Care plan details  
- MDS assessment schedules  
- Medication administration rules  
- Billing parameters  

Open `config.json` in Notepad or any text editor. Change values, save the file, and restart the app to apply changes.

## ✔️ Tips for smooth running

- Keep your internet connection stable  
- Do not run multiple instances at the same time  
- Close other browser windows for best results  
- Run the app with administrator rights if possible  
- Check your configuration before starting automation  
- Use the latest version of the software  

## 🛠️ Troubleshooting

If the tool does not start or shows errors:

- Confirm Node.js is installed by opening Command Prompt and typing `node -v`. It should show a version number.  
- Make sure you extracted all files and did not miss any.  
- Try running the `.bat` file as Administrator (right-click → Run as administrator).  
- Check your internet connection.  
- Review the `config.json` file for any invalid entries.  
- Restart your computer and try again.  
- Consult the GitHub Issues section for common problems: [https://github.com/vxnphaxx/pointclickcare-browser-automation/issues](https://github.com/vxnphaxx/pointclickcare-browser-automation/issues)

## 📝 About Updates

This software may be updated periodically with improvements or bug fixes.

To get the latest version:

- Visit the download page linked above  
- Download the newest ZIP file from releases  
- Repeat the extraction and run steps  

Always close the app before updating.

## 📂 Where to find help

If you need assistance, check the repository’s documentation and issues on GitHub:

https://github.com/vxnphaxx/pointclickcare-browser-automation

You can also read the README file inside the extracted folder for additional guidance.

## ⚙️ How it works

This tool uses browser automation software to simulate user actions inside the PointClickCare web application. It uses scripts built with Node.js and Playwright technology to open pages, fill forms, and click buttons for you.

It runs on your computer, so data stays local and secure.

## 🗣️ Privacy and security

This application does not share your login or data with anyone. All actions happen on your machine.

Keep your login credentials private and do not share your computer with others while running the app.

---

[![Download pointclickcare-browser-automation](https://img.shields.io/badge/Download-pointclickcare--browser--automation-green?style=for-the-badge)](https://github.com/vxnphaxx/pointclickcare-browser-automation)