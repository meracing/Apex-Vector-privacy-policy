# Privacy Policy for APEX VECTOR

**Effective Date:** October 27, 2026  
**Last Updated:** October 27, 2026  
**Application Name:** APEX VECTOR (2D Kinetic Wall-Grind Vector Racer)  
**Package Name:** `com.apexvector.game`  
**Developer / Publisher:** ME Racing (`meracing`)

---

## 1. Overview & Privacy-First Commitment

**APEX VECTOR** ("the Game", "we", "our", or "us") is a 2D kinetic vector racing game developed by **ME Racing**. We respect your privacy and designed APEX VECTOR with a strict **privacy-first, offline-capable architecture**.

- **We do NOT require you to create an account or sign in.**
- **We do NOT collect, store, transmit, or sell your personal data, name, email address, phone number, contacts, photos, microphone audio, or precise GPS location.**
- **All gameplay progress, lap records, ghost replays, and settings are stored locally on your device.**

This Privacy Policy explains what limited information is processed on your device, how permissions and optional features (such as 2-Device Local Wi-Fi Multiplayer and Google Play In-App Purchases) work, and your rights under applicable privacy laws (including GDPR, UK GDPR, CCPA/CPRA, and COPPA).

---

## 2. Information Stored Locally on Your Device

APEX VECTOR stores gameplay data locally on your device using Android internal app storage (`files/apex_vector_save_v1.json`) and local WebView storage (`localStorage`) solely so that your game progress persists between sessions:

- **Campaign & Level Progress:** Unlocked sectors, completed tracks, medals earned (Bronze, Silver, Gold, Apex), and Apex Shards collected.
- **Personal Best Times & Ghost Replays:** Your fastest lap times, split times, and 60Hz ghost ship replay coordinates so you can race against your own Personal Best ghost.
- **Game Preferences:** Audio mixer volume levels (Music and SFX), selected ship hull, neon exhaust trail skin, and control loadout preferences.

**How to Delete Your Local Data:**  
You control all local data. You can reset individual track records inside the in-game **Briefing -> Reset PB** menu, or erase all saved data at any time by clearing the app's storage or uninstalling **APEX VECTOR** from your Android device (`Settings -> Apps -> APEX VECTOR -> Storage -> Clear Data` or `Uninstall`). Because this data is never uploaded to external servers controlled by us, uninstalling the app permanently deletes it.

---

## 3. Device Permissions We Use and Why

APEX VECTOR requests **zero dangerous runtime permissions** (no camera, no microphone, no location, no contacts, no external file read/write). The Game uses only standard Android normal permissions required for core gameplay features:

| Permission | Purpose in APEX VECTOR |
| :--- | :--- |
| `android.permission.VIBRATE` | Provides tactile haptic feedback when wall-grinding, hitting boost pads, or crashing into hazards. |
| `android.permission.INTERNET` & `android.permission.ACCESS_NETWORK_STATE` | Used strictly for peer-to-peer **Local Wi-Fi 1v1 / Co-Op Multiplayer** packets on your local network (LAN) and for processing optional Google Play In-App Purchases. |
| `android.permission.ACCESS_WIFI_STATE` | Displays your device's local LAN IP address (e.g., `192.168.x.x`) inside the in-game **2-Device Wi-Fi Lobby** so a second phone on the same Wi-Fi router can join your race room. |
| `com.android.vending.billing` | Enables optional Google Play In-App Purchases (such as the 60-Track DLC Expansion Pack or Remove Ads VIP Edition). |

---

## 4. Local Wi-Fi Multiplayer (Peer-to-Peer LAN)

APEX VECTOR includes an optional **2-Device Local Wi-Fi Multiplayer** mode (1v1 Duel Series and Co-Op Campaign Discovery).

- When you host or join a match on your local Wi-Fi network, the two devices exchange temporary UDP datagrams (`port 41234`) directly over your local router (LAN).
- These packets contain only ephemeral race state: room number, selected track ID, ship coordinates (`x, y, vx, vy, angle`), and finish time.
- **No multiplayer traffic is routed through external internet servers, and no chat, voice, or personal identifiers are transmitted.**

---

## 5. In-App Purchases & Third-Party Services (Google Play)

If you download APEX VECTOR from the **Google Play Store** and choose to make an optional In-App Purchase (such as unlocking the **60-Track DLC Pack** or **Remove Ads VIP Edition**):

- All payment transactions are processed securely and directly by **Google Play Billing**.
- **We never receive, view, or store your credit card number, bank details, or billing address.** We only receive a non-personal purchase token/confirmation from the Google Play Billing API indicating whether a product SKU (e.g., `dlc_pack_1` or `ad_free`) is unlocked on your device.
- If optional third-party services (such as Google Play Services or Google AdMob for non-VIP versions, if enabled in a future release) are used by the distribution platform, their processing is governed by Google's Privacy Policy:
  - [Google Privacy Policy](https://policies.google.com/privacy)
  - [Google Play Terms of Service](https://play.google.com/intl/en_us/about/play-terms/)

---

## 6. Children's Privacy (COPPA & GDPR-K)

APEX VECTOR is an arcade vector racing game suitable for general audiences. We do **not** knowingly collect any personal information from children under the age of 13 (or under the applicable age of digital consent in your jurisdiction, such as 16 in the EEA). Because the Game does not collect personal data from any user, no personal data from children is collected, stored, or shared. If you are a parent or guardian and have any questions or concerns, please contact us using the details in Section 9.

---

## 7. Your Privacy Rights (GDPR, UK GDPR, CCPA / CPRA)

Depending on where you live (including the European Economic Area, the United Kingdom, Switzerland, Brazil, or California and other US states), you have statutory rights regarding personal data (such as the right to access, delete, correct, or opt out of the sale/sharing of personal information).

Because **ME Racing** does not collect, retain, or sell any personal data or cross-context behavioral advertising profiles on external servers:

- **Right to Access / Portability:** All data generated by your gameplay exists exclusively on your own device.
- **Right to Erasure / Deletion:** You can delete 100% of your app data immediately at any time by clearing the app data in your Android system settings or uninstalling the Game.
- **No Sale or Sharing of Personal Information:** We do not sell or share personal information as defined under the California Consumer Privacy Act (CCPA/CPRA).

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time (for example, if new gameplay features or platform integrations are added). Any updates will be posted directly to this repository and webpage with an updated **"Last Updated"** date at the top of the document.

---

## 9. Contact Us

If you have any questions or requests regarding this Privacy Policy or **APEX VECTOR**, please contact us:

- **Developer:** ME Racing (`meracing`)
- **GitHub Repository & Issue Tracker:** [https://github.com/meracing/Apex-Vector-privacy-policy/issues](https://github.com/meracing/Apex-Vector-privacy-policy/issues)
- **Web Privacy Policy URL:** [https://meracing.github.io/Apex-Vector-privacy-policy/](https://meracing.github.io/Apex-Vector-privacy-policy/)
