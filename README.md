# 🚀 BeyondLife: Local Run Guide
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue)](../LICENSE)


> 🍎 iOS Simulator
> [![Platform](https://img.shields.io/badge/Run%20on-iOS%20Simulator-blue)](#)
> [![Build Type](https://img.shields.io/badge/Build-EAS%20Build-green)](https://docs.expo.dev/build/introduction/)

Welcome to the official **local run guide** for [BeyondLife](), an Open-Source Digital Will Solution for Posthumous Data Management.

This repository is dedicated to helping users run the app **locally**, starting with support for **iOS Simulator** on macOS.

---

## Demo Video

🎬 Watch a quick **BeyondLife** demonstration:

(🔊 **Turn up the volume for the full experience—there's background music!** 🎶)

https://github.com/user-attachments/assets/f86febd1-15be-4c5a-bfeb-838b4e7e32ac

---

## ✨ Current Availability

> ⚠️ As of now, **only iOS Simulator** is supported.  
> Additional platforms such as physical iOS devices or Android will be added soon.

---

## 🍏 Run on iOS Simulator (macOS Only)

You can try BeyondLife on your local machine using a prebuilt `.app` file—no compilation needed.  
This method is ideal for users who want to explore the interface without setting up a full development environment.


### 🧰 Requirements

To use this method, you must have:

- A Mac running macOS
- [Xcode](https://developer.apple.com/xcode/) installed
- iOS Simulator configured (included with Xcode)
- A stable internet connection

---

## 📦 Download Prebuilt App

The prebuilt iOS Simulator version of BeyondLife is included in this repository.
You can find the archive file at:

```
iOS-Simulator/application.tar
```

### 📂 Steps to Install:

1. **Extract the tar file**:  
   In Terminal or Finder, decompress the archive to retrieve the `.app` bundle:
   ```bash
   tar -xvf iOS-Simulator/application.tar
   ```

2. **Launch your iOS Simulator**:  
   You can open it via Xcode or run:
   ```bash
   open -a Simulator
   ```

3. **Drag and drop the `.app` into the simulator**:  
   Simply drag the extracted `.app` file onto the open simulator window — it will install and launch automatically.

> ✅ No compilation required — ideal for quick testing or previewing the UI flow.

---

## ▶️ Installation Guide (with Video)

Prefer a visual guide?  
👉 Watch our short video tutorial:  

https://github.com/user-attachments/assets/adbaec14-3cad-4792-868e-8d1b0b0151f5


> If you encounter issues, see [Troubleshooting](#️-troubleshooting)

---

## 🛠️ Troubleshooting

| Problem                          | Solution                                                                 |
|----------------------------------|--------------------------------------------------------------------------|
| Simulator not found              | Open Xcode → Preferences → Components → Install a simulator              |
| App failed to install            | Make sure the `.app` file is unzipped and correct path is used           |

---

## 🔗 Related Projects

| Repo | Description |
|------|-------------|
| [`BeyondLife-Landing-Page`]() | Official landing page for BeyondLife |
| [`BeyondLife`](https://github.com/LimeFavoredOrange/BeyondLife) | Source code for the BeyondLife application |
| [`PD-CP-ABE`](https://github.com/LimeFavoredOrange/PD-CP-ABE) | A novel cryptographic scheme enabling partially decryptable ciphertext-policy attribute-based encryption with fine-grained access control. |

---

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.  
See the [LICENSE](../LICENSE) file for more information.

---
