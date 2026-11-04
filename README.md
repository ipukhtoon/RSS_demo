# Ronyal Super Store — Demo POS

This repository contains an independent, offline-first demo application. It does not include or import the production RSS application, production database, Firebase configuration, or customer data.

## Demo restrictions
- Products: 10
- Categories: 5
- Customers: 5
- Suppliers: 3
- Completed sales: 20
- Purchases: 5
- Expenses: 10
- Returns: 3
- Credit transactions: 5

The app includes an in-app demo badge, sample data, owner/cashier access, editable store name, local demo data, and print layouts branded with the configured store name.

## Build Android APK
The GitHub Actions workflow **Build Android Demo APK** installs dependencies, packages the web app with Capacitor, builds a debug APK, and uploads it as an artifact. Download the APK from the completed workflow run.

## Important limitation
This is an offline demo. Local-only limits deter ordinary use but cannot be made tamper-proof: clearing app data, reinstalling, modifying the APK, or reverse engineering can bypass client-side restrictions. Do not use real customer or business data in this demo.

## Demo access
- Owner PIN: `2468`
- Cashier PIN: `1357`

Change these before distributing if you prefer different demo credentials.
