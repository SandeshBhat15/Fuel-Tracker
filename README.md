Fuel Tracker PWA ⛽

A lightweight, offline-capable Progressive Web App (PWA) designed to track fuel expenses, mileage, and consumption for your vehicles. Built with React and Tailwind CSS in a single file for maximum portability.

🚀 Features

Mobile-First Design: Optimized for touch screens with a native app-like feel.

Multi-Vehicle Support: Track expenses for Cars (Petrol/Diesel) and 2 Wheelers.

Smart Statistics: Automatically calculates:

Average Mileage (km/L)

Cost per Kilometer

Total Monthly Spending

Total Fuel Consumed

Offline Storage: Data is saved instantly to your browser's Local Storage. No internet or login required.

Data Management:

Export to PDF: Generate professional reports with a single click.

Export to CSV: Download spreadsheets for Excel/Google Sheets.

Backup/Restore: Save your data to a JSON file to transfer between devices.

Privacy Focused: Your data never leaves your device.

📱 How to Install (Add to Home Screen)

You don't need an App Store to install this!

iOS (Safari)

Open the hosted link in Safari.

Tap the Share button (rectangle with arrow up).

Scroll down and tap "Add to Home Screen".

Tap Add.

Android (Chrome)

Open the hosted link in Chrome.

Tap the three dots menu (top right).

Tap "Add to Home Screen" or "Install App".

🛠️ How to Host for Free (GitHub Pages)

Fork this repository or create a new one.

Create a file named index.html and paste the code.

Go to Settings > Pages in your repository.

Under Build and deployment, select Source as Deploy from a branch.

Select Branch as main (or master) and folder / (root).

Click Save.

Wait ~1 minute, and your app will be live at https://<your-username>.github.io/<repo-name>/.

💻 Running Locally

Since this app is contained within a single file, you can run it without any server:

Download index.html.

Double-click it to open in your web browser.

🧰 Technologies Used

React 18: UI Library (via CDN).

Tailwind CSS: Styling (via CDN).

Babel: JSX compilation in the browser.

jsPDF & AutoTable: For generating PDF reports client-side.
