# SportsWise – Inventory Exchange System

**SportsWise** is a Flask-based web application designed to streamline the process of issuing, returning, and managing sports inventory in an educational institute. Developed as a college-level software engineering project, this system digitizes traditional inventory practices, reduces manual errors, and enhances transparency in sports equipment management.

## 🏀 Features

* 🔐 **User Login**: Authenticated access for sports faculty.
* 📦 **Inventory Management**: Add, delete, and view current stock of sports items.
* 📝 **Issue & Return Items**: Track item issues and returns against student IDs.
* ⏰ **Fine Calculation**: Automatically calculate dues for late returns.
* 📊 **Report Generation**: View logs of transactions and outstanding dues.
* 🔒 **Secure & Scalable**: Built with secure login and scalable to handle 1000+ items.

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3
* **Backend**: Python (Flask)
* **Database**: MySQL or any standard RDBMS
* **Server**: WSGI-compatible (e.g., Gunicorn, Flask's dev server)

---

## 📁 Folder Structure

```
SportsWise/
├── static/              # CSS, images
├── templates/           # HTML files (Jinja2 templating)
├── app.py               # Flask application
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 🚀 Installation Guide

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/SportsWise.git
cd SportsWise
```

### 2. Set Up a Virtual Environment (Optional but recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the Database

* Set up MySQL or your preferred RDBMS.
* Create necessary tables as per the data model (refer to the project report).
* Update database connection string in `app.py`.

### 5. Run the Application

```bash
python app.py
```

The application will be accessible at `http://localhost:5000`.

---

## 📚 Project Report

For detailed design, architecture, use cases, and testing procedures, refer to the full [Project Report](./Project_Report.pdf).
