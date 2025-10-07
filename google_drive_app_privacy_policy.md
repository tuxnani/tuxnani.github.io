# Privacy Policy for Google Drive Viewer

**Last Updated: October 7, 2025**

## Introduction

Google Drive Viewer ("the Application", "we", "our") is a desktop application that allows users to view and export their Google Drive file information. This Privacy Policy explains how the Application accesses, uses, and protects your information.

## Information We Access

### Google Drive Data
The Application accesses the following information from your Google Drive account:
- File names
- File sizes
- Last modified dates
- File MIME types (file format information)

### What We DO NOT Access
- **File contents**: We do not read, download, or access the actual contents of your files
- **Sharing permissions**: We do not access information about who your files are shared with
- **Personal information**: We do not collect your name, email address, or other personal details
- **Location data**: We do not track your physical location
- **Usage analytics**: We do not track how you use the Application

## How We Use Your Information

The Application uses your Google Drive metadata **exclusively** for the following purposes:

1. **Display**: To show your files in a list view within the Application interface
2. **Export**: To create Excel spreadsheets containing file information when you choose to export
3. **Local Operation**: All processing happens locally on your computer

## Data Storage and Security

### Local Storage Only
- All data retrieved from Google Drive is processed and stored **only on your local computer**
- No data is transmitted to external servers (except Google's servers during authentication and data retrieval)
- Authentication tokens are stored locally in a file called `token.pickle`

### Excel Exports
- Excel files are created and saved on your local computer only
- You have full control over where these files are saved and who can access them

## Data Sharing

**We do not share, sell, rent, or distribute your data to any third parties.**

The Application:
- Does not have backend servers
- Does not upload your data anywhere
- Does not include analytics or tracking tools
- Does not share information with advertisers or data brokers

## Third-Party Services

### Google APIs
The Application uses Google's official APIs to access your Google Drive data. When you sign in:
- You authenticate directly with Google's servers
- Google's Privacy Policy applies to this authentication process
- You can review Google's Privacy Policy at: https://policies.google.com/privacy

### OAuth 2.0 Authentication
- The Application uses OAuth 2.0 for secure authentication
- You explicitly grant permission for the Application to access your Drive metadata
- You can revoke this permission at any time through your Google Account settings

## Your Rights and Controls

### Access Control
- You control when the Application accesses your Google Drive
- You can sign out at any time using the "Sign Out" button
- Signing out deletes the local authentication token

### Revoke Access
You can revoke the Application's access to your Google Drive at any time by:
1. Going to your Google Account: https://myaccount.google.com/permissions
2. Finding "Google Drive Viewer" in the list of connected apps
3. Clicking "Remove Access"

### Data Deletion
To delete all data associated with the Application:
1. Delete the `token.pickle` file from the Application folder
2. Delete any exported Excel files you created
3. Revoke access through your Google Account (as described above)
4. Uninstall the Application

## Data Retention

- **Authentication tokens**: Stored locally until you sign out or delete the `token.pickle` file
- **File metadata**: Temporarily stored in memory while the Application is running; cleared when you close the Application
- **Exported files**: Stored on your computer until you manually delete them

## Children's Privacy

The Application does not knowingly collect information from children under 13 years of age. If you are under 13, please do not use this Application without parental supervision.

## Permissions Required

The Application requests the following Google API scope:
- `https://www.googleapis.com/auth/drive.metadata.readonly`

This permission allows **read-only access to metadata only** (file names, sizes, and dates). It does **not** allow:
- Reading file contents
- Modifying or deleting files
- Creating new files
- Sharing files

## Security Measures

We implement the following security practices:
- Use of official Google API libraries
- OAuth 2.0 authentication protocol
- Local-only data processing
- No network transmission of file data
- Secure credential storage using Google's recommended practices

## Open Source Transparency

The Application's source code is available for inspection, allowing you to verify:
- What data is accessed
- How data is processed
- Where data is stored
- That no unauthorized data collection occurs

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do:
- The "Last Updated" date at the top will be revised
- Significant changes will be communicated through the Application or documentation
- Continued use of the Application after changes constitutes acceptance of the updated policy

## Limitations of Liability

The Application is provided "as is" without warranties. We are not responsible for:
- Data loss or corruption
- Unauthorized access to your local computer
- Issues arising from Google API changes
- Misuse of exported data

## Compliance

### GDPR (General Data Protection Regulation)
For users in the European Union:
- You have the right to access, correct, and delete your data
- All data processing happens locally on your device
- No data is transferred outside your control

### CCPA (California Consumer Privacy Act)
For users in California:
- We do not sell your personal information
- You have the right to know what data is accessed
- You can request deletion of locally stored data at any time

## Contact Information

If you have questions or concerns about this Privacy Policy or the Application's data practices, please note:

- This is an open-source/personal project application
- For technical issues, refer to the documentation provided with the Application
- For Google Account security concerns, contact Google Support directly

## Your Consent

By using the Google Drive Viewer application, you consent to this Privacy Policy and agree to its terms.

## Acknowledgment

This Application uses Google APIs and is subject to Google's terms of service and privacy policies in addition to this policy.

---

**Summary**: Google Drive Viewer is a privacy-focused, local-only application that accesses only file metadata (names, sizes, dates) from your Google Drive. No file contents are accessed, no data is sent to external servers, and all processing happens on your computer. You maintain full control over your data at all times.
