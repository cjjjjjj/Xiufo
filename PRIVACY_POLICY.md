# Privacy Policy for 潜心修佛 (Mindful Buddhist Meditation) Chrome Extension

**Last Updated:** June 30, 2026

We take your privacy very seriously. This Privacy Policy describes how the **潜心修佛** Chrome Extension (the "Extension") handles your data.

---

## 1. No Collection of Personal Information
The Extension is built with a local-first design. We do not collect, store, or transmit any personally identifiable information (PII), such as your name, email address, physical address, browsing history, or account credentials. 

## 2. Local Storage and Data Retention
To maintain your meditation progress, the Extension saves the following data locally on your device using Chrome's secure storage API (`chrome.storage.local`):
- **Accumulated Meditation Time** (`totalSeconds`)
- **Woodfish Knock Counts** (`muyuCount`)
- **Donated Merit Time** (`donatedSeconds`)
- **Donated Woodfish Counts** (`donatedMuyu`)
- **Current Meditation State** (meditating, interrupted, or shielded)
- **Active Shield Expiry Time** (`shieldExpiry`)

**All of this data stays strictly on your local machine.** We have no servers to store this data, and it is never uploaded or shared with any third party. If you uninstall the Extension, all locally stored records are immediately and permanently deleted by the browser.

## 3. Network Connections and Third-Party Integrations
The Extension makes outward network requests strictly to support its core functions:
- **Alipay Integration (`https://openapi.alipay.com/*`)**: Initiates secure pre-create trade requests when you buy custom protection hours (Golden Bell Shield). No personal financial account details or credit numbers are processed or visible to the Extension.
- **IP Address Verification (`https://api.ipify.org/*`)**: Verifies network connectivity for the payment module. Your IP address is never stored or tracked.
- **QR Code Generation (`https://api.qrserver.com/*`)**: Renders checkout QR codes. No user details are transmitted to this service.
- **httpbin (`https://httpbin.org/*`)**: Used for sandbox payment integration testing. No personal data is transmitted.

## 4. Permissions Disclosures
The Extension requests the following browser permissions to perform its core functions:
- **`storage`**: Used solely to persist your meditation counts and stats locally.
- **`alarms`**: Used to wake up the background script to increment meditation time and calculate random interruptions.
- **`notifications`**: Used to alert you with a desktop notification when the meditating monk is interrupted (e.g. by sweat or wind).

## 5. Changes to This Policy
 We may update this Privacy Policy from time to time. Any changes will be posted on this page with the updated revision date.

## 6. Contact Us
If you have any questions or feedback regarding your privacy when using the Extension, please contact us at:
- **Support Email**: support@xiufo.local (or your registered Web Store developer email)
