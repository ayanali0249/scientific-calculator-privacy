# Privacy Policy for Scientific Calculator

**Effective Date:** October 20, 2026  
**Application ID:** `com.ayanali.scientific_calculator`  
**Developer:** Ayan Ali  
**Contact Email:** ayankalwaniya7890@gmail.com  

---

## 1. Introduction

Scientific Calculator ("we", "our", or "the app") respects your privacy. This Privacy Policy outlines our data handling practices and discloses what information is processed when you use our mobile application.

The core calculator is designed **offline-first**: all mathematical calculations, equations, numerical calculus, matrices, vectors, complex numbers, statistical formulas, unit conversions, and calculation histories run strictly on your local device without sending your mathematical inputs or results to any server.

---

## 2. Information We Collect and Process

### A. Mathematical Computations & Calculator Usage (Zero Collection)
- **Zero Server Transmission:** All calculations, formulas, variables, matrix entries, statistical datasets, and history records are processed strictly on your device.
- We do **not** transmit, collect, log, or store your expressions, calculation results, or history on any external servers or third-party cloud services.
- Your calculation history, memory values, and user preferences are stored locally on your device via Android's private app sandbox (`SharedPreferences`) and are erased when you clear app data or uninstall the application.

### B. Advertising & Diagnostics Data (Google Mobile Ads SDK)
The app integrates the **Google Mobile Ads SDK (AdMob)** to display non-intrusive banner advertisements. The SDK may automatically process certain technical device information, which Google handles according to its own privacy policy:
- **Advertising Identifiers:** Android Advertising ID (AAID) and Google Play Services identifiers used by Google to deliver, measure, and attribute advertisements, as well as detect and prevent fraudulent ad traffic.
- **Network & Diagnostics Information:** IP address, mobile network status, connection type, and ad performance/crash diagnostic logs.
- **Coarse Location Data:** General geographic region inferred from your IP address to display relevant advertisements (where permitted by your device settings).
- **Ad Interaction Data:** Views, impressions, and click interactions with banner advertisements.

For further information on how Google processes advertising data and your privacy controls, refer to:
- [Google Privacy & Terms](https://policies.google.com/privacy)
- [Google AdMob Data Safety Disclosures](https://support.google.com/admob/answer/10705229)

---

## 3. Permissions Breakdown

### A. Declared Application Permissions
The application's manifest explicitly requests only two basic network permissions:
- `android.permission.INTERNET`: Allows the Google Mobile Ads SDK to fetch and render banner ads.
- `android.permission.ACCESS_NETWORK_STATE`: Allows the Google Mobile Ads SDK to detect network availability before attempting ad requests.

### B. Transitive Permissions Merged by Google Mobile Ads SDK
When compiled, the Google Mobile Ads SDK transitively includes the following system permissions to support modern Android ad delivery and fraud prevention:
- `com.google.android.gms.permission.AD_ID`: Required on Android 13 (API level 33) and higher for Google Play Services to access the Android Advertising ID.
- `android.permission.ACCESS_ADSERVICES_AD_ID`, `android.permission.ACCESS_ADSERVICES_ATTRIBUTION`, `android.permission.ACCESS_ADSERVICES_TOPICS`: Integrated for compatibility with the Android Privacy Sandbox.
- `android.permission.WAKE_LOCK`: Utilized internally by Google Play Services for background ad lifecycle tasks.

### C. Sensitive Permissions (Zero Usage)
The app does **not** request, access, or use any sensitive device permissions, including:
- ❌ No Camera or Microphone access
- ❌ No Contacts, Calendar, or Accounts access
- ❌ No Exact or Fine GPS Location access
- ❌ No Storage, Photos, Media, or External Files access
- ❌ No SMS, Call Logs, or Phone State access

---

## 4. Offline Functionality & Data Control

- **100% Offline Capability:** All eight calculator modes (COMP, EQN, CMPLX, MAT/VEC, STAT, CALC, CONV, BASE-N) and reference libraries are fully operational without an internet connection. When offline, ad requests simply collapse and the calculator continues to work seamlessly.
- **Managing Your Advertising ID:** You have complete control over personalized advertising. You can reset or completely delete your Android Advertising ID at any time through your device settings:
  - **Android Settings > Google > Ads > Reset advertising ID** or **Delete advertising ID** (or **Settings > Security & Privacy > Privacy > Ads** depending on your Android OS version).

---

## 5. Children's Privacy (COPPA Compliance)

Scientific Calculator is intended for general audiences, students, engineers, and educators. We do not knowingly collect personal information from children under the age of 13.

---

## 6. Data Security & Encryption

- Any network communication performed by the Google Mobile Ads SDK is encrypted in transit using standard Transport Layer Security (HTTPS).
- Local calculator settings and history are confined within Android's sandboxed private storage.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect changes in legal requirements or app features. Any revisions will be published with an updated "Effective Date" at the top of this policy.

---

## 8. Contact Us

If you have any questions, feedback, or concerns regarding this Privacy Policy or your data privacy, please contact:
- **Developer:** Ayan Ali
- **Email:** ayankalwaniya7890@gmail.com
