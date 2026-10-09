# My Pigeon PH - Legal & Compliance Documents

Quick Links:
* [Terms of Service & Disclaimer Agreement](#terms-of-service)
* [Privacy Policy & RA 10173 Compliance](#privacy-policy)

---

<a name="terms-of-service"></a>
# TERMS OF SERVICE AND DISCLAIMER AGREEMENT

**Last Updated:** October 10, 2026

Please read this Terms of Service and Disclaimer Agreement ("Agreement") carefully before using **My Pigeon PH** ("Application" or "Service"). By creating an account, logging in, accepting our legal terms, or using the Application, you ("User" or "You") agree to be bound by this Agreement.

## 1. ACCEPTANCE OF TERMS, ACCOUNT REGISTRATION & SINGLE EMAIL POLICY
* **"AS-IS" & "AS-AVAILABLE" Provision:** The Application is provided on an "AS IS" and "AS AVAILABLE" basis without warranties of any kind, either express or implied, including but not limited to implied warranties of merchantability, fitness for a particular purpose, or non-infringement.
* **Scope of Service:** **My Pigeon PH** is designed as a digital administrative, high-capacity record-keeping, genetic lineage, and loft management platform built primarily to empower pigeon breeders, fanciers, and racing enthusiasts in the **Philippines**, while also welcoming and accommodating international fanciers and racing communities worldwide.
* **Cloud Account Registration & Single Email Policy:** To access the Application, basic account details (**Email Address, Display Name, User ID [UID], and Device ID**) are recorded in our secure cloud database (Google Firebase Firestore) alongside your legal consent state. To maintain account integrity and device license verification, each application installation is restricted to a **single registered email address**.
* **Account Switching & Deletion Requirement:** If you decide to switch to a different email address, you must first initiate a full account deletion for the currently registered email. You acknowledge that executing an account deletion permanently purges all local loft records, pigeon profiles, and financial logs from your device, and you are solely responsible for exporting local backups (`.mypigeon` files) prior to switching accounts.

## 2. SYSTEM REQUIREMENTS, DISPLAY ORIENTATION & ACCESS SECURITY
* **Mobile Smartphone Optimization & Portrait Mode Restriction:** **My Pigeon PH** is designed, optimized, and tested exclusively for **mobile smartphone devices running in Portrait Mode**. The Application is restricted to Portrait Mode to ensure the precision, visual rendering, and integrity of complex user interfaces, 6-generation pedigree trees, genetic matrices, and Digital Pigeon Picture Cards. Landscape orientation is explicitly disabled.
* **Tablet & Large-Screen Disclaimer:** The Application has not been tested or optimized for tablet devices, foldables, or large-screen displays. We do not warrant proper layout formatting, visual scaling, or error-free usability if the Application is installed on tablet devices or forced into non-standard aspect ratios/landscape view via third-party display overrides.
* **Device Security, PIN & Biometric Access:** You are solely responsible for maintaining the physical security of your smartphone, safeguarding any in-app local PIN configured within the Application, and controlling biometric access (fingerprint or facial recognition) enabled on your device. The developer is not liable for unauthorized access to your local loft records resulting from shared device usage, compromised device PINs, or additional biometrics enrolled on your physical hardware.
* **Android System Permissions & Alarms:** Scheduled alarms, dual daily feeding alerts, egg cycle notifications, and custom audio reminders rely on system permissions (`SCHEDULE_EXACT_ALARM`). Operating system battery optimization features, device restarts, or manufacturer background process killing may affect background alert execution.

## 3. SMART APP LOGIC, CONTEXT SHORTCUTS & AUTOMATED WORKFLOWS
* **Context Menu Shortcuts & Gesture Execution:** The Application incorporates gesture shortcuts (such as double-tapping the 🏠 My Lofts icon for quick section navigation or long-pressing a pigeon tile to trigger Context Menu options including Edit Pigeon, Log Medical Health, Log Race Result, OLR Enrollment, View Pedigree Tree, View Picture Card, or Delete Pigeon). Actions performed through these shortcuts are executed immediately on your local device database. You are responsible for verifying actions prior to triggering deletion gestures.
* **Automated Status & Inventory Rules:** The Application utilizes automated status rules to streamline loft management (e.g., automatically re-listing a bird in your active roster when an OLR Buyback status is triggered, or calculating real-time headcount breakdowns by cocks and hens).
* **Automated Sales & Financial Ledger Integration:** Updating a bird's status to "Sold" automatically prompts the system to log a direct sales credit entry into your Loft Financial & Expense Tracker, with an option to record buyer details. These automated workflows are administrative convenience tools, and you remain responsible for manually auditing your financial statements and bird inventory.

## 4. PEDIGREE, GENETIC COI & MISREPRESENTATION DISCLAIMER
* **User-Generated Records & Digital Cards:** All data entered into the database—including bird profiles, ring numbers, batch loft assignments, CSV imported entries, 6-Generation PDF Pedigrees, and QR Digital Pigeon Cards—is user-generated.
* **Automated QR Data Capturing:** Sharing Digital Pigeon Cards with app-exclusive QR codes allows other users to automatically capture bird data. The developer does not verify, authenticate, or legally certify the accuracy, genetic legitimacy, performance records, or ownership of any pigeon logged, calculated (e.g., Coefficient of Inbreeding / COI analysis), or transferred via QR codes or exported files.
* **Third-Party Sales & OLR Disputes:** If you use exported PDF pedigrees, digital cards, or financial reports to sell, trade, auction, or register pigeons with local clubs or One Loft Races (OLR), you are solely responsible for the accuracy of that data. You agree to hold the developer harmless against any third-party claims, buyer disputes, or allegations of fraud or misrepresentation.

## 5. VETERINARY, HEALTH TRACKER & EGG CYCLE DISCLAIMER
* **Record-Keeping Only:** The Health & Medication Tracker, treatment/vaccination logs, egg cycle trackers, and 6-month breeding analytics are administrative tools designed strictly for personal loft management.
* **No Professional Veterinary Advice:** The Application does not provide biological, medical, or diagnostic advice. Features, alerts, or logs do not replace consultation with a licensed veterinarian.
* **Assumption of Risk:** You assume full responsibility for any medication, vaccination, egg foster transfer, or treatment administered to your birds. The developer accepts no liability for bird mortality, disease outbreak, reduced racing performance, egg spoilage, infertility, or injury resulting directly or indirectly from reliance on the Application or automated incubation alarms.

## 6. LOFT FINANCIAL REPORTS & RACE LOGS DISCLAIMER
* **Informal Ledger Tracking:** The Loft Financial & Expense Tracker, debit/credit ledgers, and downloadable Fancier’s Monthly Records are provided for informal tracking purposes only. The Application is not a certified tax, accounting, or auditing software.
* **Club & OLR Race Tracking:** Club and One Loft Race (OLR) performance logs are manual user entries. The developer is not responsible for ledger miscalculations, accounting discrepancies, or monetary disputes arising from local races, club pools, or commercial breeding transactions.

## 7. DATA PORTABILITY, AES-256 BACKUPS & DATA LOSS
* **Offline-First Storage:** All loft records, pedigree trees, bird photos, financial ledgers, and race entries are stored **exclusively on your local device (Room/SQLite)** and are **never** backed up to our cloud servers.
* **User Backup Responsibility:** You are solely responsible for regularly exporting and safeguarding your local database using the app's encrypted Full Virtual Loft Local Backup feature (`.mypigeon` files via AES-256 GCM) or CSV exports.
* **Password Security:** Local backup exports are encrypted using a user-specified password. The developer cannot decrypt, recover, or reset passwords for lost backup files.
* **Account Wiping Rules:** Logging out, switching users, or performing an account deletion purges user-isolated database tables and resets local encryption states. The developer is not liable for data loss resulting from hardware failure, OS upgrades, device resets, or user-initiated account clearing.

## 8. LIMITATION OF LIABILITY
To the maximum extent permitted by applicable law:
* Under no circumstances shall the developer, owner, or affiliates be liable for any direct, indirect, incidental, consequential, special, or punitive damages (including, without limitation, loss of bird stock, lost tournament/OLR earnings, device failure, or loss of data) arising out of the use of or inability to use this Application.
* In any event, the developer's total cumulative liability under this Agreement shall be limited to the total amount paid by You (if any) to purchase or download the Application.

## 9. INDEMNIFICATION
You agree to defend, indemnify, and hold harmless the developer, owner, and representatives from and against any claims, liabilities, losses, damages, or legal costs arising from:
1. Your violation of any section of this Agreement.
2. Any false, misleading, or unverified pedigree or sales data generated by your account.
3. Any dispute between you, a buyer, a third party, or a racing club/OLR organizer involving records produced by the Application.

## 10. GOVERNING LAW AND JURISDICTION
This Agreement shall be governed by and construed in accordance with the laws of the **Republic of the Philippines**, including the Philippine Civil Code and Republic Act No. 10173 (Data Privacy Act of 2012), without regard to conflict of law principles. Any legal action arising from this Agreement shall be brought exclusively before the competent courts of the Philippines.

## 11. ACKNOWLEDGMENT AND CONSENT
By creating an account, clicking "I Agree", installing, or continuing to use **My Pigeon PH**, you acknowledge that you have read, understood, and agreed to be bound by every section of this Terms of Service and Disclaimer Agreement.

---

<a name="privacy-policy"></a>
# PRIVACY POLICY & RA 10173 COMPLIANCE FOR MY PIGEON PH

**Last Updated:** October 10, 2026

**My Pigeon PH** ("we," "our," or "us") respects your privacy and is committed to protecting your personal data in compliance with Republic Act No. 10173, also known as the **Philippine Data Privacy Act of 2012 (RA 10173)**, its Implementing Rules and Regulations, and National Privacy Commission (NPC) issuances.

### 1. INFORMATION WE COLLECT AND PROCESS
We handle three distinct categories of data: **Cloud Account Details**, **Local Loft Records**, and **Device Security Credentials**.

#### A. Cloud Account Details (Stored Online)
When you create an account, log in, or accept our legal terms, we collect and store the following basic account details in our secure cloud database (Google Firebase Firestore):
* **Display Name**
* **Email Address** (Restricted to a single active email per installation)
* **User ID (UID)**
* **Device ID** (used to verify your device license)
* **Legal Consent Logs** (timestamps verifying your acceptance of our Terms of Service, Privacy Policy, and RA 10173 notice)

#### B. Local Loft Records (Stored Only on Your Phone)
**My Pigeon PH** is designed as an **offline-first application** equipped to manage databases of 1,000+ pigeon entries locally. All your day-to-day loft features and data are processed and stored exclusively on your device's internal database (Room/SQLite):
* **Pigeon Registrations & Pedigrees:** Ring numbers, strain, color, gender, ancestral lineages (up to 6-generation PDF pedigrees), batch loft assignments, and pigeon photos.
* **Real-Time Loft Inventory:** Automated headcount tracking, default/custom loft configurations, and status indicators.
* **Breeding, Foster & Genetic Logs:** Pairings, nest box assignments, 18-day hatching trackers, foster parent transfers, and Coefficient of Inbreeding (COI) calculations.
* **Race & Activity Tracking:** Local club race performance, One Loft Race (OLR) entries, and activity logs.
* **Health & Medication Records:** Treatments, vaccination schedules, and recovery logs.
* **Loft Financial Ledgers:** Income, entry fees, upkeep expenses, direct sales credit entries (with optional buyer names), and Fancier's Monthly Records.
* **Custom Alarms & Audio Library:** Feeding reminders, egg alerts, and custom/built-in audio files stored locally.

> **IMPORTANT:** Your pigeon entries, pedigrees, race logs, photos, and loft financial records are **100% private to you**. They are **never** uploaded, synced, or backed up to our cloud servers.

#### C. Local Biometric & PIN Security Credentials
* **Local Biometric Authentication:** If you enable Biometric Login (fingerprint or face unlock), authentication is processed entirely by your device’s Android operating system via standard device security hardware (`BiometricPrompt`). **My Pigeon PH** does not access, collect, transmit, or store your biometric data, fingerprint templates, or facial scans on any local database or cloud server.
* **In-App PIN:** If you configure an optional PIN code, it is stored securely on your local device to prevent unauthorized physical access to your loft records.

### 2. HOW YOUR DATA IS STORED AND ENCRYPTED
* **On-Device Storage:** Your loft information is saved inside an isolated, secure database sandbox on your phone.
* **Encrypted Backups:** When you export a Full Virtual Loft Local Backup (`.mypigeon` file) to your phone's storage, the file is fully encrypted using password-protected **AES-256 GCM encryption**. Without your chosen password, no unauthorized person or app can read your backup file.
* **Cloud Security:** Your basic account details (Email, Display Name, UID, Device ID, and consent timestamps) are safely stored in Google Firestore with strict database security rules.

### 3. DATA SHARING
We **do not sell, rent, trade, or share** your account details, device information, or loft records with third-party advertisers, data brokers, or marketing networks. Cloud infrastructure services (Google Firebase) are used strictly for user authentication, license validation, and legal recordkeeping.

### 4. DATA RETENTION, SINGLE EMAIL POLICY & YOUR RIGHT TO ERASURE
Under the Philippine Data Privacy Act of 2012 (RA 10173), you retain full control over your data:
* **Single Email & Account Switching Policy:** Our system enforces a single-active-email registration policy per account installation. To transition your app setup to a new email address, you must execute an account deletion for the existing registered email.
* **In-App Local Data Wipe & Account Deletion:** Initiating an account deletion, logging out, or switching accounts automatically triggers an instant, complete local database wipe. This purges all pigeon records, photos, local settings, and PIN configurations from your device while removing your cloud account entry from our servers.
* **System Clearing:** Clearing app data/cache or uninstalling the app from your Android system settings removes all local databases. You can restore your data using a previously saved `.mypigeon` backup file.

### 5. YOUR RIGHTS AS A DATA SUBJECT (RA 10173)
Under RA 10173, you have the following rights:
1. **Right to Be Informed:** You have the right to know how your personal and loft data is collected, processed, and stored.
2. **Right to Access & Data Portability:** You can export your pigeon cards, PDF pedigrees, monthly loft financial records, CSV files, and encrypted `.mypigeon` backups at any time.
3. **Right to Rectification:** You can update or edit your account info, bird records, and loft details directly within the app.
4. **Right to Erasure or Blocking:** You have the right to wipe your local device records or delete your cloud account profile.
5. **Right to Lodge a Complaint:** You may raise questions or file a complaint with the **National Privacy Commission (NPC)** of the Philippines if you believe your data privacy rights have been violated.

### 6. APP PERMISSIONS REQUESTED
The app requests minimal Android system permissions:
* **INTERNET / ACCESS_NETWORK_STATE:** Required strictly to authenticate your account login, verify your device license, and save legal consent logs to Firestore.
* **SCHEDULE_EXACT_ALARM / POST_NOTIFICATIONS:** Required to sound exact daily feeding alarms, egg hatching reminders, and custom audio alerts on your device.
* **USE_BIOMETRIC / USE_FINGERPRINT:** Required strictly to invoke system-level `BiometricPrompt` authentication if enabled by the user.

### 7. UPDATES TO THIS PRIVACY POLICY
We may update this Privacy Policy from time to time to reflect app improvements, new features, or regulatory updates. Any changes will be posted with an updated "Last Updated" date.

### 8. CONTACT US & DATA PROTECTION OFFICER
If you have any questions, feedback, or requests regarding this Privacy Policy or wish to exercise your privacy rights under RA 10173, please contact us:

* **App Name:** My Pigeon PH
* **Developer Support Email:** `mypigeonph@gmail.com`
* **Official Legal Page:** `https://mypigeonph.github.io/legal/`
