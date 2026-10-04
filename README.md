# Yaduwanshi Child Water — Version 9 Updated

GitHub-ready mobile-first PWA for **यदुवंशी चिल्ड वाटर**, Bordehi, Teh. Amla, Dist. Betul.

## New updates in this build

1. **Customer click → complete record**
   - Date-wise delivery history
   - Month-wise record
   - Monthly jars, returns, bill, payments and pending
   - All-time sales, payments and jar balance
   - Quick buttons for Delivery, Payment, Monthly Bill and Edit

2. **Daily Delivery**
   - Customer search by name/mobile/area
   - + / − jar control
   - Empty jar return
   - Rate × jar automatic amount
   - Payment mode
   - **Today Delivery** section separately shows customers already entered today
   - Edit/delete same-day entries

3. **Area-wise Customer**
   - Area/route list
   - Customer count by area
   - Area-wise jar balance and pending amount
   - Tap customer name to open full ledger

4. **Monthly customer account**
   - Monthly jar count
   - Monthly payment
   - Monthly bill
   - Current pending
   - Customer jar balance
   - Print / Save PDF
   - WhatsApp bill text

5. Existing Version 9 modules retained:
   - Dashboard
   - Customer add/edit/search
   - Payments: Cash, Online, UPI, Bank
   - Outstanding
   - Monthly bill
   - Driver/Staff
   - Jar stock
   - Reports
   - Backup/Restore
   - PWA/offline cache

## GitHub Pages

Upload all files to a GitHub repository. Then:
**Settings → Pages → Deploy from branch → main → / (root)**

Open the Pages URL in Android Chrome and use **Install app / Add to Home screen**.

## Cloud Sync — Mobile + Laptop

Version 9 now includes a **Firebase Firestore cloud-sync layer** in Settings.

### Setup
1. Create a Firebase project.
2. Create a Firestore Database.
3. Register a Web App and copy its Firebase config.
4. In Version 9 → Settings → Mobile + Laptop Cloud Sync, enter the config.
5. Use the same **Cloud ID / Business ID** on phone and laptop.
6. Use **Upload / Sync** after entries and **Download / Sync** on the other device.

**Important:** Firestore security rules/authentication should be configured before using this with real customer data. The app does not contain a private Firebase credential; you must enter your own project's web config.



This build uses browser localStorage for the working demo. It can run on phone and laptop, but **automatic cloud sync between different devices requires a cloud database/authentication layer**. Use Backup/Restore until cloud sync is configured.

