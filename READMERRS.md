# 🚆 Railway Reservation System

A complete **Railway Reservation System** developed using **Python** and **MySQL**, providing a simple CLI-based interface for managing train bookings. It allows users to **search for trains, book tickets, cancel bookings**, and view details through a terminal interface connected to a MySQL database.

---

## 📌 Features

- Add new trains to the system
- View all available trains
- Search for specific trains
- Book tickets
- Cancel tickets
- View passenger details
- Admin and user interfaces
- Fully integrated with MySQL (no CSV file dependency)

---

## 💻 Technologies Used

### 🔧 Backend
- **Python** – Core programming language
- **MySQL** – Relational database to store train and booking data
- **mysql-connector-python** – For connecting Python with MySQL
- **datetime** – Used for managing booking and journey dates
- **os** – Used for terminal screen clearing and formatting

### 🖥️ Frontend
- **Command Line Interface (CLI)** – Simple text-based UI built using Python's `print`, `input`, and formatting logic

> Note: This project currently uses a **terminal-based frontend** (CLI). GUI or Web-based frontend is not included but can be implemented using **Tkinter**, **Flask**, or **React** in future enhancements.

---

## 📂 Project Structure

```bash
railway-reservation-system/
│
├── railway.py                 # Main executable script
├── db_config.sql              # SQL schema and table creation queries
├── README.md                  # Project documentation (this file)
└── requirements.txt           # Python dependencies
```

---

## 🧪 Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/Safwan02ck/railway-reservation-system.git
cd railway-reservation-system
```

### 2. Install Python dependencies
```bash
pip install -r requirements.txt
```

### 3. Set up MySQL Database
- Create a MySQL database (e.g., `railway`)
- Import the schema using the provided SQL file:
```bash
mysql -u root -p railway < db_config.sql
```
- Ensure your MySQL user, password, host, and database match the values in `railway.py`.

### 4. Run the Project
```bash
python railway.py
```

---

## 🔐 Admin Credentials

> Note: These are hardcoded in the script and can be updated.

- **Username:** `admin`
- **Password:** `admin123`

---

## ✍️ Author

- **Safwan** – [GitHub Profile](https://github.com/Safwan02ck)

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✅ TODO / Future Improvements

- Add user login/registration system
- Improve UI using a GUI (Tkinter or PyQt) or a web interface (Flask/Django)
- Add email notifications for booking confirmations
- Deploy as a Flask web app using Render or Railway
