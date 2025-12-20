# 📁 Free Intune Win32 App Documentation Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0-green.svg)](https://github.com/MrtnRQL/intune-doc-generator/releases)
[![Free](https://img.shields.io/badge/price-free-brightgreen.svg)](https://mrtnrql.github.io/intune-doc-generator/)
[![Privacy](https://img.shields.io/badge/privacy-100%25%20local-success.svg)](https://mrtnrql.github.io/intune-doc-generator/)

**Auto-generate professional documentation for Microsoft Intune Win32 app packages in seconds.** No more manual copy-paste. No upload required. 100% browser-based and private.

🚀 **[Try it now →](https://mrtnrql.github.io/intune-doc-generator/intune-doc-generator.html)**

![Preview](/.github/assets/og-preview.png)

---

## ✨ Features

- ⚡ **Instant Documentation** - Generate complete package docs in seconds
- 🔒 **100% Private** - All processing happens in your browser, nothing uploaded
- 🤖 **AI-Powered Descriptions** - Auto-generate package descriptions (Beta)
- 📦 **Multi-Format Support** - PSADT v3/v4, MSI, EXE, MSIX, PowerShell, Batch
- 🌍 **Multilingual** - Norwegian and English support
- 💾 **No Installation** - Works directly in your browser
- 📋 **Copy & Paste** - One-click copy to clipboard

---

## 🚀 Quick Start

### Step 1: Open the Tool
**[Click here to open the Documentation Generator →](https://mrtnrql.github.io/intune-doc-generator/intune-doc-generator.html)**

### Step 2: Select Your Package Folder
Click **"Select Folder"** and choose your Intune Win32 app package folder.

The tool automatically detects:
- Package name and version (from PSADT scripts)
- Installation commands
- Uninstall commands
- Detection methods
- Log file paths

### Step 3: Review Auto-Filled Information
**⚠️ Important:** Double-check these fields:
- **Type** - Ensure correct package type (PSADT v4, v3, MSI, etc.)
- **Install Behavior** - System vs User context

### Step 4: Generate & Copy
1. Click **"Show Documentation"**
2. Click **"Copy"** 
3. Paste into your package folder or documentation system

**✅ Done!** Your documentation is ready.

---

## 📦 Supported Package Types

| Package Type | File Extension | Auto-Detection |
|-------------|----------------|----------------|
| **PowerShell App Deployment Toolkit v4** | `.ps1` | ✅ Full |
| **PowerShell App Deployment Toolkit v3** | `.ps1` | ✅ Full |
| **MSI Installer** | `.msi` | ✅ Partial |
| **EXE Installer** | `.exe` | ⚠️ Manual |
| **MSIX Package** | `.msix` | ⚠️ Manual |
| **PowerShell Script** | `.ps1` | ✅ Partial |
| **Batch/CMD Script** | `.bat/.cmd` | ⚠️ Manual |

---

## 💡 Pro Tips

### 🎯 Tip 1: Let Auto-Detection Work for You
For **PSADT packages**, the tool automatically reads:
```powershell
$appVendor = 'Adobe'
$appName = 'Acrobat Reader DC'
$appVersion = '24.1.20643'
```
And fills in all the fields for you!

### 🔐 Tip 2: Always Verify "Install Behavior"
This is **critical** for Intune deployment:
- **System** - Runs in SYSTEM context (most common)
- **User** - Runs in user context

### 🔍 Tip 3: Choose the Right Detection Method
- **Custom Script** - For advanced detection logic
- **File** - Check if specific file exists
- **Registry** - Check registry key/value
- **MSI** - Use MSI product code

### 🤖 Tip 4: Try AI-Powered Descriptions (Beta)
Click **"🤖 Let AI Help"** to auto-generate package descriptions based on your files.

---

## 🔒 Privacy & Security

**Your data never leaves your computer.**

- ✅ 100% client-side processing
- ✅ No file uploads to any server
- ✅ No data collection or tracking
- ✅ No personal information stored
- ✅ Works completely offline

When you close the browser tab, everything is deleted.

---

## 📋 Example Output

Here's what the generated documentation looks like:

```markdown
### Package Information

**Name:** Adobe Acrobat Reader DC  
**Type:** Win32: PSADT v4  
**Version:** 24.1.20643  
**Owner:** IT Department  
**Install Behavior:** System  

### Installation

**Installation Command:**  
Deploy-Application.exe -DeploymentType "Install" -DeployMode "NonInteractive"

**Uninstallation Command:**  
Deploy-Application.exe -DeploymentType "Uninstall" -DeployMode "NonInteractive"

### Detection Method

**Type:** Custom Script  
**Detection Script:** Detect-AdobeReader.ps1

### Logging

**Installation Log:** C:\Windows\Logs\Software\AdobeReader_24.1_Install.log  
**Uninstallation Log:** C:\Windows\Logs\Software\AdobeReader_24.1_Uninstall.log

### Dependencies

- Windows 10 22H2 or newer
- .NET Framework 4.8

### Notes

- Silent installation
- No reboot required
- Supports per-user installation
```

---

## 🌍 Language Support

- **🇬🇧 English** - Default language
- **🇳🇴 Norwegian** - Click "Norsk" button to switch

Switch between languages anytime using the language selector in the top-right corner.

---

## ❓ FAQ

<details>
<summary><strong>Do I need to install anything?</strong></summary>

No! Just open the link in your browser. Works on Chrome, Edge, Firefox, and Safari.
</details>

<details>
<summary><strong>Can I use this offline?</strong></summary>

Yes! The tool works completely offline. Download the HTML file and open it locally.
</details>

<details>
<summary><strong>What if auto-detection doesn't work?</strong></summary>

No problem! Just fill in the fields manually. The tool still saves you time with the template and formatting.
</details>

<details>
<summary><strong>Can I edit the documentation after generating it?</strong></summary>

Yes! Copy it to any text editor (Notepad, VS Code, Word) and modify as needed.
</details>

<details>
<summary><strong>Does this work on Mac/Linux?</strong></summary>

Yes! Works on any operating system with a modern web browser.
</details>

<details>
<summary><strong>Is my sensitive data safe?</strong></summary>

Absolutely. Nothing is uploaded. Everything happens locally in your browser. Close the tab and it's all gone.
</details>

<details>
<summary><strong>Can I use this for hundreds of packages?</strong></summary>

Yes! Each package takes only seconds to document. Perfect for large-scale deployments.
</details>

---

## 🛠️ Use Cases

### For IT Administrators
- Quick documentation for Intune app deployments
- Standardized format across all packages
- Easy handoff to team members

### For MSPs (Managed Service Providers)
- Client documentation in seconds
- Consistent documentation across multiple tenants
- Professional appearance for customer deliverables

### For Consultants
- Fast turnaround on implementation projects
- Easy knowledge transfer
- Audit-ready documentation

---

## 🎯 SEO Keywords

Microsoft Intune, Win32 app documentation, PSADT documentation generator, Intune package documentation, PowerShell App Deployment Toolkit, Intune Win32, app packaging, deployment documentation, IT documentation tool, free Intune tool, Intune automation, endpoint management, documentation generator

---

## 📊 Statistics

- 🚀 Generate docs in **under 30 seconds**
- 📦 Supports **7+ package types**
- 🌍 Available in **2 languages**
- 💯 **100% free** and open source

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🎉 Credits

Built with ❤️ for the Microsoft Intune community by **[Morten Glimme](https://github.com/MrtnRQL)**

> *"Code tells you how. Documentation tells you why. Your future self will thank you, and your colleagues will give you cake."*  
> — Unknown IT Legend

---

**⭐ If this tool saved you time, consider giving it a star on GitHub!**
