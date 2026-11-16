# M-oRDONEZ
Tindahan POS  A lightweight, offline-ready point of sale for small shops, built as a single web page with no backend, no database server and no account required. It runs in any modern browser and can be installed on Android like an app.
Features
Fast selling: tap items to build a sale, search by name, and filter by category.
Cash payments: enter the cash received and the change is calculated instantly.
Tax support: set a tax rate (12% by default) and choose whether prices include tax or tax is added on top. The subtotal and tax appear on every receipt.
SMS receipts: enter the customer’s mobile number and send the receipt through the phone’s own Messages app, with the text already filled in.
Downloadable receipts: save any receipt as a clean HTML file that opens offline and can be printed.
Item management: add, edit and delete products, including names, prices and categories.
Sales reports: view totals, receipt counts and average sale by day, week, month or year, with bar charts and a best-sellers list for each period.
Works offline: a service worker caches the app after the first visit.
Light and dark mode that follow the device settings.
How it works

All data, including products, tax settings and sales history, is stored in the browser’s localStorage on the device. Nothing is sent to a server. The project is plain HTML, CSS and JavaScript in one file, plus a web manifest and a service worker for installation.

Getting started
Download or clone this repository.
Host the files with any static host such as GitHub Pages, or serve them locally with python -m http.server.
Open the address in Chrome on Android and choose Add to Home screen.
Limitations
Data stays on one device. Clearing the browser’s data erases it.
SMS opens the device’s messaging app and needs one tap to send. Automatic sending requires a separate backend and an SMS gateway provider.
Cash payments only.
Roadmap
Backup and restore of sales data
Tax-exempt items
CSV export of sales
Automatic SMS through a gateway such as Semaphore or PhilSMS
