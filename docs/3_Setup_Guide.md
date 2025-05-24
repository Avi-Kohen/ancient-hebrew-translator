# 3. Setup Guide

This guide walks you through setting up your Windows machine to develop the Ancient Hebrew Translator app using Android Studio + Chaquopy.

---

## Prerequisites

- A Windows PC with administrative privileges  
- Git installed (optional but recommended)  
- Internet connection  

---

## 1. Install Java & Android Studio

1. **Java JDK**  
   - Download and install [Java SE JDK 17+](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html).  
   - During installation, note the install path (e.g., `C:\Program Files\Java\jdk-17`).  
   - Optionally set `JAVA_HOME` in System Environment Variables to that path.

2. **Android Studio**  
   - Download & install the latest **Android Studio** from https://developer.android.com/studio  
   - Launch it once and follow the wizard to install the Android SDK, SDK Tools, and an emulator image.

---

## 2. Clone & Open the Project

1. Open **Git Bash** (or a terminal) and run:
   ```bash
   git clone https://github.com/YourUsername/ancient-hebrew-translator.git
   cd ancient-hebrew-translator
