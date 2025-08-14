# Mum's Furniture Catalog & Order Tracker

A clean and cozy web-based tool for managing furniture orders, designed for simplicity and ease of use. The tool allows tracking orders, customers, and related financial details in a centralized, browser-friendly interface.

---

## Features

- **User Authentication**  
  Sign in or register to save your orders securely using Firebase Authentication.

- **Order Management**  
  - Add, edit, and delete orders in a dynamic table.  
  - Track item details including name, number, quantity, price, shipping, fees, returns, tax, and totals.  
  - Record important dates: order and shipment dates.  
  - Filter orders by customer, item name, item number, or tracking number.

- **CSV Import/Export**  
  - Import orders from a CSV file to quickly load existing data.  
  - Export the current order list to CSV for external use.

- **Automatic Calculations**  
  - Taxes automatically calculated per order (default 6% rate).  
  - Total and grand total values update dynamically with edits.

- **Local & Remote Storage**  
  - Orders are saved locally for offline access.  
  - Authenticated users can sync data to Firebase Firestore for persistence across devices.

- **Responsive Interface**  
  - Works on desktop and mobile browsers.  
  - Built using Tabulator for an interactive table experience.

- **WIP Overlay**  
  - Alerts users if the page is under construction, with a "Don't show again" option.

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Table Management:** [Tabulator](https://tabulator.info/)  
- **Backend & Storage:** Firebase (Firestore and Authentication)  
- **Hosting:** Any static web server (currently hosted at [https://mumstool.onthewifi.com](https://mumstool.onthewifi.com))

---

## Usage

1. Open the web tool in your browser.  
2. Register or sign in to start tracking orders.  
3. Add new orders using the **Add New Row** button.  
4. Edit fields directly in the table; totals and tax are calculated automatically.  
5. Filter orders using the search input to quickly find items or customers.  
6. Export or import CSV files as needed.  
7. Your data is saved locally and synced to Firebase when logged in.

---

## Security & Data Privacy

- **Authentication:** Users must sign in to save or load orders remotely.  
- **Data Rules:** Firebase Security Rules enforce user-specific access to prevent unauthorized reads/writes.  
- **Local Storage:** Cached locally for quick access but can be cleared at any time.

---

## Preview

![Preview](https://mumstool.onthewifi.com/imgs/MumsToolPreview.png)

---

## Notes

- Designed for personal or small business use.  
- Work in progress—some features may continue to evolve.