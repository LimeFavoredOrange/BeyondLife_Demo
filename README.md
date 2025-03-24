# 🚀 BeyondLife: Local Run Guide
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue)](../LICENSE)


> 🍎 IOS Simulator
> [![Platform](https://img.shields.io/badge/Run%20on-iOS%20Simulator-blue)](#)
> [![Build Type](https://img.shields.io/badge/Build-EAS%20Build-green)](https://docs.expo.dev/build/introduction/)

Welcome to the official **local run guide** for [BeyondLife](), an Open-Source Digital Will Solution for Posthumous Data Management.

This repository is dedicated to helping users run the app **locally**, starting with support for **iOS Simulator** on macOS.

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

Download the latest `.app` build here:

🔗 [Download iOS Simulator Build]()

1. Unzip the file to get:  
   ```bash
   BeyondLifeDemo.app
   ```

2. Move the `.app` to a convenient location (e.g. Desktop)

---

## ▶️ Installation Guide (with Video)

Prefer a visual guide?  
🎬 Watch our short video tutorial:  
👉 [How to Run BeyondLife on iOS Simulator]()

### Or follow these steps:

1. Open your iOS Simulator from Xcode or via command:
   ```bash
   open -a Simulator
   ```


2. You should now see the BeyondLife app running in the simulator 🎉

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
