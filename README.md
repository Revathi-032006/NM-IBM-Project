# NM-IBM-Project
🛍️ Product Catalog with Filter

📖 Project Overview

This project is a Product Catalog System built entirely using JavaScript (JS).
It allows users to browse, search, and filter products by category, brand, price range, and rating.
The system also supports sorting by name, price, and rating, with real-time updates simulated in the console.

This project is part of the NM Mini Project.


---

💡 Features

✅ Display a list of products with details (name, brand, category, price, rating).
✅ Filter products by:

Category

Brand

Price Range

Search Query


✅ Sort products by:

Name (A–Z)

Price (Low → High / High → Low)

Rating (High → Low)


✅ Reset filters to view all products again.
✅ Console-based simulation for demonstration.
✅ Modular JavaScript structure — easy to connect with a web interface later.


---

🧩 Technologies Used

Language: JavaScript (ES6)

Platform: Node.js / Browser Console

Tools: Visual Studio Code



---

🏗️ How It Works

1. The project starts with a list of predefined products (mobiles, laptops, cameras, etc.).


2. Filters are applied dynamically using JS functions.


3. Filter and sort results are displayed in the console.


4. The code is fully customizable — you can connect it with HTML forms or buttons.




---

⚙️ Main JavaScript Functions

Function Name	Purpose

applyFilters()	Applies all active filters and updates the displayed product list.
setCategory(cat)	Filters products based on the selected category.
setBrand(brand)	Filters products based on brand.
setPriceRange(min, max)	Sets a minimum and maximum price filter.
setSearch(query)	Searches products by name.
setSort(option)	Sorts by price, rating, or name.
resetFilters()	Resets all filters to default values.
displayProducts()	Displays the filtered product list in console.



---

💻 How to Run the Project

Option 1 — In Browser Console

1. Open your HTML page or create a new .html file.


2. Add this line before closing </body>:

<script src="productCatalog.js"></script>


3. Open the page in your browser.


4. Open Developer Tools → Console (Press F12).


5. See the filtered product list appear dynamically.



Option 2 — In VS Code / Node.js

1. Open the folder in VS Code.


2. Run the script:

node productCatalog.js


3. View all outputs in the terminal console.




---

📊 Example Simulation Output

=== PRODUCT CATALOG ===
Samsung Galaxy S23 | Samsung | Mobile | ₹74,999 | ⭐4.7
Apple iPhone 14 | Apple | Mobile | ₹79,999 | ⭐4.8
OnePlus 12 | OnePlus | Mobile | ₹59,999 | ⭐4.5

Total Products: 3


---

🧠 Learning Outcomes

Understanding data filtering and sorting logic in JavaScript

Structuring reusable and modular code

Implementing product catalog systems for e-commerce

Building logic that can be easily integrated with HTML/CSS UI



---

👨‍💻 Author

Revathi
NM Mini Project — Product Catalog with Filter
Developed using JavaScript (200+ lines)
