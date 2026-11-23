<p align="center">
  <img src="https://raw.githubusercontent.com/jewelvault/.github/main/assets/logo.png" alt="JewelVault logo" width="120" />
</p>

<h1 align="center">JewelVault</h1>

<p align="center"><strong>Jewellery business management, built around the way jewellers work.</strong></p>

JewelVault is a connected set of tools for jewellery retailers and their teams. It brings day-to-day store operations together: jewellery inventory, GST billing, purchases, customer accounts, khata, audit, backups, reports, and hardware-assisted workflows. The product is designed for jewellery-specific details such as purity, fine weight, metal rates, old-metal exchange, HUID, and scannable item tags.

[Visit JewelVault](https://jewelvault.co.in/) · [Browse repositories](https://github.com/orgs/jewelvault/repositories)

## Who JewelVault is for

- Jewellery shop owners and managers
- Gold and silver retailers
- Diamond boutiques and showrooms
- Billing counter operators
- Inventory and audit staff
- Businesses managing more than one store
- Shops moving from notebooks, spreadsheets, or generic billing tools

## What you can do

### Jewellery inventory

- Organize stock by category and subcategory.
- Record item details, purity, gross/net/fine weight, quantity, HSN, HUID, and other attributes.
- Add, edit, find, filter, and scan items.
- Import item data from Excel with category mapping and confirmation.
- Track aggregate stock quantities and weights.
- Use current metal rates and purity-aware calculations where valuation is available.
- Generate QR/barcode-enabled tags and print labels from saved templates.

### Sales, GST invoices, and payments

- Prepare sales invoices using inventory items and customer details.
- Calculate fine weight and metal value using supported Gold and Silver rates and purity.
- Apply making charges, component charges, GST, discounts, card charges, payments, and round-off in the invoice flow.
- Add old-metal exchange by entered value or metal-rate calculation.
- Preview invoices, save completed sales, and generate invoice PDFs.
- Create draft invoices and draft PDFs.
- Customize invoice layouts with editable PDF templates, field bindings, page settings, and preview data.
- Keep sale, invoice, and payment activity available in the store ledger.

### Purchases and metal exchange

- Record purchase orders, sellers/firms, purchased items, and exchange metal.
- Review purchase and item details in the purchase ledger.
- Support stock changes and inventory totals through purchase and sale workflows.

### Customers, balances, and khata

- Create and look up customers by mobile number.
- Review customer profiles, transaction history, outstanding balances, and payments.
- Record regular payments and customer dues.
- Create and manage khata books, reusable khata plans, plan payments, and plan completion.
- View customer invoices, orders, and shared repair information through customer-facing flows where enabled.

### Audit, reports, and store operations

- Review audit-related activity and store reports where enabled for the account.
- Use dashboard summaries and date-range selection for a store snapshot.
- Manage store staff, users, and supported permissions.
- Review plan, subscription, feature access, and usage information.
- Manage devices, files, and available store data workflows from the Console.

### Backups, import, and restore

- Export and import supported store data through Excel workbooks.
- Back up to Google Drive or export locally.
- Restore from Drive or a local workbook, with merge and replace modes where supported.
- View backup and sync status, selected source, and restore details.
- Validate store and account binding information in Drive backup/restore flows.

### Printers, scanners, and templates

- Scan inventory QR/barcodes with the Android camera.
- Connect and manage supported Bluetooth devices and printers.
- Test printer output and use saved printers for invoice or label printing.
- Design label templates with configurable dimensions and item-field bindings.
- Design sell and draft invoice PDF templates with configurable page size, padding, data bindings, and preview.

## JewelVault apps

### Android app

The Android app is the mobile store workspace. It includes inventory, scanning, sales and draft invoices, purchases, customer and khata workflows, ledgers, audit, reports, staff management, subscriptions, backup/restore, PDF and label designers, and Bluetooth device management. Store data can use the app's local database and supported workbook/Drive and cloud-connected workflows.

[Open the Android app repository](https://github.com/jewelvault/JewelVaultMobile)

### Merchant Web Console

The Web Console gives merchants and support staff browser-based access to supported store operations, including dashboard, inventory, customer records, sales and purchase ledgers, repairs, reports, device and file management, subscription and usage views, and account settings. Availability depends on the signed-in role, plan, and configured data connections.

[Open the Web Console repository](https://github.com/jewelvault/jewelVaultConsole)

### Customer Portal

Customers can sign in with phone verification to view their JewelVault customer dashboard and supported shared records, including orders, invoices, and repairs. The portal also supports customer profile updates, notifications, and PDF document downloads for records the store has shared.

[Open the Customer Portal repository](https://github.com/jewelvault/JewelVaultCustomerPortal)

### Employee Portal

Employees have a separate sign-in and dashboard experience, with access controlled by their employee session and the store's configured permissions.

[Open the Employee Portal repository](https://github.com/jewelvault/JewelVaultEmployeePortal)

### Public product website

The public website introduces JewelVault and its capabilities. It includes product features, pricing, hardware and printing guidance, security and backup information, a jewellery price calculator, inventory information, setup guidance, demo/contact flows, and legal pages.

[Visit the public website](https://jewelvault.co.in/) · [Open its repository](https://github.com/jewelvault/JewelVaultPublicWebsite)

### Windows desktop app

The Windows desktop application provides a native shell for the Web Console, including desktop window and operating-system integration.

[Open the desktop app repository](https://github.com/jewelvault/JewelVaultDesktop) · [Get desktop releases](https://github.com/jewelvault/JewelVaultDownloads)

## Platform and data

JewelVault includes an Android application, React web applications, a Django API backend, and a Windows desktop shell for the Console. Depending on the feature and account setup, workflows use local app storage, Excel/Google Drive workbooks, Firebase services, and authenticated backend APIs. Sign-in, role and store scope, feature access, and plan limits control access to protected workflows.

Some capabilities vary by platform, account plan, permissions, and service configuration. Newer cloud workflows may still be in development; repository presence alone does not mean a feature is available to every user or deployed in production. Metal-rate billing currently supports Gold and Silver rate resolution in the described invoice flows.

## Repositories

- [Android Mobile](https://github.com/jewelvault/JewelVaultMobile)
- [Django Backend](https://github.com/jewelvault/JewelVaultBackend)
- [Merchant Web Console](https://github.com/jewelvault/jewelVaultConsole)
- [Customer Portal](https://github.com/jewelvault/JewelVaultCustomerPortal)
- [Employee Portal](https://github.com/jewelvault/JewelVaultEmployeePortal)
- [Public Website](https://github.com/jewelvault/JewelVaultPublicWebsite)
- [Windows Desktop app](https://github.com/jewelvault/JewelVaultDesktop)
- [Desktop downloads](https://github.com/jewelvault/JewelVaultDownloads)