# Privacy Policy

**Move 37 — Board Game App**  
**Last Updated:** February 22, 2026

---

## Table of Contents
1. [Information We Collect](#1-information-we-collect)
2. [How We Use Information](#2-how-we-use-information)
3. [Third-Party Services](#3-third-party-services)
4. [Data Sharing](#4-data-sharing)
5. [GDPR & Privacy Rights](#5-gdpr--privacy-rights)
6. [Data Security](#6-data-security)
7. [Data Retention](#7-data-retention)
8. [Children's Privacy](#8-childrens-privacy)
9. [Your Rights & Choices](#9-your-rights--choices)
10. [Changes to This Policy](#10-changes-to-this-policy)
11. [Consent](#11-consent)
12. [Contact](#12-contact)

---

## 1. Information We Collect
Move 37 ("the App") uses the following services to provide advertising, analytics, crash reporting, and AI-powered game analysis. Each service collects data as described below.

### 1.1 Google AdMob (Advertising SDK)
We use Google AdMob to display advertisements. AdMob may collect:
* **Advertising Identifier** — IDFA (iOS) / GAID (Android), used to deliver personalized ads
* **Device information** — device model, OS version, screen resolution, language
* **IP address** — used for approximate geolocation and fraud prevention
* **Ad interaction data** — impressions, clicks, view duration

Ad formats displayed: **Banner**, **Interstitial (full-screen)**, and **Rewarded Video**.

On iOS 14.5+, we request App Tracking Transparency (ATT) permission before accessing your IDFA. If you decline, only non-personalized ads are shown. On Android and in EEA/UK regions, a GDPR User Messaging Platform (UMP) consent dialog is presented before personalized ad delivery.

[Google Privacy Policy →](https://policies.google.com/privacy)

### 1.2 Meta Audience Network (AdMob Mediation)
We use Meta Audience Network (operated by Meta Platforms, Inc.) as a mediation partner for advertisements. When the App displays ads from Meta, Meta may collect:
* **Advertising Identifier** — IDFA (iOS) / GAID (Android)
* **App usage data** — interactions with ads and the App
* **Device technical information** — OS version, device model, mobile carrier
* **IP address** — used for approximate location and fraud prevention

Meta use this data to provide localized and personalized advertising. For more information on how Meta processes your information, please visit [Meta's Privacy Policy](https://www.facebook.com/about/privacy/).

### 1.3 AppLovin (Ad Mediation)

We work with AppLovin to deliver ads in our app. AppLovin and its partners may collect device identifiers, usage data, and other information for advertising and analytics purposes. For more information, visit: [https://www.applovin.com/privacy/](https://www.applovin.com/privacy/)

### 1.4 Firebase Analytics
We use Firebase Analytics (Google) to understand how users interact with the App. Firebase Analytics collects:
* **App Instance ID** — a pseudonymous identifier per app installation
* **Session data** — session start/end, session duration
* **In-app events** — game start, game end, feature usage, screen views
* **User properties** — language/locale, country, app version
* **Ad revenue data** — aggregate AdMob impression and revenue events (linked via Firebase–AdMob integration)
* **Device & OS information** — device model, OS version, app version

Firebase Analytics data is transmitted to Google's servers. You can opt out via device settings (see Section 9).

[Firebase Privacy →](https://firebase.google.com/support/privacy)

### 1.5 Firebase Crashlytics
We use Firebase Crashlytics to automatically detect and diagnose app crashes. Crashlytics collects:
* **Crash reports** — stack traces, error types, error messages
* **Device information** — device model, OS version, available memory, CPU architecture
* **App state** — app version, time of crash, whether device was jailbroken/rooted
* **Crashlytics Installation UUID** — a pseudonymous per-install identifier

Crash data does **not** include personal information such as names, email addresses, or game content.

[Firebase Privacy →](https://firebase.google.com/support/privacy)

### 1.6 AI Game Analysis — Google Gemini API
Move 37 offers an optional AI-powered game analysis feature. When you request an analysis of a completed game, the following data is transmitted to Google's Gemini API:
* **Move history** — the sequence of moves made during the game (no personal identifiers)
* **Board state** — initial and final board layout
* **Game metadata** — game type, difficulty level, winner, turn count, time remaining
* **Locale** — your language preference (e.g., "en", "ko"), used to return analysis in your language
* **IP address** — collected by our API server solely for rate-limiting purposes (5 requests/minute per IP); not stored persistently

> **Important:** Game analysis data is transmitted to Google's Gemini API *only when you actively request an analysis*. This feature is entirely optional and can be ignored if you prefer not to send data externally.

No personally identifiable information (name, email, user ID) is included in analysis requests. The data is used solely to generate the analysis response and is subject to [Google's Gemini API Terms of Service](https://ai.google.dev/gemini-api/terms) and [Google's Privacy Policy](https://policies.google.com/privacy).

### 1.6 Locally Stored Data
The following data is stored **only on your device** and is never transmitted to our servers:
* Game settings and preferences (difficulty, theme)
* Game history and statistics
* Cached AI analysis results (to avoid redundant network requests)

This data is stored in the app's local storage on your device. You can delete it by uninstalling the App.

### 1.7 Data We Do NOT Collect
> We do **not** collect: name, email address, phone number, precise location (GPS), payment information, contacts, photos, or any other personally identifiable information beyond what is described above.

---

## 2. How We Use Information

| Purpose | Data Used | Legal Basis (GDPR) |
| :--- | :--- | :--- |
| Display advertising (personalized or non-personalized) | Ad ID, device info, IP (AdMob, Meta) | Consent (EEA/UK) / Legitimate interest |
| App performance & usage analytics | App Instance ID, events, user properties (Firebase Analytics) | Legitimate interest |
| Ad revenue analysis | AdMob impression & revenue events (Firebase–AdMob integration) | Legitimate interest |
| Crash detection & app stability | Crash logs, device info (Crashlytics) | Legitimate interest |
| AI game analysis (on request) | Move history, board state, metadata, locale, IP (Gemini API) | Consent (implied by voluntary feature use) |
| Local app functionality | On-device storage only | Contract performance |

---

## 3. Third-Party Services
The App integrates the following third-party services, all operated by Google LLC:

* **Google AdMob (Advertising)**: Mobile advertising platform. Processes advertising identifiers and device data to serve ads. [Privacy Policy](https://policies.google.com/privacy) · [Opt-out](https://support.google.com/ads/answer/2662922)
* **Meta Audience Network (Advertising)**: AdMob mediation partner. Processes device identifiers and interaction data to serve personalized ads. [Privacy Policy](https://www.facebook.com/about/privacy/) · [Ad settings](https://www.facebook.com/help/568137493302217)
* **Google Firebase Analytics (Analytics)**: App usage analytics. Processes app events, session data, and user properties. [Firebase Privacy](https://firebase.google.com/support/privacy) · [Opt-out](https://firebase.google.com/support/privacy#disable_firebase_analytics_collection)
* **Google Firebase Crashlytics (Crash Reporting)**: Automated crash reporting. Processes stack traces and device metadata when the app crashes. [Firebase Privacy](https://firebase.google.com/support/privacy)
* **Google Gemini API (AI Analysis)**: Generative AI service. Processes game move data to produce strategic analysis. Activated only on user request. [Terms of Service](https://ai.google.dev/gemini-api/terms) · [Privacy Policy](https://policies.google.com/privacy)

All five services may transfer data to the United States and other countries where Google or Meta operates. These transfers are governed by their respective Data Processing Terms and Standard Contractual Clauses.

### iOS — SKAdNetwork
On iOS, the App includes Apple's SKAdNetwork framework (registered in Info.plist) to support privacy-preserving advertising attribution. This framework does not transmit personal data; attribution is handled at the network level by Apple.

---

## 4. Data Sharing
We do **not sell** your personal data. Data is shared only in the following circumstances:
* **With Google & Meta** — via AdMob, Meta Audience Network, Firebase Analytics, Crashlytics, and Gemini API as described in Section 3.
* **Legal obligations** — if required by applicable law, court order, or governmental authority.
* **Business transfer** — in the event of a merger, acquisition, or asset sale, user information may be transferred as part of that transaction, subject to the same privacy protections.

No other third-party sharing occurs.

---

## 5. GDPR & Privacy Rights

### 5.1 User Messaging Platform (UMP) Consent
Users in the European Economic Area (EEA), United Kingdom, and Switzerland are shown a **GDPR consent dialog** on first launch, implemented via Google's User Messaging Platform (UMP). This dialog allows you to:
* Accept personalized advertising (requires consent)
* Accept only non-personalized advertising
* Manage your consent preferences at any time

Personalized ads are only delivered after affirmative consent. If you decline or limit consent, non-personalized ads are shown instead.

### 5.2 Your Rights Under GDPR (EEA/UK Users)
If you are located in the EEA, UK, or Switzerland, you have the following rights under GDPR / UK GDPR:
* **Right of access** — request a copy of data held about you
* **Right to rectification** — request correction of inaccurate data
* **Right to erasure** — request deletion of your data ("right to be forgotten")
* **Right to restriction** — request that we limit processing
* **Right to data portability** — receive your data in a structured, machine-readable format
* **Right to object** — object to processing based on legitimate interests
* **Right to withdraw consent** — withdraw consent at any time (affects future processing only)

To exercise these rights, contact us at [visionary.0419@gmail.com](mailto:visionary.0419@gmail.com). For data held by Google, you may also contact Google directly through their privacy portal.

You have the right to lodge a complaint with your local data protection authority (DPA).

### 5.3 Legal Basis Summary
| Processing Activity | Legal Basis |
| :--- | :--- |
| Personalized advertising (AdMob, Meta) | Consent (Art. 6(1)(a) GDPR) |
| App analytics (Firebase Analytics) | Legitimate interest (Art. 6(1)(f) GDPR) |
| Crash reporting (Crashlytics) | Legitimate interest (Art. 6(1)(f) GDPR) |
| AI game analysis (Gemini) | Consent via voluntary use (Art. 6(1)(a) GDPR) |

---

## 6. Data Security
We take reasonable technical and organizational measures to protect your data:
* API communications are encrypted using HTTPS/TLS.
* The Gemini API key is stored only on the server side and is never exposed to client applications.
* We do not maintain our own user databases; data processing is delegated to Google's infrastructure, which maintains its own security certifications (ISO 27001, SOC 2).

---

## 7. Data Retention
| Data Type | Retention Period | Controlled By |
| :--- | :--- | :--- |
| AdMob advertising identifiers & interaction data | Up to 63 days (Google standard) | Google LLC |
| Meta Audience Network data | Up to 2 years or as long as necessary for the purpose | Meta Platforms, Inc. |
| Firebase Analytics event data | 2 months or 14 months (configurable by developer) | Google LLC |
| Firebase Crashlytics crash reports | 90 days | Google LLC |
| Gemini API — game data sent for analysis | Data used to generate the response; subject to Google's API data retention policy | Google LLC |
| IP address (rate limiting) | Not persisted; held only in-memory during request processing | Our API server |
| Local device data (settings, history, cached analysis) | Until app is uninstalled or storage is cleared | User |

For details on Google's data retention practices, see [Google's Data Retention Policy](https://policies.google.com/technologies/retention).

---

## 8. Children's Privacy
Move 37 is not directed at children under the age of 13 (or under 16 in the EEA). We do not knowingly collect personal data from children. If we become aware that a child has provided personal information, we will take steps to delete it.

If you are a parent or guardian and believe your child has used the App, please contact us at [visionary.0419@gmail.com](mailto:visionary.0419@gmail.com).

---

## 9. Your Rights & Choices

### Advertising Personalization Opt-out
* **iOS:** Go to *Settings → Privacy & Security → Tracking* and disable "Allow Apps to Request to Track". When ATT permission is denied, Move 37 shows non-personalized ads only.
* **Android:** Go to *Settings → Google → Ads → Delete advertising ID* or enable "Opt out of Ads Personalization".
* **In-app (EEA/UK):** Use the GDPR consent dialog shown at first launch to manage your advertising preferences.

### Firebase Analytics Opt-out
* You may opt out of Firebase Analytics data collection by disabling analytics tracking in the device settings (both iOS and Android provide per-app tracking settings).
* Alternatively, contact us at [visionary.0419@gmail.com](mailto:visionary.0419@gmail.com) to request opt-out processing.

### AI Game Analysis
Using the AI analysis feature is entirely voluntary. If you do not want game data transmitted to Google's Gemini API, simply do not use the "Analyze Game" feature.

### iOS App Tracking Transparency (ATT)
On iOS 14.5 and later, when you first open Move 37, you will be prompted by the system ATT dialog asking whether to allow tracking across apps and websites. If you select **"Ask App Not to Track"**, the App will:
* Not access your IDFA
* Display only non-personalized advertisements
* Otherwise function normally with no feature restrictions

### Deleting Local Data
You can delete all locally stored data by uninstalling the App from your device.

---

## 10. Changes to This Policy
We may update this Privacy Policy from time to time. When we do, we will update the "Last Updated" date at the top of this page. For significant changes, we will provide in-app notification.

We encourage you to review this policy periodically. Continued use of the App after changes constitutes acceptance of the revised policy.

---

## 11. Consent
By downloading and using Move 37, you consent to the data practices described in this Privacy Policy. Where applicable law requires explicit consent (e.g., GDPR for personalized advertising), we obtain that consent through in-app consent dialogs before processing begins.

---

## 12. Contact
If you have questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact:

**Move 37 — Developer**  
Email: [visionary.0419@gmail.com](mailto:visionary.0419@gmail.com)  
GitHub: [github.com/kai-0419](https://github.com/kai-0419)

We aim to respond to all inquiries within 30 days.

---
© 2026 Move 37. All rights reserved.
