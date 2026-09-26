# Sari-Sort: A Micro-Inventory & Expiration Tracker for Sari-Sari Stores 

Sari-Sort is a simple, smart app concept designed to help neighborhood sari-sari store owners ditch traditional pen-and-paper logs. Instead of managing stock by memory or writing down sales in a beat-up notebook, this app makes it easy for owners to keep track of their items, get alerts before products expire, and automatically view their total revenue at the end of the day. ᕙ(`▽´)ᕗ

This repository holds my initial project structure and draft proposal for our First Quarter Computer Science requirements. 

*(Heads up: This is just the project planning and proposal phase, so the actual application code isn't fully built out yet!)*

## 🌟 Core Features

* **📋 Check Stock & Alerts:** View your current shelf space in real-time. The system automatically warns you if you are running low (`⚠️ Running low!`) or if items are going to spoil soon (`⏰ Expiring soon!`).
* **➕ Quick Product Adding:** Easily stock new inventory by typing in the item's name, category, prices, stock count, and expiration date.
* **🛒 Sell Items on the Fly:** Log retail purchases immediately. The app drops the product stock count automatically and calculates the transaction total for you.
* **💰 See Today's Profit:** Skip the manual coin-counting and math at closing time. Get a fast summary of the total cash earned during the day. `(💵_💵)`

## ⚙️ Behind the Scenes (How It Works)

The logic operates on a continuous menu loop to keep things quick and simple for the owner:
1. **Startup:** The application boots up, sets a low-stock alert limit (default is 5 units), and displays the primary control menu.
2. **Daily Tasks:** The user chooses to inspect current inventory alerts, restock shelves, record a quick sale, or view the financial summary.
3. **Live Calculation:** Product array listings and total revenue variables are instantly updated behind the scenes depending on user input actions.

*Take a look inside the formal proposal PDF to see the exact structured pseudocode!* ＼(￣▽￣)／
