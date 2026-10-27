# Google Play Console — Privacy Policy & Data Safety Setup Guide for APEX VECTOR

This document is a quick-reference checklist for configuring the **Google Play Console** (`App Content -> Privacy Policy` and `Data Safety`) for **APEX VECTOR** (`com.apexvector.game`).

---

## 1. Privacy Policy URLs (For Google Play Console -> App Content -> Privacy Policy)

- **GitHub Pages URL (Recommended for Play Store listing):**  
  `https://meracing.github.io/Apex-Vector-privacy-policy/`
- **GitHub Repository URL:**  
  `https://github.com/meracing/Apex-Vector-privacy-policy`
- **Local Directory in Wing-Racer Project:**  
  `c:\Projects\Wing-Racer\privacy-policy`  
  *(Standalone Git clone also located at `c:\Projects\Apex-Vector-privacy-policy`)*

---

## 2. Google Play Console "Data Safety" Questionnaire Answers

When filling out **Policy -> App content -> Data safety** in Google Play Console:

1. **Does your app collect or share any of the required user data types?**
   - **If releasing without third-party ads (Pure Offline + Local LAN + Google Play Billing):**  
     Select **No** (All game progress is stored locally on the user's device and never transmitted off-device to developer servers; Google Play Billing handles its own payment processing within Google Play).
   - **If Google Play Billing requires declaring Purchase History:**  
     Check **Financial info -> Purchase history** (Processed ephemerally by Google Play Billing for unlocking `dlc_pack_1` / `ad_free`, **App functionality**, **Not shared with third parties**).
2. **Target Audience and Content (COPPA):**
   - Target age group: **13+** (or general audience; zero personal data collected).
3. **App Permissions Summary (`AndroidManifest.xml`):**
   - `android.permission.VIBRATE` (Normal — Haptics)
   - `android.permission.INTERNET` (Normal — Local Wi-Fi UDP LAN Multiplayer)
   - `android.permission.ACCESS_NETWORK_STATE` (Normal — Local Wi-Fi check)
   - `android.permission.ACCESS_WIFI_STATE` (Normal — Display LAN IP in 2-Device Wi-Fi Lobby)
   - `com.android.vending.billing` (Normal — Optional In-App Purchases)
