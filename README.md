# Vibe Coding Hackathon Guide is Live! 🎉

# Group 9 Complete Assignment

**Group Members**

1.  Violet Engefu
2.  Moses Mutinda
3.  Jacob Mwambwa
4.  clement oladokun

A web-based Price Tracker application to help you record, visualize, and manage product prices from different suppliers over time.

---

## Features

- **Add New Price Entry:**  
  Enter product name, supplier, price, date, and quantity/unit using a simple form.

- **View & Manage Records:**  
  All entries are shown in a responsive table. You can edit or delete individual records.

  - **Edit:** Opens a modal to update entry details.
  - **Delete:** Opens a confirmation modal before removing an entry.

- **Filter Records:**  
  Filter price records by product name, supplier, or date range (including custom date ranges).

- **Price Trends Chart:**  
  Visualizes price changes over time for each product-supplier combination using Chart.js.

- **Export Data:**  
  Export all price records as a PDF file using jsPDF and jsPDF-AutoTable.

- **Theme Toggle:**  
  Switch between light and dark themes.

- **Help & Contact:**

  - **Help Modal:** Step-by-step instructions and usage tips.
  - **Contact Us Modal:** Demo contact form (no backend).

- **Responsive Design:**  
  Works well on both desktop and mobile devices.

---

## File Overview

- [index.html](index.html):  
  Main HTML file. Contains the UI layout, Bootstrap modals (for editing, confirming, help, and contact), and links to all scripts and styles.

- [style.css](style.css):  
  Custom styles for the app, including dark theme support and responsive adjustments.

- [script.js](script.js):  
  Handles all app logic:

  - Theme toggling
  - Data storage (localStorage)
  - Table and chart rendering
  - Filtering, editing, deleting, and exporting data
  - Modal management and alert messages

- [README.md](README.md):  
  Project documentation (this file).

---

## How to Use

1. **Open `index.html` in your browser.**
2. **Add a new price entry** using the form on the left.
3. **View, filter, edit, or delete** records in the table.
4. **See price trends** in the chart above the table.
5. **Export your data** as a PDF using the Export button.
6. **Switch themes** using the moon/sun button in the header.
7. **Get help or contact** via the Help and Contact Us modals.

---

## Technologies Used

- [Bootstrap 5](https://getbootstrap.com/) for layout and components
- [Chart.js](https://www.chartjs.org/) for data visualization
- [jsPDF](https://github.com/parallax/jsPDF) and [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) for PDF export
- [Font Awesome](https://fontawesome.com/) for icons
- Custom CSS and JavaScript

---

## Pitch Deck

[View the Pitch Deck](https://www.canva.com/design/DAGoX8gtMO4/1LJd3IiYm7l9b92Trjry_w/edit?utm_content=DAGoX8gtMO4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

**Note:**  
All data is stored in your browser’s localStorage. No backend or server
