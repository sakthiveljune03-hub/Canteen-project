# 🍽️ DRS Quick Serve

DRS Quick Serve is a modern web-based smart canteen management and food ordering system developed for DMI College Canteen.  
The system digitizes the complete food ordering workflow, allowing students and staff to browse menu items, place orders, track food status in real time, and generate digital bills with scannable barcodes.

---

## 🚀 Features

- 🔐 User Authentication using Firebase
- 📋 Online Food Menu with Tamil Traditional Foods
- 🛒 Smart Cart Management
- 🎟️ Coupon Code Support
- 📡 Real-Time Order Tracking
- 👨‍💼 Admin Dashboard for Order Management
- 🧾 Digital Bill Generation
- 🔳 CODE-128 Barcode Generation using JsBarcode
- 📱 Fully Responsive Design
- ☁️ Firebase Realtime Database Integration

---

## 🏗️ System Architecture

The project follows a three-tier architecture:

1. **Client Layer**
   - HTML5
   - CSS3
   - JavaScript

2. **Backend Layer**
   - Firebase Authentication
   - Firebase Realtime Database

3. **Admin Layer**
   - Real-time order monitoring
   - Status updates
   - Menu management

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| HTML5 | Structure |
| CSS3 | Styling & Responsive Design |
| JavaScript (ES6+) | Application Logic |
| Firebase Authentication | User Login & Signup |
| Firebase Realtime Database | Real-Time Backend |
| JsBarcode | Barcode Generation |
| Google Fonts | Typography |

---

## 📂 Project Modules

### 1. Home Page
- Introduction to the system
- Menu preview
- Navigation to login page

### 2. Authentication Module
- User Signup
- User Login
- Firebase Authentication Integration

### 3. Menu Module
- 22 Tamil Traditional Food Items
- Category Filtering
- Add to Cart functionality

### 4. Cart & Checkout
- Quantity management
- Coupon discount support
- Order placement

### 5. Real-Time Order Tracker
Order stages:
- Placed
- Confirmed
- Preparing
- Ready
- Completed

### 6. Admin Dashboard
- View incoming orders
- Update order status
- Add new food items

### 7. Digital Bill Generation
- Barcode-enabled bill
- Order summary
- Printable invoice

---

## 🍛 Menu Categories

### Meals
- Full Meals
- Sambar Rice
- Curd Rice
- Lemon Rice
- Tamarind Rice
- Rasam Rice
- Idli
- Masala Dosa
- Veg Biryani

### Snacks
- Medhu Vadai
- Masala Vadai
- Pongal
- Bonda
- Bajji
- Murukku

### Juices & Drinks
- Nannari Sherbet
- Sugarcane Juice
- Tender Coconut
- Buttermilk
- Rose Milk
- Filter Coffee
- Masala Tea

---

## 🔥 Firebase Integration

### Firebase Services Used
- Firebase Authentication
- Firebase Realtime Database

### Database Structure

```json
users/
   userId/
      name
      email
      role

orders/
   orderCode/
      customerName
      items
      total
      status
