# Privacy Policy — GratitudeGlow

**Last updated:** 2026-03-21
**Effective date:** 2026-03-21

This Privacy Policy describes how **Sudarshan Tech Labs** ("we", "us", or "our") handles information in the **GratitudeGlow** Android application ("the App").

---

## 1. About This App

GratitudeGlow is a gratitude journaling app with cloud-backed accounts. Users create an account, write daily gratitude entries, and sync data across devices via Firebase Firestore.

---

## 2. Data We Collect

### 2.1 Account Information

| Data | Purpose | Storage |
|---|---|---|
| Email address | Account identification | Firebase Authentication |
| Display name | Profile display | Firebase Authentication, Firestore |
| Authentication tokens | Secure sign-in | Firebase Authentication |
| Google account info (if Google Sign-In used) | Authentication | Firebase Authentication |

### 2.2 Journal Content

| Data | Purpose | Storage |
|---|---|---|
| Gratitude journal entries (text) | Core app functionality | Firebase Firestore |
| Entry dates and timestamps | Journaling history | Firebase Firestore |
| Streak and progress data | Habit tracking | Firebase Firestore |
| App preferences | Personalisation | DataStore (on-device) |

### 2.3 Analytics and Crash Data

| Data | Purpose | Storage |
|---|---|---|
| App usage events | Improve user experience | Firebase Analytics |
| Crash reports (device info, stack trace) | App stability | Firebase Crashlytics |

---

## 3. How Data Is Used

- To provide the journaling service and sync entries across sessions
- To authenticate you securely via Firebase Authentication
- To track your gratitude streak and journaling progress
- To improve the App through aggregated analytics
- To diagnose and fix crashes via Crashlytics

---

## 4. Data Sharing

We do not sell your data. Your journal entries are private to your account and are not accessible to other users.

Data is processed by:

- **Google Firebase (Authentication, Firestore, Analytics, Crashlytics)** — https://firebase.google.com/support/privacy
- **Google (Google Sign-In)** — https://policies.google.com/privacy

No other third-party sharing occurs.

---

## 5. Permissions Explained

| Permission | Reason |
|---|---|
| `INTERNET` | Required for Firebase sync, authentication, and analytics |

---

## 6. Data Retention

| Data | Retention |
|---|---|
| Account and journal data | Until you delete your account |
| Firebase Analytics | Aggregated, 14 months (per Firebase policy) |
| Firebase Crashlytics | 90 days (per Firebase policy) |

---

## 7. Your Rights

You have the right to:

- **Access** your journal entries within the App
- **Delete** individual entries within the App
- **Delete** your account and all associated data (see Data Deletion guide)
- **Export** your data by contacting us at sudarshantechlabs@gmail.com

---

## 8. Account Deletion

To delete your account and all associated journal data:

1. Open the App
2. Go to **Settings > Account > Delete Account**

Or contact us at sudarshantechlabs@gmail.com with the subject "Account Deletion Request".

All Firestore data associated with your account will be permanently deleted within 30 days.

---

## 9. Children's Privacy

GratitudeGlow is not directed at children under 13. We do not knowingly collect personal information from children. If we become aware that a child under 13 has created an account, we will delete it promptly.

---

## 10. Data Security

- Authentication is handled by Firebase Authentication with industry-standard security
- Data is encrypted in transit (HTTPS/TLS)
- Firebase Firestore security rules restrict data access to the authenticated owner
- App code obfuscation is applied in release builds

---

## 11. Changes to This Policy

We will notify you of significant changes by updating the "Last updated" date and, where appropriate, through an in-app notice. Continued use of the App constitutes acceptance.

---

## 12. Contact

**Sudarshan Tech Labs**
Official website: https://sudarshantechlabs.com
Company email: sudarshantechlabs@gmail.com
Developer contact: sunny.sudarshan@gmail.com

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Email address | Yes | No | Account authentication |
| Journal entries | Yes | No | App functionality |
| App interactions | Yes (Firebase Analytics) | No | Analytics |
| Crash logs | Yes (Crashlytics) | No | App stability |

---

*This policy applies to the GratitudeGlow Android application published by Sudarshan Tech Labs.*
