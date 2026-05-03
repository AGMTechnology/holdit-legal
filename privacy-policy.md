---
layout: default
title: Privacy Policy - HoldIt
permalink: /privacy-policy
---

# Privacy Policy

**HoldIt - Try Not To Laugh Challenge**
**Last Updated: March 19, 2026**

---

## 1. Introduction

This Privacy Policy describes how HoldIt ("we," "our," or "the app") collects, uses, and protects your information when you use the HoldIt mobile application. We are committed to protecting your privacy and being transparent about our data practices.

By using HoldIt, you agree to the collection and use of information as described in this policy.

---

## 2. Information We Collect

### 2.1 Camera and Face Detection

HoldIt uses your device's front-facing camera solely during active gameplay to detect facial expressions (smiling and laughing). All face detection processing occurs entirely on your device. No photos, videos, or biometric data are ever captured, stored, transmitted, or shared. The camera feed is analyzed in real-time to produce a simple numerical smile probability score, which exists only in temporary memory and is discarded immediately after each gameplay session.

**What face data is collected:**
- A smiling probability score (a number from 0.0 to 1.0) computed on-device from each camera frame
- A face-detected boolean (true/false) indicating whether a face is visible

**How face data is used:**
- The smiling probability score determines if the player is smiling or laughing during gameplay. If the score exceeds a threshold, the player loses a life.
- The face-detected boolean pauses the game when no face is visible.

**Face data storage and retention:**
- Face data is **never stored** on disk, in databases, or in any persistent storage
- Face data exists **only in volatile device memory (RAM)** during active gameplay
- Face data is **discarded immediately** when the gameplay round ends or the app is closed
- No face data is **ever transmitted** over the network or shared with any third party

**Face data and third parties:**
- Face data is **never shared** with any third party, including our own servers
- All face processing uses on-device frameworks (Apple Vision/Google ML Kit) with no cloud processing

**Technical implementation:**
- Face detection is powered by the device's native machine learning frameworks (Apple Vision framework on iOS, Google ML Kit on Android) via react-native-vision-camera
- Only two numerical values (smile probability and face-detected boolean) are produced — no face maps, feature vectors, depth data, or biometric identifiers are generated

You can use HoldIt without granting camera access, but the reaction detection gameplay feature will not be available.

### 2.2 Anonymous Account

When you first open HoldIt, an anonymous account is automatically created for you. This account:
- Is identified by a randomly generated unique ID
- Does **not** require an email address, phone number, name, or any personal information
- Is used solely to track your game progress, XP, leaderboard ranking, and achievements
- Is stored securely on our servers

You may optionally link your account to a sign-in provider in future updates, but this is never required.

### 2.3 Gameplay Data

We collect gameplay session data to provide game features:
- Reaction outcomes per content item (held, smiled, laughed)
- Streak counts, XP earned, round scores
- Content items you have viewed (to avoid showing duplicates)
- Session timestamps and duration
- Content reports you submit via the in-game report button

### 2.4 Device Information

We may collect basic device information for app functionality:
- Device type and operating system version
- App version
- Network status (online/offline)

We do **not** collect your device's unique advertising identifier unless you grant tracking permission (see Section 3).

### 2.5 In-App Purchase Data

If you make an in-app purchase (e.g., "Remove Ads"), the transaction is processed entirely by Apple (App Store) or Google (Google Play). We do **not** collect or store your payment information, credit card details, or billing address. We only receive a purchase confirmation (product ID and transaction status) to unlock the purchased feature.

---

## 3. Advertising and Tracking

### 3.1 Ad Services

HoldIt displays advertisements provided by Google AdMob to support free gameplay. Ad types include:
- **Interstitial ads** — full-screen ads shown between game rounds
- **Rewarded video ads** — optional ads you choose to watch for in-game rewards (extra life, bonus XP)
- **Banner ads** — small ads displayed on game over and round summary screens

### 3.2 App Tracking Transparency (iOS)

On iOS, HoldIt will ask for your permission before allowing ad networks to track your activity across other apps and websites. This is the standard Apple App Tracking Transparency (ATT) prompt.

- If you **allow** tracking: AdMob may use your advertising identifier to show more relevant ads
- If you **deny** tracking: You will still see ads, but they will be non-personalized
- You can change this setting at any time in your device's Settings > Privacy > Tracking

### 3.3 Ad Data

When ads are displayed, Google AdMob may collect:
- Ad interaction data (impressions, clicks)
- Device information for ad targeting
- IP address (for approximate location-based ad targeting)

This data is collected and processed by Google under [Google's Privacy Policy](https://policies.google.com/privacy). We request non-personalized ads by default.

---

## 4. How We Use Your Information

We use the information we collect to:
- Provide and maintain the HoldIt gameplay experience
- Track your game progress, XP, level, and achievements
- Display leaderboards and rankings
- Prevent duplicate content in your feed
- Display advertisements to support free gameplay
- Process content reports and maintain content quality
- Improve app performance and fix bugs
- Process and validate in-app purchases

We do **not**:
- Sell your personal information to third parties
- Use facial recognition or biometric identification
- Store or transmit camera images or video
- Track your location
- Send marketing emails or push notifications (unless you opt in)

---

## 5. Data Storage and Security

- Gameplay data and anonymous accounts are stored on secure servers
- Camera data never leaves your device
- All communication between the app and our servers uses HTTPS encryption
- We use industry-standard security measures to protect your data
- In-app purchase validation is handled through official Apple and Google APIs

---

## 6. Data Retention

- Your anonymous account and gameplay data are retained as long as you use the app
- If you uninstall the app and do not reinstall within 12 months, your anonymous account data may be deleted
- Content reports are retained for moderation purposes
- Ad interaction data is managed by Google AdMob per their retention policies

---

## 7. Children's Privacy

HoldIt is rated 12+ and is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe a child under 13 has provided us with personal information, please contact us and we will delete it.

---

## 8. Third-Party Services

HoldIt uses the following third-party services:

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Google AdMob | Advertising | [Google Privacy Policy](https://policies.google.com/privacy) |
| Apple App Store | App distribution, IAP | [Apple Privacy Policy](https://www.apple.com/privacy/) |
| Google Play Store | App distribution, IAP | [Google Privacy Policy](https://policies.google.com/privacy) |
| Expo | App framework | [Expo Privacy Policy](https://expo.dev/privacy) |

---

## 9. Your Rights

You have the right to:
- **Deny camera access** — The app works without camera, but reaction detection is disabled
- **Deny ad tracking** — You will still see ads, but they will be non-personalized
- **Report content** — Use the in-game report button to flag inappropriate content
- **Delete your data** — Contact us to request deletion of your anonymous account and associated data
- **Restore purchases** — Use the "Restore Purchases" option in the app to recover previous in-app purchases on a new device

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any significant changes by updating the "Last Updated" date at the top of this policy. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 11. Contact Us

If you have questions about this Privacy Policy or want to request data deletion, contact us at:

**Email:** ahmed.agoummadane@gmail.com
**Website:** https://agmtechnology.github.io/holdit-legal/support

---

*This privacy policy is effective as of March 19, 2026.*
