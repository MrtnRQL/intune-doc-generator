# 📁 Intune Apps Documentation Generator

**Automatically create documentation for your Intune app packages in seconds!**

No more manual documentation. Just select your package folder, and this tool does the rest.

---

## 🚀 How to Use

###
 Step 1: Open the Tool

Click here: 
[Open Documentation Generator](https://mrtnrql.github.io/intune-doc-generator/intune-doc-generator.html

### Step 2: Select Your Package Folder
Click the **"Select Folder"** button and choose your Intune package folder (the one with your source files).

### Step 3: Review the Information
The tool automatically finds:
- Package name and version
- Installation commands
- Log file paths
- File types

**Important:** Double-check the fields marked with ⚠️ (Type and Install Behavior)

### Step 4: Generate Documentation
Click **"Show Documentation"** to see your formatted documentation.

### Step 5: Copy and Save
Click **"Copy"** and paste the documentation into your package folder or documentation system.

**Done!** ✅

---

## 🌍 Language

- **Default language:** English
- **Switch to Norwegian:** Click the **"Norsk"** button in the top-right corner
- **Switch back to English:** Click the **"English"** button

---

## 📦 What Files Does It Support?

The tool works with:
- **PSADT packages** (Deploy-Application.ps1)
- **MSI installers** (.msi files)
- **EXE installers** (.exe files)
- **PowerShell scripts** (.ps1 files)
- **MSIX packages** (.msix files)

---

## 💡 Pro Tips

### Tip 1: Let It Do the Work
The tool automatically reads your `Deploy-Application.ps1` file and fills in:
- Package name (from $appVendor and $appName)
- Version (from $appVersion)
- Install/Uninstall commands
- Log file paths

### Tip 2: Always Check "Install Behavior"
This field is critical for Intune! Make sure it's set correctly:
- **System** - Installs for all users (most common)
- **User** - Installs per user

### Tip 3: Choose the Right Detection Method
- **Custom Script** - If you have a detection script
- **File** - If you check for a specific file
- **Registry** - If you check a registry key
- **MSI** - If you use MSI product code

---

## 🔒 Is My Data Safe?

**Yes! 100% safe.**

- ✅ Everything happens in your browser
- ✅ No files are uploaded anywhere
- ✅ No data is stored on any server
- ✅ No personal information is collected

When you close the page, everything is deleted.

---

## 📋 Example: What You Get

Here's what the documentation looks like:

```
Name:  
Adobe Acrobat Reader DC

Type:  
Win32: PSADT

Version:  
24.1.0

Installation:  
Deploy-Application.exe -DeploymentType "Install" -DeployMode "NonInteractive"

Uninstallation:  
Deploy-Application.exe -DeploymentType "unInstall" -DeployMode "NonInteractive"

Detection:  
Custom Script

Dependencies:  
- Windows 10 22H2 or newer

Notes:  
- No reboot required
```

---

## ❓ Common Questions

### Q: Do I need to install anything?
**A:** No! Just open the link in your browser. Works on Chrome, Edge, Firefox, and Safari.

### Q: Can I use this offline?
**A:** Yes! Download the HTML file and open it locally. Everything works offline.

### Q: What if the tool doesn't detect my package info?
**A:** No problem! Just fill in the fields manually. The tool still saves you time with the template.

### Q: Can I edit the documentation after generating it?
**A:** Yes! Copy it to a text editor and modify as needed.

### Q: Does this work on Mac?
**A:** Yes! Works on any operating system with a modern web browser.

---





## 🎉 Credits

Built for Intune admins who are tired of writing the same documentation over and over.

**"Code tells you how. Documentation tells you why. Your future self will thank you, and your colleagues will give you cake."**

---

**Made with ❤️ for the Intune community by Morten Glimme**
