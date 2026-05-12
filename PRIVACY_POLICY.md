# Privacy Policy for KULT App

**Last Updated:** May 12, 2026

## 1. Overview

KULT App ("App") is committed to protecting your privacy and ensuring you have a positive experience on our platform. This Privacy Policy explains what personal data we collect, how we use it, and how we protect it.

---

## 2. User Data Collection

### 2.1 Data Directly Collected from Users

The following user data is collected through the App and stored locally on your device:

#### Customer Information:
- **Full Name** - Required for customer profile and documentation
- **Address** - Required for customer records
- **Email Address** - Required for communication and customer identification
- **Phone Number** - Required for contact purposes
- **Interior Designer Name** - Optional, for project attribution

#### Room & Board Configuration Data:
- **Room Names** - User-defined room identifiers
- **Board Specifications:**
  - Board names and sizes (2-18 module boards)
  - KULT range selection (KULT or KULT NXT)
  - Board color selections
  - Slot type selections (2 Switch Master, 2 Switch Slave, 4 Switch Slave, 20A Switch, 4 Switch, Light Dimmer, Fan Regulator, Blind Controllers, Accessories, Bell Push)
  - Driver selections (1-4 drivers per load)
  - Appliance type selections
  - Load type selections (Wattage, Ampere, Tonnage)
  - Load limit values
- **Remarks** - User-provided notes and specifications

#### Generated Documents:
- **PDF Files** - Complete specifications including all customer and configuration data listed above

### 2.2 Data Collection Method

All data is collected through:
- Text input fields for customer information
- Dropdown menus for selections
- User interactions with the application interface
- PDF generation from collected data

**Data Storage Location:** All data is stored locally on the user's device. The App does NOT store data on external servers unless explicitly shared by the user.

---

## 3. Third-Party Libraries and SDKs

The following libraries and SDKs are used in the App and may interact with data:

### 3.1 Libraries Used and Their Data Practices

| Library | Purpose | Data Transmitted | Transmission Details |
|---------|---------|------------------|---------------------|
| **pdf** v3.11.3 | PDF generation and document creation | None off-device | Operates entirely locally; generates PDFs from user data on the device |
| **path_provider** v2.1.5 | Device file system path management | None | Provides local file paths; no external communication |
| **share_plus** v12.0.0 | Native sharing functionality | User-controlled | Shares files/data only when user explicitly selects share option; destination determined by user's choice (email, messaging, cloud storage, etc.) |
| **syncfusion_flutter_pdfviewer** v29.1.38 | PDF viewing and document display | None | Displays PDFs locally; no external data transmission |
| **intl** v0.20.2 | Internationalization and date formatting | None | Provides localization services; operates locally |
| **animate_do** v4.2.0 | UI animations | None | Provides animation functionality; no data transmission |
| **flutter_toast_message_bar** v0.0.8 | User notifications | None | Displays local notifications; no external transmission |

### 3.2 Data NOT Transmitted to Third Parties by Libraries

**Important:** The libraries used in this App do NOT automatically transmit any user data to external servers, analytics platforms, or third parties. The only data transmission occurs when:

1. **User explicitly shares a PDF** through the native share dialog (user controls destination)
2. **User opens URLs** using url_launcher (if implemented)
3. **User navigates to webpages** (if implemented)

---

## 4. Server-to-Third-Party Data Transfer

### 4.1 Current Implementation

The KULT App currently has **NO backend server infrastructure** for data storage or transfer. All operations are performed locally on the user's device.

### 4.2 Firebase Status

While Firebase Cloud Firestore is available as an optional dependency (currently commented out in the codebase), it is **NOT actively used** in the current version of the App. If Firebase integration is added in future versions, users will be notified and this Privacy Policy will be updated.

### 4.3 Third-Party Data Transfers

**Data is NOT transferred to third parties** except when:
- User explicitly chooses to share a PDF document
- User selects a specific destination (email, messaging app, cloud storage, etc.)
- In these cases, the user's device's native sharing mechanism is used, and the user controls the recipient

---

## 5. WebView Data Collection

### 5.1 WebView Usage

The KULT App **does NOT currently use WebViews**. Users are not exposed to in-app web browsing that could collect additional data.

### 5.2 URL Navigation

If any URL navigation is implemented in future versions:
- Users will be navigated to external websites using the device's default web browser
- Standard browser privacy policies of those external websites will apply
- The App does NOT track or collect data from external websites

---

## 6. Data Security and Protection

### 6.1 Local Storage Security

- All user data is encrypted at rest on the user's device using standard iOS/Android encryption
- PDF files are stored in temporary directories and can be managed by the user
- No data is transmitted over the internet unless explicitly shared by the user

### 6.2 User Control

- Users have complete control over all data in the App
- Users can delete customer profiles and room configurations at any time
- Users can export data via PDF sharing to their chosen destination
- Deleting data from the App removes it from the device

### 6.3 Data Backup

- iOS: Data may be included in iCloud backups if iCloud backup is enabled on the user's device
- Android: Data may be included in Google Drive backups if enabled on the user's device
- Users can disable app-specific backups in their device settings

---

## 7. Data Retention

### 7.1 Retention Policy

- **Active Data:** User data remains stored as long as the App is installed and the user maintains the data
- **Deleted Data:** When users delete customer profiles or configurations, data is immediately removed from the App
- **App Uninstall:** All App data is automatically removed when the App is uninstalled

### 7.2 Shared PDFs

- PDFs generated and shared by users are no longer under the App's control once shared
- Users are responsible for managing shared documents according to their own privacy requirements

---

## 8. User Rights and Choices

### 8.1 Data Access

Users can access all their data at any time by:
- Viewing customer information in the App
- Reviewing room and board configurations
- Generating and downloading PDF reports

### 8.2 Data Modification

Users can:
- Edit all customer information
- Modify room and board configurations
- Update load specifications and appliance selections

### 8.3 Data Deletion

Users can:
- Delete individual customer profiles
- Delete specific rooms or boards
- Delete the entire App and all associated data

### 8.4 Opt-Out Options

- Users can choose NOT to share PDFs or any data
- Users can disable app-specific iCloud/Google Drive backup in device settings
- Users can uninstall the App at any time

---

## 9. Age Restrictions

The KULT App is designed for professional and business use. The App is **not intended for users under 13 years of age**. We do not knowingly collect data from children under 13.

---

## 10. California Privacy Rights (CCPA)

If you are a California resident, you have the following rights under the California Consumer Privacy Act (CCPA):

1. **Right to Know:** You can request information about personal data collected
2. **Right to Delete:** You can request deletion of personal data
3. **Right to Opt-Out:** You can opt-out of data sales (none occur in this App)
4. **Right to Non-Discrimination:** You will not be discriminated against for exercising your rights

To exercise these rights, contact us at the email provided below.

---

## 11. European Privacy Rights (GDPR)

If you are an EU resident, you have the following rights under the General Data Protection Regulation (GDPR):

1. **Right of Access:** You can access your personal data at any time within the App
2. **Right of Rectification:** You can correct inaccurate personal data
3. **Right of Erasure:** You can request deletion of your data
4. **Right of Portability:** You can export your data as PDFs
5. **Right to Object:** You can object to data processing

To exercise these rights, contact us at the email provided below.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or for other operational, legal, or regulatory reasons. When we make material changes, we will:

- Update the "Last Updated" date at the top of this policy
- Notify users through the App or via email if changes significantly affect data collection practices

Continued use of the App after changes constitutes acceptance of the updated Privacy Policy.

---

## 13. Contact Us

If you have questions about this Privacy Policy or our privacy practices, please contact us:

**Company:** KULT (Kolors Unlimited Limited)  
**Email:** privacy@kultapp.com  
**Address:** [Company Address]  
**Phone:** [Company Phone Number]

---

## 14. Appendix: Data Flow Diagram

```
┌─────────────────────────────────────────────────────────────┐
│                    KULT App Data Flow                       │
└─────────────────────────────────────────────────────────────┘

User Input
   ↓
[Customer Information] → [Local Device Storage]
[Room Configuration]   → [Local Device Storage]
[Board Settings]       → [Local Device Storage]
   ↓
[PDF Generation] → [Temporary Storage]
   ↓
[User Sharing Decision]
   ├─→ [Share PDF] → [User's Selected Destination]
   │                  (Email, Drive, Messaging, etc.)
   │
   └─→ [No Share] → [Data Remains Local]

* No external servers
* No third-party data collection (unless user explicitly shares)
* All processing happens on-device
```

---

## 15. Summary of Key Points

✓ **All data is stored locally on your device**  
✓ **No automatic data transmission to servers or third parties**  
✓ **You control when and where data is shared**  
✓ **No analytics or tracking libraries used**  
✓ **No user behavior monitoring**  
✓ **Complete data deletion available**  
✓ **Industry-standard security practices**  

---

**By using the KULT App, you agree to this Privacy Policy.**

For app store compliance purposes, this Privacy Policy should be prominently displayed to users during app installation and available in the app's settings menu.
