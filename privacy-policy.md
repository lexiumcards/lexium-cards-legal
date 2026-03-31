---
layout: default
title: Privacy Policy — Lexium Cards
---

# Privacy Policy

**Last updated:** March 29, 2026

**Developer:** Yurii Dobrovolskyi ("we", "us", "our")

**Contact:** lexiumcards@gmail.com

Welcome to Lexium Cards! This Privacy Policy explains how we collect, use, and protect your personal data when you use our mobile application Lexium Cards (the "App"), available on the App Store and Google Play.

We process personal data in accordance with the General Data Protection Regulation (EU) 2016/679 ("GDPR") and other applicable data protection laws.

All personal data is obtained directly from you or your device during use of the App, or from third-party authentication providers (Google, Apple) during sign-in.

---

## 1. Personal Data We Collect

### 1.1 Account Information

When you create an account using Google Sign-In or Apple Sign-In, we receive:

- Email address
- Name (given name and family name, if provided by the authentication provider)

We do not store your password. Authentication is handled entirely by Google or Apple through secure OAuth protocols.

### 1.2 User-Generated Content

Content you create within the App:

- Decks (language pair selections)
- Collections (themed word sets)
- Flashcards (words, translations, notes)
- Study progress and spaced repetition state

Please do not use the App to store sensitive personal information (health data, political opinions, religious beliefs, etc.) in your flashcards or notes.

### 1.3 Study and Progress Data

- Daily study scores and streaks
- Card review history (iterations, review timestamps)
- Session activity

### 1.4 User Settings

- Interface language preference
- Active deck selection
- Theme preference (light/dark)

### 1.5 Subscription and Purchase Data

When you subscribe to a paid plan, we collect:

- Transaction identifiers
- Subscription status (active, expired, cancelled)
- Platform of purchase (iOS or Android)

This data is processed by RevenueCat, our third-party payment processor, for subscription management and receipt validation. We do not collect or store your payment method details (credit card numbers, billing address, etc.) — these are handled entirely by the App Store, Google Play, and RevenueCat.

### 1.6 Usage Data and Analytics

When you use the App in production, we collect pseudonymized usage data through Mixpanel:

- Pseudonymous user identifier (internal account ID)
- Feature usage events (which screens you visit, actions you take)
- App environment metadata (platform, app version)

Mixpanel data is processed on EU servers (api-eu.mixpanel.com).

### 1.7 Diagnostics and Error Reporting

Through Sentry, we collect crash reports and error logs in production:

- Error type and stack trace
- Operation context (which feature caused the error)
- Error codes and operation duration
- Basic device information (OS version, app version)

This data is used solely to identify and fix bugs.

### 1.8 Data Processed by AI Services

When you use translation and vocabulary features, the text you submit is processed by:

- **Google Gemini** — for word analysis, translation variants, and category classification
- **Google Cloud Translation** — for quick translations
- **Google Cloud Text-to-Speech** — for word pronunciation audio

This processing happens on our server (Supabase Edge Functions). The text you submit is sent to Google's APIs for processing. We cache AI responses on our server to improve performance and reduce repeated API calls. Cached data does not contain personally identifiable information — only the text content and its processed result.

### 1.9 Locally Stored Data

Some data is cached locally on your device for offline access and performance, including study data and user settings. This data remains on your device and is cleared when you log out or uninstall the App.

### 1.10 Cookies and Tracking Technologies

The App does not use cookies or similar web-based tracking technologies. Authentication tokens and cached data are stored locally on your device using standard platform storage mechanisms.

---

## 2. How We Use Your Data

We use your personal data for the following purposes:

| Purpose                                                                        | Data Used                                        | Legal Basis             |
| ------------------------------------------------------------------------------ | ------------------------------------------------ | ----------------------- |
| Provide core App functionality (flashcards, study sessions, progress tracking) | Account info, user content, study data, settings | Performance of contract |
| Authenticate your identity                                                     | Account info (via Google/Apple)                  | Performance of contract |
| Generate translations and word analysis                                        | Text submitted by you                            | Performance of contract |
| Synthesize pronunciation audio                                                 | Text submitted by you                            | Performance of contract |
| Manage subscriptions and validate purchases                                    | Purchase data (via RevenueCat)                   | Performance of contract |
| Improve App quality and fix bugs                                               | Diagnostics data                                 | Legitimate interest     |
| Understand feature usage and improve the App                                   | Pseudonymized usage data (analytics)             | Legitimate interest     |
| Respond to your inquiries                                                      | Contact information, communication content       | Legitimate interest     |
| Comply with legal obligations                                                  | Account info, purchase info (when applicable)    | Legal obligation        |

### Automated Decision-Making

The App uses automated algorithms (spaced repetition) to determine your study schedule. These decisions are based solely on your study history and do not produce legal or similarly significant effects.

---

## 3. Data Storage and Security

### 3.1 Where Your Data Is Stored

Your data is stored on Supabase infrastructure hosted in cloud data centers. Authentication tokens and cached data are stored locally on your device.

### 3.2 Security Measures

- All data in transit is encrypted using TLS/HTTPS
- Database access is protected by Row-Level Security (RLS) — each user can only access their own data
- Authentication tokens are stored locally on your device
- Server-side API keys are stored as encrypted environment variables

### 3.3 Data Retention

- **Account data and user content:** retained as long as your account exists
- **Analytics data (Mixpanel):** retained for up to 12 months
- **Error logs (Sentry):** retained for up to 90 days
- **AI response cache:** retained indefinitely (contains no personal data)
- **TTS audio cache:** retained indefinitely (contains no personal data)

When you delete your account, all your personal data (account info, cards, collections, decks, study progress) is permanently deleted from our database.

---

## 4. Third-Party Services

We share data with the following third-party service providers:

| Service                               | Purpose                                         | Data Shared                                 | Privacy Policy                                                                                     |
| ------------------------------------- | ----------------------------------------------- | ------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Supabase** (Supabase Inc.)          | Backend, database, authentication, file storage | All user data                               | [supabase.com/privacy](https://supabase.com/privacy)                                               |
| **Google** (Google LLC)               | Sign-In authentication                          | Email, profile info                         | [policies.google.com/privacy](https://policies.google.com/privacy)                                 |
| **Apple** (Apple Inc.)                | Sign-In authentication (iOS)                    | Email, name                                 | [apple.com/privacy](https://www.apple.com/privacy/)                                                |
| **Sentry** (Functional Software Inc.) | Error monitoring and crash reporting            | Error logs, device metadata                 | [sentry.io/privacy](https://sentry.io/privacy/)                                                    |
| **Mixpanel** (Mixpanel Inc.)          | Product analytics                               | Pseudonymized usage events, user identifier | [mixpanel.com/legal/privacy-policy](https://mixpanel.com/legal/privacy-policy/)                    |
| **RevenueCat** (RevenueCat Inc.)      | Subscription management and receipt validation  | Transaction IDs, subscription status, platform | [revenuecat.com/privacy](https://www.revenuecat.com/privacy)                                       |
| **Google Cloud AI** (Google LLC)      | Translation, word analysis (Gemini), TTS        | Text content submitted by user              | [cloud.google.com/terms/cloud-privacy-notice](https://cloud.google.com/terms/cloud-privacy-notice) |

All third-party providers are either located in the EEA, covered by EU adequacy decisions, or operate under Standard Contractual Clauses (SCCs) or the EU-U.S. Data Privacy Framework.

---

## 5. Children's Privacy

The App is not intended for children under the age of 13. We do not knowingly collect personal data from children under 13. If we discover that a child under 13 has created an account, we will promptly delete their data. If you are a parent or guardian and believe your child has provided us with personal data, please contact us at lexiumcards@gmail.com.

---

## 6. Your Rights

Under the GDPR and applicable data protection laws, you have the right to:

- **Access** your personal data
- **Rectify** inaccurate or incomplete data
- **Erase** your personal data ("right to be forgotten")
- **Restrict** processing of your data
- **Data portability** — receive your data in a machine-readable format
- **Object** to processing based on legitimate interest
- **Withdraw consent** at any time (where processing is based on consent)
- **Lodge a complaint** with a supervisory authority — EU residents may contact their local data protection authority

### How to Exercise Your Rights

- **Delete your account:** available directly in the App (Settings)
- **Other requests:** email us at lexiumcards@gmail.com

We will respond to your request within 30 days. In complex cases, this may be extended by an additional 60 days, and we will inform you of any extension.

---

## 7. Data Transfers

Your data may be transferred to and processed in countries outside the European Economic Area (EEA). When this occurs, we ensure appropriate safeguards are in place, including:

- EU adequacy decisions
- Standard Contractual Clauses (SCCs)
- EU-U.S. Data Privacy Framework certification

---

## 8. Marketing Communications

We do not currently send marketing communications or newsletters. If we do in the future, we will update this Privacy Policy and provide you with opt-out mechanisms.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make significant changes, we will notify you through the App or by other appropriate means. The updated policy will indicate the "Last updated" date at the top.

We encourage you to review this Privacy Policy periodically.

---

## 10. Dispute Resolution

For EU residents, the European Commission provides an online dispute resolution platform at [https://ec.europa.eu/consumers/odr](https://ec.europa.eu/consumers/odr).

---

## 11. Contact Us

If you have any questions about this Privacy Policy or our data practices, please contact us:

**Email:** lexiumcards@gmail.com

**Developer:** Yurii Dobrovolskyi
