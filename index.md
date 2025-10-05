# Privacy Policy for Arc

**Effective Date:** October 5, 2025  
**Last Updated:** October 5, 2025

---

## Introduction

Welcome to **Arc** (AI Summary), developed by **Rethink**. We are committed to protecting your privacy and being transparent about how we handle your data. This Privacy Policy explains what information we collect, how we use it, and your rights regarding your data.

By using Arc, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information We Collect

### 1.1 Information You Provide

**Google Account Information:**
- When you sign in with Google, we collect:
  - Your Google ID
  - Email address
  - Full name
  - Profile information

**Content You Create:**
- Text summaries you generate
- Content you explicitly save
- Screenshots you choose to save
- Categories and tags you assign
- Search queries within the app

### 1.2 Information Collected Automatically

**Screen Content:**
- When you request a summary or use the "Read Aloud" feature, Arc temporarily accesses the text content displayed on your screen through Android's Accessibility Service
- This content is processed in real-time and is **never stored on our servers**

**Technical Information:**
- Device information (model, operating system version)
- App version
- Network connectivity status
- Crash logs and performance data

**Usage Data:**
- Features you use
- Interaction patterns within the app
- Timestamp of actions

### 1.3 Information We Do NOT Collect

- We do **not** collect your screen content except when you explicitly request a summary or use the Read Aloud feature
- We do **not** monitor your activity in other apps
- We do **not** store or log screen content on our servers
- We do **not** collect location data
- We do **not** access your contacts, camera, or microphone

---

## 2. How We Use Your Information

### 2.1 To Provide Core Features

**AI Summaries:**
- Screen text is sent to Google Gemini API (or OpenAI as fallback) to generate summaries
- This is done only when you explicitly tap "Summarize"
- The text is processed and immediately discarded—never stored

**Read Aloud (Text-to-Speech):**
- Uses Android's built-in TTS engine
- No data is sent to external servers for this feature

**Save and Organize:**
- Summaries, screenshots, and metadata are stored locally on your device using Room database
- Accessible only to you

### 2.2 To Authenticate Users

- Google Sign-In is used to authenticate your identity
- Your authentication token is stored securely on your device
- Backend servers store basic user information (Google ID, email, name) to manage your account

### 2.3 To Provide Backup Services

- **Google Drive Backup (Optional):**
  - You can choose to back up your saved summaries and screenshots to your personal Google Drive
  - Data is stored in your Google Drive's "appDataFolder" (private to the app)
  - Only you can access this backup
  - You control when backups occur

### 2.4 To Display Advertisements

- For free tier users, we display ads through Google AdMob
- AdMob may collect device identifiers and usage data for ad personalization
- You can opt out of personalized ads through your device settings

### 2.5 To Improve the App

- Crash reports and performance data help us fix bugs and improve stability
- Usage analytics help us understand which features are most valuable

---

## 3. How We Share Your Information

### 3.1 Third-Party Services

We share data with the following third-party services to provide functionality:

**Google Services:**
- **Google Sign-In:** For authentication
- **Google Drive API:** For optional backups (only to your personal Drive)
- **Google Gemini API:** For AI-powered text summarization
- **Google AdMob:** For displaying advertisements (free tier users)

**OpenAI (Fallback):**
- May be used as a fallback AI provider if Gemini is unavailable
- Screen text is sent only when you request a summary

**AWS DynamoDB:**
- Our backend uses AWS DynamoDB to store user account information
- Hosted in the US East (N. Virginia) region
- Stores: User ID, Google ID, email, name, account status

### 3.2 What We Share

- **With Google Gemini/OpenAI:** Only the on-screen text content when you request a summary (not stored by us)
- **With Google Drive:** Only the data you choose to back up (summaries, screenshots)
- **With AdMob:** Device advertising ID, app usage data for ad targeting
- **With our backend:** Authentication tokens, basic profile information

### 3.3 What We Do NOT Share

- We do **not** sell your personal information to anyone
- We do **not** share your content with third parties for marketing purposes
- We do **not** share your screen content with anyone except the AI service you're using (Gemini/OpenAI) and only when you explicitly request it

---

## 4. Data Storage and Security

### 4.1 Where Your Data is Stored

**On Your Device:**
- All saved summaries, screenshots, search history, and preferences are stored locally using Room database
- Encrypted by Android's built-in security

**On Our Servers:**
- Only basic user account information (Google ID, email, name)
- Authentication tokens
- Stored securely on AWS DynamoDB with encryption at rest

**On Your Google Drive (Optional):**
- Backup files are stored in your personal Google Drive
- Only accessible to you

### 4.2 Security Measures

- **Encryption in Transit:** All communications use HTTPS/TLS encryption
- **Encryption at Rest:** AWS DynamoDB data is encrypted at rest
- **Secure Authentication:** JWT tokens for backend authentication
- **No Plaintext Passwords:** We use Google Sign-In; we never see your password
- **Limited Access:** Our backend servers follow the principle of least privilege

### 4.3 Data Retention

- **On Device:** Data remains until you delete it or uninstall the app
- **Backups:** Remain in your Google Drive until you delete them
- **Server Data:** User account information is retained while your account is active
- **Screen Content:** Never stored—processed and immediately discarded

---

## 5. Your Rights and Choices

### 5.1 Access and Control

- **View Your Data:** All saved content is accessible within the app
- **Delete Data:** You can delete individual summaries or clear all data from Settings
- **Export Data:** Use the Google Drive backup feature to export your data
- **Account Deletion:** Sign out and request account deletion by contacting us

### 5.2 Google Drive Backup

- Backup is **optional** and disabled by default
- You control when backups occur (manual or scheduled)
- You can disable backups at any time from Settings
- You can delete backup files from your Google Drive at any time

### 5.3 Advertising

- **Opt Out of Personalized Ads:**
  - Android: Settings → Google → Ads → Opt out of Ads Personalization
  - Or use your device's "Limit Ad Tracking" setting
- **Upgrade:** Paid users do not see advertisements

### 5.4 Accessibility Service

- You grant Arc permission to use Android's Accessibility Service to read screen content
- This is only used when you explicitly request a summary or use Read Aloud
- You can revoke this permission at any time from Android Settings → Accessibility

---

## 6. Children's Privacy

Arc is **not intended for children under 13 years of age**. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided us with personal information, please contact us at [everythingrethink@gmail.com](mailto:everythingrethink@gmail.com), and we will delete such information.

---

## 7. International Data Transfers

Arc is operated from and our backend servers are located in the United States. If you are accessing Arc from outside the U.S., your information may be transferred to, stored, and processed in the U.S., where data protection laws may differ from those in your country.

By using Arc, you consent to the transfer of your information to the U.S. and other countries where we operate.

---

## 8. Compliance with Privacy Laws

### 8.1 GDPR (European Users)

If you are in the European Economic Area (EEA), you have the following rights under the General Data Protection Regulation (GDPR):

- **Right to Access:** Request a copy of your personal data
- **Right to Rectification:** Correct inaccurate data
- **Right to Erasure:** Request deletion of your data ("Right to be Forgotten")
- **Right to Restrict Processing:** Limit how we use your data
- **Right to Data Portability:** Receive your data in a machine-readable format
- **Right to Object:** Object to processing based on legitimate interests
- **Right to Withdraw Consent:** Withdraw consent at any time

To exercise these rights, contact us at [everythingrethink@gmail.com](mailto:everythingrethink@gmail.com).

### 8.2 CCPA (California Users)

If you are a California resident, you have rights under the California Consumer Privacy Act (CCPA):

- **Right to Know:** What personal information we collect and how we use it
- **Right to Delete:** Request deletion of your personal information
- **Right to Opt-Out:** Opt out of the "sale" of personal information (we do not sell your data)
- **Right to Non-Discrimination:** Equal service regardless of privacy choices

To exercise these rights, contact us at [everythingrethink@gmail.com](mailto:everythingrethink@gmail.com).

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or for legal, regulatory, or operational reasons. When we make changes:

- We will update the "Last Updated" date at the top of this policy
- For material changes, we will notify you through the app or via email
- Continued use of Arc after changes constitutes acceptance of the updated policy

We encourage you to review this Privacy Policy periodically.

---

## 10. Third-Party Links

Arc may contain links to third-party websites or services (e.g., when you open a source URL). We are not responsible for the privacy practices of these third parties. We encourage you to read the privacy policies of any third-party sites you visit.

---

## 11. Permissions Explained

Arc requires the following Android permissions:

| Permission | Purpose | When Used |
|------------|---------|-----------|
| **Accessibility Service** | Read on-screen text for summaries | Only when you tap "Summarize" or "Read Aloud" |
| **Internet** | Communicate with AI services and backend | Throughout app usage |
| **System Alert Window** | Display floating sidebar overlay | When floating sidebar is enabled |
| **Network State** | Check connectivity before API calls | Throughout app usage |
| **Foreground Service** | Keep sidebar accessible while using other apps | When sidebar is active |
| **Boot Completed** | Restart sidebar after device reboot (if enabled) | On device startup |
| **Post Notifications** | Show backup status and other notifications | When relevant events occur |

All permissions are used only for their stated purpose and in accordance with this Privacy Policy.

---

## 12. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or how we handle your data, please contact us:

**Email:** [everythingrethink@gmail.com](mailto:everythingrethink@gmail.com)

**Developer:** Rethink  
**App:** Arc (AI Summary)

We aim to respond to all inquiries within 7 business days.

---

## 13. Summary

**What We Collect:**
- Google account info (when you sign in)
- Content you save
- Screen text (only when you request a summary—not stored)

**What We Do:**
- Send screen text to AI services (Gemini/OpenAI) only when you request it
- Store your saved summaries locally on your device
- Optionally back up to your personal Google Drive
- Use secure authentication and encryption

**What We Don't Do:**
- Store or log your screen content on servers
- Monitor your activity in other apps
- Sell your data to third parties
- Access your data without your permission

**Your Control:**
- Delete data anytime from the app
- Control backups
- Opt out of personalized ads
- Request account deletion

---

**By using Arc, you acknowledge that you have read and understood this Privacy Policy.**

---

*This privacy policy is effective as of October 5, 2025.*

