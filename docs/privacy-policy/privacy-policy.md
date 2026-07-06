# Privacy Policy — Convertica

**Last updated:** July 6, 2026

**App name:** Convertica  
**Developer:** SSForge  
**Contact:** [omerss.apps@gmail.com](mailto:omerss.apps@gmail.com)

---

## Introduction

This Privacy Policy explains how SSForge (“we,” “us,” or “our”) handles information when you use **Convertica**, a mobile utility app for currency conversion, unit conversion, document scanning and export, date calculations, and camera-based scanning.

By using Convertica, you agree to the practices described in this policy. If you do not agree, please do not use the app.

This document is written to meet Google Play requirements and to give you a clear, transparent overview of our data practices. It may be adapted for other SSForge apps with app-specific details updated where noted.

---

## Information We Collect

Convertica is designed to work primarily on your device. We do **not** require you to create an account, and we do **not** operate a backend service that stores your documents, photos, or scan content on SSForge servers.

Depending on how you use the app, the following types of information may be processed:

| Category | Examples | Where it is processed |
|----------|----------|------------------------|
| **Usage analytics** | Feature usage events (e.g., app opened, conversion completed, scan completed) | Google Firebase Analytics (see below) |
| **Diagnostic data** | Crash logs, stack traces, device and app version | Google Firebase Crashlytics (see below) |
| **Advertising data** | Ad impressions, ad identifiers | Google AdMob (see below) |
| **On-device content you create** | Scanned photos, cropped images, extracted text, exported files | Your device only |
| **Local preferences** | Language choice, onboarding completion, cached exchange rates | Your device only |
| **Network requests** | Anonymous requests to public exchange-rate APIs | Sent from your device to third-party services |

We do **not** knowingly collect names, email addresses, phone numbers, or payment information through Convertica unless you contact us directly by email.

Convertica uses **Google Firebase** for usage analytics and crash reporting. These services help us understand how features are used and improve stability. They do **not** receive your document content, OCR text, file names, free-form input, or conversion amounts (see the Firebase sections below).

---

## Camera Permission

Convertica requests access to your device **camera** only when you choose a scan-related feature, such as:

- Scanning a price or unit label (Currency / Unit scan flows)
- Scanning a document for OCR and export

**Important points:**

- The camera is used **only for scanning and capture** related to these features.
- Convertica does **not** record audio or access your microphone. The app does not request microphone permission.
- Images captured for scanning are processed to fulfill the feature you requested (for example, text recognition or conversion). They are not uploaded to SSForge servers.

You can deny camera permission; scan features will not work without it, but other app features remain available.

---

## Document Processing

When you use the **Document Converter** feature:

- You capture or select an image on your device.
- You may crop the image before processing.
- Text recognition (OCR) runs **on your device** using Google ML Kit (on-device text recognition).
- Extracted text and exported files (PDF, TXT, DOCX, etc.) are stored **locally on your device** unless you choose to share them through your device’s share sheet.

**SSForge does not receive, store, or access your documents, photos, or extracted text on our own servers.**

You are responsible for exported files saved on your device and for any content you share with third parties.

---

## Firebase Analytics

Convertica uses **Firebase Analytics** to understand how the app is used and to improve performance and features.

**Purpose:**

- Analyze app usage patterns
- Understand which features are used
- Improve app performance and user experience

**Examples of event types we may collect** (not the content of your actions):

- App opened
- Currency conversion completed
- Unit conversion completed
- Document scan completed
- Document export completed
- Date calculation completed
- General feature usage (e.g., screen opened)

**What Firebase Analytics does not collect through Convertica:**

- OCR text from document scans
- Document or image content
- File names of exported documents
- Free-form text you type in the app
- Currency amounts, prices, or other values you convert

Analytics events are limited to **non-personal, aggregated usage signals** (such as event names and general categories). We design our analytics to avoid sending sensitive or user-entered content.

For more information, see [Google’s Privacy Policy](https://policies.google.com/privacy) and [Firebase documentation](https://firebase.google.com/support/privacy).

---

## Firebase Crashlytics

Convertica uses **Firebase Crashlytics** to collect crash and error reports when the app fails unexpectedly.

**Purpose:**

- Collect crash reports
- Diagnose errors and bugs
- Improve app stability and reliability

**Examples of information that may be included in crash reports:**

- Crash logs and stack traces
- Android OS version
- Device model (manufacturer and model name)
- App version and build number

**What Crashlytics does not include:**

- Document content or OCR results from your scans
- Text you entered in converters or document fields
- Photos, exports, or file names from your device

Crash reports are used solely to fix technical issues. They are processed by Google under Firebase terms.

---

## Data Security

We take reasonable steps to protect information processed through Convertica and the third-party services we use:

- Data transmitted to Firebase, AdMob, and other online services is sent over **secure connections** (such as HTTPS/TLS) where supported by those services.
- **Firebase and Google** apply their own industry-standard security practices, access controls, and infrastructure protections as described in their documentation.
- Most of your scan content, documents, and conversion data remain **on your device** and are not uploaded to SSForge servers.

No method of transmission or storage is 100% secure. If you have concerns about security, contact us at the address below.

---

## Advertising (Google AdMob)

Convertica displays advertisements through **Google AdMob** to support the free version of the app.

During **closed testing and development**, the app may show **Google test ads** so that advertising can be verified without live campaigns.

After **public release**, Convertica may display **live Google AdMob advertisements** in supported regions, subject to Google’s policies and your device settings.

AdMob may collect and use information to show and measure ads, which may include:

- Advertising ID (e.g., Google Advertising ID on Android)
- Device information (device type, OS version)
- Ad interaction data (impressions, clicks)
- Approximate location derived from IP address (as permitted by your device settings)

You can limit ad personalization through your device settings (for example, “Opt out of Ads Personalization” on Android).

For more information, see Google’s advertising policies and privacy documentation:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

---

## Data Storage

Most Convertica data stays **on your device**, including:

- Cached currency exchange rates
- App settings and preferences
- Document scan history and exported files you create
- Onboarding and language preferences

Data may be removed when you uninstall the app or clear app storage through your device settings, subject to how your operating system handles app data.

SSForge does **not** maintain a central cloud database of your personal scan content or conversion history.

---

## Third-Party Services

Convertica relies on the following third-party services:

| Service | Purpose |
|---------|---------|
| **Google Firebase Analytics** | Usage analytics and feature insights |
| **Google Firebase Crashlytics** | Crash and stability reporting |
| **Google AdMob** | Displaying banner advertisements |
| **Google ML Kit (on-device)** | Text recognition for scan features |
| **Frankfurter API** | Public exchange-rate data for the currency converter |
| **Google Play services** | App distribution and platform services (Android) |

We may add or update third-party services over time (for example, additional Firebase products such as Remote Config, or new analytics events). When we do, we will update this Privacy Policy and the **“Last updated”** date where appropriate.

Each third party processes data under its own privacy policy. We encourage you to review Google’s policies at [policies.google.com](https://policies.google.com/privacy).

Network requests for exchange rates do not include your personal identity; they request public rate data needed for the currency feature to function.

---

## User Rights

Depending on your location, you may have rights regarding your personal data, including under the **GDPR** (European Economic Area, UK, and similar jurisdictions) and other applicable laws.

These rights may include:

- **Access** — request information about data processed about you where applicable
- **Rectification** — request correction of inaccurate data we hold about you (primarily relevant to data you send us directly, such as support emails)
- **Erasure** — request deletion of personal data we control
- **Restriction or objection** — object to or restrict certain processing where applicable
- **Data portability** — receive data you provided in a portable format where applicable
- **Withdraw consent** — where processing is based on consent, withdraw it at any time

Because most Convertica processing occurs on your device, you can also:

- Reset your advertising ID or limit ad tracking in device settings
- Clear app data or uninstall the app to remove locally stored information
- Manage Google ad settings related to AdMob where applicable

To exercise your rights or ask questions, contact us at **[omerss.apps@gmail.com](mailto:omerss.apps@gmail.com)**. We will respond within a reasonable time as required by applicable law.

If you are in the EEA/UK, you may also lodge a complaint with your local data protection authority.

---

## Children's Privacy

Convertica is a general-purpose utility app and is **not directed at children under 13** (or the minimum age required in your country).

We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us at **[omerss.apps@gmail.com](mailto:omerss.apps@gmail.com)** and we will take steps to delete such information where we are able to do so.

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in the app, legal requirements, third-party services (including Firebase or advertising), or our practices.

When we make material changes, we will update the **“Last updated”** date at the top of this document. For significant changes, we may also provide notice within the app or through the app store listing where appropriate.

Your continued use of Convertica after an update means you accept the revised policy.

---

## Contact

If you have questions, concerns, or requests regarding this Privacy Policy or Convertica’s data practices, please contact:

**SSForge**  
Email: [omerss.apps@gmail.com](mailto:omerss.apps@gmail.com)

---

*This policy applies to Convertica (package name: `com.ssforge.convertica`) published by SSForge.*

<!--
Release TODO (maintainers only — not shown in rendered policy)

- Update Google Play Data Safety form when Firebase or ad settings change
- Review collected data categories after new analytics events or Firebase products
-->
