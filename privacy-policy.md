---
layout: page
title: "AuraEat Nexus — Privacy Policy"
permalink: /auraeat/privacy-policy/
---

# Privacy Policy

**AuraEat Nexus**
_Effective Date: April 1, 2026_
_Last Updated: April 1, 2026_

---

## 1. Introduction

AuraEat Nexus ("AuraEat", "we", "us", or "our") is a circadian nutrition intelligence app that aligns your eating window with your biological rhythms using biometric data from Apple HealthKit and AI-powered food analysis. We take the privacy and security of your health data extremely seriously.

This Privacy Policy describes how we collect, use, store, and protect your information when you use the AuraEat Nexus mobile application (the "App"). By using the App, you agree to the practices described in this policy.

---

## 2. Information We Collect

### 2.1 Apple HealthKit Data

With your explicit permission, the App reads the following data from Apple HealthKit:

- **Sleep Analysis** — sleep duration, sleep stages, and quality metrics to determine your actual wake-up and bedtime.
- **Heart Rate** — average beats per minute (BPM) to assess cardiovascular recovery.
- **Heart Rate Variability (HRV)** — millisecond-level variability data to compute metabolic readiness.
- **Resting Heart Rate** — daily resting heart rate to detect elevated stress or recovery states.

With your explicit permission, the App writes the following data to Apple HealthKit:

- **Water Intake** — hydration entries logged within the App, so your data stays consistent across Health-connected apps.

**We do not access any HealthKit data categories beyond those listed above.**

### 2.2 Data You Provide Directly

- **Food photos** — images you capture or select for AI-based nutritional grading.
- **Manual meal timestamps** — times you log for your last meal.
- **Hydration entries** — beverage type, volume, and timestamps.
- **App settings** — language preference, wake/bedtime overrides, privacy mode selections, and hydration goals.

### 2.3 Data We Do NOT Collect

- We do **not** collect your name, email address, phone number, or other personal contact information.
- We do **not** collect location data.
- We do **not** use advertising identifiers or tracking technologies.
- We do **not** collect device identifiers for the purpose of user tracking.

---

## 3. How We Use Your Information

All data collected is used exclusively to provide core App functionality:

| Data | Purpose |
|------|---------|
| Sleep Analysis | Calculate your personalized daily eating window (Aura-Sync algorithm) |
| Heart Rate & HRV | Compute your Aura Score — a metabolic readiness metric that fine-tunes eating window timing |
| Resting Heart Rate | Detect recovery state and adjust eating window delay |
| Food Photos | AI-powered nutritional grading (glycemic load and circadian impact assessment) |
| Meal Timestamps | Meal-sleep correlation analysis to discover your optimal last-meal-to-bedtime gap |
| Hydration Entries | Track daily water intake and sync to Apple Health |

**We do not use your health data for advertising, marketing, data mining, or any purpose other than providing and improving the App's core health features.**

---

## 4. Third-Party Services

### 4.1 Groq AI (Large Language Model)

The App uses **Groq**, a third-party AI inference service, for two features:

1. **Food Photo Grading** — Your food photos are compressed (resized and quality-reduced) and sent to Groq's API for nutritional analysis. No personally identifiable information is attached to these images.

2. **Daily Wellness Insights** — Aggregated, non-identifying biometric values (sleep score, HRV value, resting heart rate, and Aura Score as numerical values only) are sent to generate personalized wellness tips.

**What is NOT sent to Groq:**
- Your name, account information, or any personal identifiers
- Raw HealthKit data or Apple Health records
- Your location, device identifiers, or contact information
- Historical health data — only the current day's aggregated metrics

Groq processes data pursuant to their own privacy policy and data processing terms. We select AI models and configure prompts to minimize data exposure.

### 4.2 Apple HealthKit

Apple HealthKit data is accessed through Apple's secure HealthKit framework. We comply fully with Apple's HealthKit guidelines:

- **HealthKit data is never shared with third parties** for advertising or data-brokering purposes.
- **HealthKit data is never sold.**
- **HealthKit data is never used for purposes unrelated** to the App's health and fitness functionality.
- **HealthKit data is not stored in iCloud** or any cloud service by the App.

### 4.3 No Other Third-Party Data Sharing

Beyond the limited data sent to Groq as described above, we do not share, sell, rent, or otherwise disclose your personal or health data to any third party.

---

## 5. Data Storage and Security

### 5.1 Local-First Architecture

All your data is stored **locally on your device** using encrypted on-device storage (AsyncStorage). This includes:

- Cached HealthKit snapshots (up to 30 days)
- Food scan history and grades
- Meal-sleep correlation history (up to 60 days)
- Streak and badge progress
- Hydration logs
- App settings and preferences

### 5.2 No Cloud Storage

The App does **not** upload your health data, food logs, or biometric information to any cloud server or remote database controlled by us. Your data stays on your device.

### 5.3 Security Measures

- All data remains on-device within the App's sandboxed storage.
- HealthKit data is accessed through Apple's secure, permissioned framework.
- Food images sent to Groq are compressed and transmitted over encrypted HTTPS connections.
- The App does not implement user tracking (NSPrivacyTracking is set to `false`).

---

## 6. Data Retention and Deletion

- **HealthKit cache**: Up to 30 days of historical biometric data, automatically managed.
- **Meal-sleep correlation history**: Up to 60 days, automatically pruned.
- **Food scan logs**: Retained until you clear them.
- **All data can be deleted** at any time through the App's Settings screen ("Clear Data" option), which permanently removes all locally stored data.
- **Uninstalling the App** removes all App data from your device.
- HealthKit data written by the App (water intake) can be managed directly through Apple's Health app.

---

## 7. Children's Privacy

AuraEat Nexus is not directed at children under the age of 17. We do not knowingly collect personal or health data from children. If you believe a child has provided us with data, please contact us and we will promptly delete it.

---

## 8. Your Rights and Choices

You have full control over your data:

- **HealthKit Permissions** — You can grant or revoke HealthKit access at any time through your device's Settings > Health > AuraEat.
- **Privacy Mode** — The Nexus community feature includes a "Share My Aura" / "Anonymous Aura" toggle. When anonymous, no personal biometric data is visible to other users.
- **Data Deletion** — You can delete all App data at any time from the Settings screen.
- **Opt Out of AI Features** — You can choose not to use the food scanner or AI insights; the core eating window functionality operates using only local HealthKit data.

If you are located in the European Economic Area (EEA), you may have additional rights under the General Data Protection Regulation (GDPR), including the right to access, rectify, or erase your data, and the right to data portability. Contact us to exercise these rights.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Last Updated" date at the top of this page. We encourage you to review this policy periodically. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us at:

**Email:** janerik.sternberg@alumni.esade.edu

---

_This privacy policy is provided in connection with the AuraEat Nexus app, developed as part of the IdeaUp Challenge (ESADE/Ennova)._
