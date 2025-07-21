# LinkedIn CSV Profile Filter Dashboard 🚀

A lightweight, intuitive web application designed to help you efficiently **manage and filter your LinkedIn connections**. Built with **FastAPI** for the backend and **TailwindCSS** for a sleek, responsive UI, this tool enables you to upload your exported LinkedIn connections CSV and **quickly search and filter profiles** based on multiple criteria.

---

## ✨ Features

- 🔍 **Name Search**: Easily find connections by typing their names.
- 🏢 **Company Filter**: Filter profiles by company using an auto-search dropdown.
- 👔 **Position/Designation Filter**: Narrow down connections by job title/designation with smart filtering.

---

## 📸 Demo

![demo gif or screenshot here]

---

## 📁 How to Use

### 1. Export Your LinkedIn Data

To get started, export your LinkedIn connections:

- Navigate to:  
  `LinkedIn → Settings & Privacy → Data Privacy → Get a copy of your data`
- Select **"Connections"** as the data archive to download.
- Download the generated **CSV file**.

---

### 2. Run This Project Locally

#### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/linkedin-csv-filter-dashboard.git
cd linkedin-csv-filter-dashboard
```

#### Step 2: Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

**On macOS/Linux:**

```bash
source venv/bin/activate
```

**On Windows:**

```bash
venv\Scripts\activate
```

#### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

#### Step 4: Run the Server

```bash
uvicorn backend.main:app --reload --port 5028
```

Then, open your browser and go to:  
👉 [http://localhost:5028/](http://localhost:5028/)

---

## 🛠 Tech Stack

- **Python + FastAPI**: High-performance, async-ready backend.
- **Pandas**: For efficient in-memory CSV processing and filtering.
- **TailwindCSS**: Utility-first CSS for rapid, responsive UI development.
- **No Database**: All filtering is done in-memory — fast and secure!

---

## 🛡️ Notes

- **Data Privacy**: Your data is never stored. Everything runs in-memory for your safety.
- **Extensibility**: Easily extend this project to support:
  - CSV export
  - User authentication
  - Advanced filters

---

## 📃 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute it, giving credit to the original source.

---

> Made with ❤️ using FastAPI & TailwindCSS
