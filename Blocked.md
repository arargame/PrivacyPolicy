# Blocked: Pixel Panzer – Privacy Policy (Android)

**Last Updated: 22 September 2026**

This privacy policy explains what data the mobile game **Blocked: Pixel Panzer** (package name `com.arargames.blocked`, "the Game") processes, why, and what choices you have.

The Game is developed and published by **Arar Games** ("we", "us").  
Contact: **arargame@hotmail.com** | **korayarar@gmail.com**

---

## Summary

The Game does **not** collect personally identifiable information (PII) such as your real name, email address, phone number, physical address, contacts, photos, microphone, or camera access, and it does **not** track your precise GPS location.

However, the Game integrates standard mobile game services for in-game advertising, in-app purchases, gameplay analytics, and Google platform features. These services involve data processing that is described in detail below.

---

## Data We Process

### 1. Analytics & Telemetry (Google Analytics for Firebase)

The Game uses **Google Analytics for Firebase** (Firebase Analytics) to analyze game performance, balance tank battles, evaluate progression funnels, and improve player experience.

Data processed includes:
- **Anonymous Gameplay Events:** Level started (`level_started`), level completed (`level_completed`), level failed (`level_failed`), shop interactions, powerup upgrades, boss battle outcomes, and rewarded ad revive responses.
- **Screen Transitions (`screen_view`):** Navigated menus and screens (such as `MainMenuScreen`, `GameBoard`, `PauseScreen`, `GameOverScreen`).
- **Anonymous User Properties:** Progression stage bucket (`progress_bucket`), unlocked level, control style preference, and device performance tier (`device_tier`).
- **Pseudonymous Player Identifier:** A randomly generated local GUID assigned upon installation (`PlayerId`). This identifier is completely random and contains no personally identifiable data.
- **Firebase App Instance ID:** An anonymous, auto-generated pseudonymous identifier created by Google Play Services.

**GDPR / Privacy Safeguard:**  
In accordance with GDPR, KVKK, and Google UMP guidelines, Firebase Analytics data collection is **disabled by default** on app startup (`firebase_analytics_collection_enabled = false`). Collection is only enabled after user consent choices are established through the consent form.

Learn more:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Firebase Privacy and Security in Firebase](https://firebase.google.com/support/privacy)

---

### 2. Advertising (Google AdMob)

The Game displays banner, interstitial, and optional rewarded video ads through **Google AdMob**.

Google may collect and process:
- Your **advertising identifier** (Android Advertising ID). The Game declares the `com.google.android.gms.permission.AD_ID` permission for this purpose.
- Technical device data (device model, Android OS version, language, screen resolution).
- **Approximate location** derived from your IP address (country/city level, never precise GPS).
- Ad interactions, impressions, and video completion status.

Google acts as an independent controller/processor for ad serving. You can review how Google uses this data at [Google's Partner Privacy Policy](https://policies.google.com/technologies/partner-sites).

---

### 3. Consent Management (Google User Messaging Platform)

If you reside in the **European Economic Area (EEA), the United Kingdom, or Switzerland**, the Game presents a consent dialog powered by the **Google User Messaging Platform (UMP)** on initial launch.

- Your consent preferences (including IAB TCF 2.2 standard values) are stored **locally on your device**.
- Personalised advertising and analytics data collection are only activated if permitted under your selected choices.
- **You can change or withdraw your consent at any time:** Open **Options → PRIVACY OPTIONS** inside the Game.

---

### 4. In-App Purchases (Google Play Billing)

The Game offers optional digital purchases processed **exclusively through Google Play Billing** (e.g., removing advertisements, gold packs, and tank upgrades).

- All payment information (credit cards, bank accounts, billing addresses) is processed securely and exclusively by **Google Play**.
- Arar Games **never** receives, views, or stores your financial or payment details.
- Verified purchase state is cached locally in encrypted application storage to unlock items offline.

---

### 5. Google Play Games Services

The Game integrates **Google Play Games Services** for achievements and cloud leaderboards.

- If you sign in with your Google Play Games account, Google processes your gamer profile and scores.
- Signing in is entirely **optional**. The Game is fully playable offline without signing in.

---

### 6. Local Game Data & Offline Storage

Your game progress, high scores, audio volume settings, and configurations are stored locally on your device in private application storage.

- Game save files are stored locally and are not sold or transferred to external servers.
- Clearing application data or uninstalling the Game removes locally stored files.

---

### 7. Local Notifications

The Game may schedule **local offline reminder notifications** using the standard Android AlarmManager.

- These notifications are created and triggered entirely offline on your device without any external push notification server.
- You can enable or disable notifications at any time via Android Settings → Apps → Blocked → Notifications.

---

## Legal Basis (GDPR / KVKK)

For users protected under the GDPR, UK GDPR, or Turkish KVKK (Law No. 6698):

- **Consent (Art. 6(1)(a) GDPR):** For personalised advertising and analytics storage, obtained via Google UMP.
- **Contractual Necessity (Art. 6(1)(b) GDPR):** For delivering in-app purchases processed via Google Play.
- **Legitimate Interests (Art. 6(1)(f) GDPR):** For game security, bug diagnostics, invalid traffic detection, and non-personalised ad delivery.

---

## Data Retention & Deletion

- **Local save files & purchase cache:** Retained locally until you clear app data or uninstall the Game.
- **Analytics & Diagnostic data:** Retained by Google Analytics according to the standard retention period (up to 14 months), after which it is automatically deleted.
- **Data Deletion Inquiries:** To request deletion of records associated with your random Player ID or for any data privacy inquiry, contact us at **arargame@hotmail.com**.

---

## Children's Privacy

The Game is designed for general audiences and is **not directed to children under 13** (or under 16 in the EEA). We do not knowingly solicit or collect personal information from children. If you believe a child has provided personal information through third-party services in the Game, please contact us at **arargame@hotmail.com** so we can take immediate corrective measures.

---

## Third-Party Services Summary

| Service | Provider | Purpose | Link |
| :--- | :--- | :--- | :--- |
| **Google Analytics for Firebase** | Google LLC | Gameplay telemetry & optimization | [Privacy Policy](https://policies.google.com/privacy) |
| **Google AdMob** | Google LLC | In-game advertising | [Privacy Policy](https://policies.google.com/technologies/partner-sites) |
| **Google UMP** | Google LLC | Consent management (GDPR/KVKK) | [Privacy Policy](https://policies.google.com/privacy) |
| **Google Play Billing** | Google LLC | In-app purchase processing | [Terms of Service](https://play.google.com/about/play-terms/) |
| **Google Play Games** | Google LLC | Achievements & Leaderboards | [Privacy Policy](https://policies.google.com/privacy) |

---

## Contact

**Arar Games**  
Developer: Koray Arar  
Location: Bursa, Türkiye  
Email: **arargame@hotmail.com** | **korayarar@gmail.com**  
Website: [https://arargames.com](https://arargames.com)  
GitHub: [https://github.com/arargame](https://github.com/arargame)
