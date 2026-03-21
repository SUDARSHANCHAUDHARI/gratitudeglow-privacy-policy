# GratitudeGlow — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

GratitudeGlow is a guided gratitude journaling app for Android. It uses Firebase Authentication for secure accounts and Firebase Firestore to sync your journal entries across sessions. This policy explains exactly what is collected, where it is stored, and how you can delete it.

---

## Data Collection

### Account Information

| Data | Purpose | Storage |
|---|---|---|
| Email address | Account identification and sign-in | Firebase Authentication |
| Display name | Profile display within the App | Firebase Authentication, Firestore |
| Google account info (if Google Sign-In used) | Authentication only | Firebase Authentication |
| Authentication session tokens | Maintain secure sign-in | Firebase Authentication |

### Journal Content

| Data | Purpose | Storage |
|---|---|---|
| Gratitude journal entries (text, prompts, date) | Core app functionality | Firebase Firestore |
| Entry timestamps and streaks | Progress tracking | Firebase Firestore |
| Journaling preferences and app settings | Personalisation | DataStore on your device |

### Analytics and Crash Data

| Data | Purpose | Storage |
|---|---|---|
| App usage events (screens visited, features used) | App improvement | Firebase Analytics |
| Device model, OS version, app version | Analytics context | Firebase Analytics |
| Crash stack traces (no personal data) | App stability | Firebase Crashlytics |

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Authenticate you securely | Firebase Authentication |
| Store and display your journal entries | Firebase Firestore |
| Maintain your gratitude streak | Firestore streak data |
| Improve app features | Firebase Analytics (aggregated) |
| Fix crashes and bugs | Firebase Crashlytics |

---

## Data Storage and Security

- **Authentication:** Firebase Authentication with Google's secure infrastructure
- **Journal data:** Firebase Firestore with encryption in transit (HTTPS/TLS) and at rest
- **Firestore security rules:** Your data is accessible only to your authenticated account
- **Local preferences:** Stored in DataStore on your device

## Data Retention

| Data | Retention |
|---|---|
| Account and Firestore data | Until you delete your account |
| Local preferences | Until you uninstall the App |
| Firebase Analytics | Aggregated, 14 months (Firebase default) |
| Firebase Crashlytics | 90 days (Firebase default) |

---

## Data Sharing

We do not sell your data. Your journal entries are private to your account. Data is processed by:

- **Google Firebase (Authentication, Firestore, Analytics, Crashlytics):** https://firebase.google.com/support/privacy
- **Google (Google Sign-In):** https://policies.google.com/privacy

---

## Account Deletion

You have the right to delete your account and all associated data at any time.

### Option 1 — In-App Deletion
1. Open GratitudeGlow
2. Go to **Settings**
3. Tap **Account**
4. Tap **Delete Account**
5. Confirm the deletion

### Option 2 — Email Request
Send an email to **sudarshantechlabs@gmail.com** with:
- Subject: **GratitudeGlow Account Deletion Request**
- Your registered email address

We will process your request within 30 days and send confirmation.

### What Gets Deleted
- ✅ Firebase Authentication account (email, display name)
- ✅ All gratitude journal entries in Firestore
- ✅ All streak and progress data
- ✅ All app preferences

### What May Remain
- Aggregated, anonymised Firebase Analytics data (cannot be linked to you)
- Firebase Crashlytics reports (no personal data)

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `INTERNET` | Required for Firebase Authentication, Firestore, Analytics, and Crashlytics |

---

## Your Rights and Controls

- **View and edit entries:** Directly within the App
- **Delete individual entries:** Use the delete option within any entry
- **Delete account:** See Account Deletion section above
- **Export data:** Contact us at sudarshantechlabs@gmail.com

---

## Children's Privacy

GratitudeGlow is not directed at children under 13. We do not knowingly create accounts for children under 13. If we become aware that a child under 13 has registered, we will delete the account promptly.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of GratitudeGlow after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## GDPR Rights (EU Users)

If you are in the European Economic Area, you have the right to:

- **Access** — Request a copy of your personal data
- **Rectification** — Correct inaccurate data
- **Erasure** — Request deletion of your data
- **Restrict Processing** — Limit how we use your data
- **Data Portability** — Receive your data in a portable format
- **Object** — Object to certain types of processing

To exercise these rights, contact us at the details above.

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Email address | Yes | No | Account authentication |
| Journal entries | Yes | No | App functionality |
| App interactions | Yes (Firebase Analytics) | No | Analytics |
| Crash logs | Yes (Crashlytics) | No | App stability |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
