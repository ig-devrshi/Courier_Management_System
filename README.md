# 📦 Courier Management System

A simple and efficient **Courier Management System** built using **HTML**, **CSS**, **JavaScript**, and **PHP**, running on a **XAMPP server**. This project allows admin and users to manage and track couriers easily.

---

## 🚀 Features

- User Registration and Login
- Admin Dashboard
- Add / Update / Delete Courier Details
- Track Courier Status by ID
- View All Couriers
- Status Updates (In Transit, Delivered, etc.)
- Responsive UI Design

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL (via phpMyAdmin)  
- **Server:** Apache (XAMPP)

---

## 🗂️ Project Structure

```
Courier-Management-System/
├── index.html
├── login.php
├── register.php
├── dashboard.php
├── add_courier.php
├── update_courier.php
├── track_courier.php
├── delete_courier.php
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
├── db/
│   └── connection.php
└── README.md
```

---

## ⚙️ Installation and Setup

1. **Download or Clone this repository**
   ```bash
   git clone https://github.com/yourusername/courier-management-system.git
   ```

2. **Move the project folder to XAMPP's `htdocs`**
   ```
   C:/xampp/htdocs/courier-management-system/
   ```

3. **Start Apache and MySQL in XAMPP Control Panel**

4. **Import the Database**
   - Open your browser and go to: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a new database (e.g., `courier_db`)
   - Import the provided `.sql` file (if available)

5. **Configure Database Connection**
   - Open `db/connection.php`
   - Update database name, username, and password if needed:
     ```php
     $conn = mysqli_connect("localhost", "root", "", "courier_db");
     ```

6. **Run the project**
   - Go to: [http://localhost/courier-management-system](http://localhost/courier-management-system)

---

## 👤 Roles

- **Admin:** Can add, update, delete courier data and manage status.
- **User:** Can register/login and track their courier by tracking ID.

---

## 📌 Future Enhancements

- Email/SMS notification on courier status update
- Role-based access (Staff, Delivery Agent, etc.)
- Enhanced dashboard with analytics
- Upload delivery proof images
- Integration with Google Maps API for tracking

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-source and free to use under the MIT License.

---

## ✍️ Author

**Aman Sahani**  
[Email: your-email@example.com]  
[GitHub: https://github.com/yourusername]

---

## 🌐 Demo

If hosted locally, access via:  
[http://localhost/courier-management-system](http://localhost/courier-management-system)