# BMS

**Business management that keeps working when the internet doesn't.**

BMS is a complete point-of-sale and back-office app for small distributors,
shops, bakeries, cafés and trading businesses. It runs on Android and Windows,
keeps every record on the device, and updates itself from this page.

No account. No cloud subscription. No always-on connection.

## Download

The latest release is **BMS 1.5.1**.

| Platform | Download | Notes |
|---|---|---|
| Android | [BMS-Mobile-v1.5.1.apk](https://github.com/Lalla-Challa/BMS-Releases/releases/latest/download/BMS-Mobile-v1.5.1.apk) | Android 7.0 or newer · 81 MB |
| Windows 10/11 x64 | [BMS-Desktop_1.5.1_x64-setup.exe](https://github.com/Lalla-Challa/BMS-Releases/releases/latest/download/BMS-Desktop_1.5.1_x64-setup.exe) | Recommended installer · 3 MB |
| Windows 10/11 x64 | [BMS-Desktop_1.5.1_x64_en-US.msi](https://github.com/Lalla-Challa/BMS-Releases/releases/latest/download/BMS-Desktop_1.5.1_x64_en-US.msi) | For managed or scripted installs · 4 MB |

Other versions are available under [Releases](https://github.com/Lalla-Challa/BMS-Releases/releases).
Every asset has a published SHA-256 checksum in
[CHECKSUMS-1.5.1.txt](https://github.com/Lalla-Challa/BMS-Releases/releases/latest/download/CHECKSUMS-1.5.1.txt).

**Android:** download the APK, allow installation from this source when Android
asks, then open the file. **Windows:** run the installer and launch BMS Desktop.
Both start with a short setup so you can enter your business details.

## What BMS does

### Sell from the counter or online

Charge walk-in customers or bill named accounts, apply line and invoice
discounts, add tax, take part-payments, and print or share an invoice. Online
orders can be recorded with their platform, reference, shipping status and
tracking note. Sell by piece, box, bottle, kilogram or any pack you define, while
stock stays accurate in the unit you buy it in.

### Keep stock honest

Record purchases from suppliers and receive them in full or in part. Each lot is
tracked with its own cost, and sales consume the oldest stock first, so the cost
you see is the cost you actually paid. Low-stock alerts, stock adjustments and a
full movement history keep the count explainable. Barcode scanning speeds up
item lookup at the counter and in the stockroom.

### Know the real profit

Every sale stores its cost at the moment it happened, not a number that changes
later. Operating expenses and salary payments are recorded separately, so the
profit-and-loss report shows revenue, cost of goods, overheads and net profit for
any date range. Businesses that make their own products can define recipes with a
batch yield, and BMS will cost each sale from the ingredients it consumed.

### Give credit without guesswork

Set credit limits and payment terms per customer, watch balances and ageing, and
record recoveries as they come in. The same ledger keeps receivables,
payables and cash consistent, so reports always reconcile.

### Deliver on time

Plan delivery routes, order the stops, mark them delivered or failed, and open
the whole run in Google Maps for turn-by-turn navigation. Recurring routes can be
scheduled forward in one step.

### Run the back office

Manage suppliers, expenses, employees, attendance and salary payments alongside
the shop floor. Export a workbook with the business's records for your accountant,
or take an encrypted backup and restore it on another device.

## Your data stays yours

BMS is local-first: the database lives on your phone or PC and is not uploaded
anywhere. There is no telemetry, no advertising identifier and no remote account.

- **Encrypted backups.** A `.bmsbackup` file is protected with AES-256 encryption
  using a passphrase you choose. The backup can be restored on either platform.
- **App Lock.** Optionally require the device's biometrics, PIN or password before
  the app opens.
- **Excel exports are not encrypted.** Share them carefully; the app warns you
  before saving one.
- **Device protection still matters.** The working database is protected by the
  operating system's app sandbox, not by a second password. Keep your device
  lock and disk encryption on.

## One business, two screens

BMS Mobile and BMS Desktop are two front ends for the same business model. Take
the tablet to the counter, keep the PC in the office, and move the business
between them with an encrypted backup. Both apps understand the same file, the
same ledger and the same reports.

## Updates that come to you

BMS checks for a newer release at start-up and from **Settings → About**. On
Windows the update is verified with a cryptographic signature before it installs.
On Android, the download is handed to the system installer, which verifies the
app's signing identity. You always see what is being installed and can decline.

## Under the hood

Curious how it is built? Read [ARCHITECTURE.md](ARCHITECTURE.md) for a plain-language
tour of the offline core, the two clients, the accounting engine and the update
channel.

## Support and security

- Questions and bug reports: [open an issue](https://github.com/Lalla-Challa/BMS-Releases/issues).
- Security problems: please use the repository's private security advisory instead
  of a public issue.
- Source code is maintained privately. This repository publishes installers,
  checksums and update manifests only.

BMS is proprietary software published for its users. No open-source licence is
granted by downloading these binaries.
