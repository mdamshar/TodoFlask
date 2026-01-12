# 📝 Flask To-Do App

A simple **To-Do List web application** built using **Flask**, **Jinja2**, and **Semantic UI**.
This app allows users to **add**, **update**, **mark complete**, and **delete** tasks through a clean and responsive UI.

---

## 🚀 Features

* Add new to-do items
* View all tasks in a list
* Mark tasks as **Completed / Not Completed**
* Update existing tasks
* Delete tasks
* Clean UI using **Semantic UI**
* Server-side rendering using **Jinja templates**

---

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **Jinja2**
* **HTML5**
* **Semantic UI (CDN)**
* **SQLite** (commonly used with Flask)

---

## 📁 Project Structure

```
todoFlask/
│
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── (optional css/js)
├── venv/
├── requirements.txt
└── README.md
```

---

## 📄 Template Overview

The main UI is rendered using **index.html**, which includes:

* A form to add new to-do items
* A loop to display all tasks
* Status labels:

  * 🟢 Completed
  * ⚪ Not Complete
* Action buttons:

  * **Update**
  * **Delete**

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/flask-todo-app.git
cd flask-todo-app
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install flask
```

### 5️⃣ Run the Application

```bash
python app.py
```

---

## 🌐 Routes Used

| Route          | Method | Description              |
| -------------- | ------ | ------------------------ |
| `/`            | GET    | Display all todos        |
| `/add`         | POST   | Add a new todo           |
| `/update/<id>` | GET    | Toggle completion status |
| `/delete/<id>` | GET    | Delete a todo            |

---

## 🖥️ UI Framework

This project uses **Semantic UI CDN**:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/semantic-ui@2.5.0/dist/semantic.min.css">
```

---

## 📌 Future Improvements

* User authentication
* Due dates & priorities
* Edit todo titles
* REST API support
* Database migrations
