# CRUD

#  CRUD Product Management System

A lightweight, browser-based product management system built with **Vanilla JavaScript**, **HTML5**, and **CSS3**. Allows you to create, read, update, and delete products — with real-time price calculation and search functionality. All data is persisted in the browser using **localStorage**.

---

##  Features

-  **Create** products with name, price, taxes, ads, discount, count, and category
-  **Read** all products displayed in a dynamic table
-  **Update** any existing product inline
-  **Delete** a single product or all products at once
-  **Live total price** calculation (price + taxes + ads − discount)
-  **Search** by product title or category
-  **Persistent storage** via `localStorage` — data survives page refreshes
-  **Bulk add** — create multiple copies of the same product using the Count field

---

##  Project Structure

```
📁 project/
├── CRUD.html       # Main HTML structure and layout
├── project.js      # All JavaScript logic (CRUD + Search)
└── style.css       # Styling and responsive layout
```

---

##  Getting Started

No installation or build tools required.

1. Clone or download the project files
2. Open `CRUD.html` in any modern browser

```bash
git clone https://github.com/your-username/crud-product-manager.git
cd crud-product-manager
# Open CRUD.html in your browser
```

---

##  How It Works

## Creating a Product
Fill in the required fields (Name, Price, Category) and click **Create**. If Count > 1, the product is duplicated that many times.

## Price Calculation
The total is calculated in real-time as you type:

```
Total = (Price + Taxes + Ads) - Discount
```

## Updating a Product
Click the **Update** button on any row. The form fills with the product's data — edit and click **Update** to save.

## Searching
- Click **Search By Title** or **Search By Category** to switch search mode
- Type in the search box — results filter instantly

## Deleting
- Click **Delete** on a row to remove a single product
- Click **Delete All** to clear everything

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure and form elements |
| CSS3 | Styling, transitions, and layout |
| JavaScript (ES6) | Application logic and DOM manipulation |
| localStorage | Client-side data persistence |

---

# Limitations

- Data is stored in the browser only — not synced across devices
- No backend or database integration
- No user authentication

---

# Possible Improvements

- [ ] Add form validation with visual feedback
- [ ] Connect to a REST API / backend database
- [ ] Add sorting by column (price, name, etc.)
- [ ] Export data to CSV or Excel
- [ ] Add responsive mobile layout
- [ ] Pagination for large product lists

---

# Author

Built as a front-end JavaScript practice project.  
Feel free to fork, improve, and use it as a learning reference.

---

##  License

This project is open source and available under the [MIT License](LICENSE).
