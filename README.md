# 🛒 Toko Online – PHP

A simple **online shop system** built with **PHP** and **MySQL**, providing product management, shopping cart, and transaction history for customers and staff. Designed for learning and small-scale e-commerce setups.

---

## 📦 Features

- 👥 **Users**:
  - Login & Logout
  - Browse available products
  - Add to cart, checkout, and view order history

- 🧑‍💼 **Staff**:
  - Manage products (add, update, delete)
  - View all transactions and customer history
  - Dashboard for sales overview

- 🛍️ **Shopping**:
  - Cart system with product quantity management
  - Purchase processing and stock updates

---

## 🧱 Tech Stack

| Layer      | Technology                |
|------------|---------------------------|
| Backend    | PHP 7/8 (Procedural)      |
| Database   | MySQL                     |
| Frontend   | HTML, CSS                 |
| Assets     | Product images in ASSETS and tb folders |

---

## 📁 Project Structure

```yaml
toko_online-master/
├── ASSETS/                # Images & other assets
│   ├── foto/
│   ├── foto_produk/
│   └── RANDOM/
├── tb/                    # Sample product images (.jpg)
├── beli_produk.php        # Purchase processing
├── checkout.php           # Checkout page
├── dashboard.php          # Staff/admin dashboard
├── history_pembelianpelanggan.php
├── history_pembelianpetugas.php
├── home_tokopelanggan.php # Customer home page
├── home_tokopetugas.php   # Staff home page
├── keranjang.php          # Shopping cart page
├── koneksitoko.php        # Database connection
├── login_toko.php         # Login page
├── logout.php             # Logout handler
├── produk_pelanggan.php   # Product list for customers
├── produk_petugas.php     # Product list for staff
├── proses_*               # CRUD processing scripts
├── signup_petugas.php     # Staff registration
├── tambah_petugas.php     # Add staff
├── tambah_produk.php      # Add products
├── ubah_produk.php        # Edit products
└── toko_online (2).sql    # Database structure & sample data
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Felix-ryn/toko_online.git
```

### 2. Set Up Environment
- Extract `toko_online-master` into your server directory (e.g., `htdocs` for XAMPP).
- Start Apache and MySQL services.

### 3. Import the Database
- Open phpMyAdmin.
- Create a new database (e.g., `toko_online`).
- Import the included `toko_online (2).sql` file.

### 4. Configure Database Connection
- Edit `koneksitoko.php` to match your MySQL credentials.

### 5. Run the Application
- Visit: `http://localhost/toko_online-master/login_toko.php`

---

## 🗄️ Database Overview

- **Users (Staff & Customers)**
- **Products**: ID, name, price, stock, image
- **Transactions**: purchase records linked to users
- **Cart Items**: temporary purchase data before checkout

---

## 📜 License

MIT License  
Copyright (c) 2025 Felix Ryan Agusta

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in  
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN  
THE SOFTWARE.

---

## 👨‍💻 Author

**Felix Ryan Agusta**  
GitHub: [@Felix-ryn](https://github.com/Felix-ryn)

> “Building simple e-commerce solutions with PHP and MySQL.” 🛒
