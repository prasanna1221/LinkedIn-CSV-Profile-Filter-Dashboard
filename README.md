# LinkedIn CSV Profile Filter Dashboard 🚀

# This is a lightweight, intuitive web application designed to help you efficiently manage and filter your LinkedIn connections. Built with **FastAPI** for the backend and **TailwindCSS** for a sleek, responsive user interface, this tool allows you to upload your exported LinkedIn connections CSV and quickly search and filter profiles based on various criteria.

## Features

# **Name Search:** Easily find connections by searching for their names.
# **Company Filter:** Filter profiles by company using a convenient dropdown with auto-search functionality.
# **Position/Designation Filter:** Narrow down connections by their job title or designation, also supported by a dropdown with auto-search.

# ---

## 📸 Demo

# ![demo gif or screenshot here]

# ---

## 📁 How to Use

### 1. Export Your LinkedIn Data

# To get started, you'll need to export your LinkedIn connections data:

# Navigate to LinkedIn → Settings & Privacy → Data Privacy → Get a copy of your data.
# Select "Connections" as the data archive you wish to download.
# Download the generated CSV file.

# ---

### 2. Run This Project Locally

# Follow these steps to set up and run the application on your local machine:

#### Step 1: Clone the Repository
git clone https://github.com/YOUR_USERNAME/linkedin-csv-filter-dashboard.git
cd linkedin-csv-filter-dashboard

#### Step 2: Create a Virtual Environment (Recommended)
python -m venv venv
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

#### Step 3: Install Dependencies
pip install -r requirements.txt

#### Step 4: Run the Server
uvicorn backend.main:app --reload --port 5028

# Once the server is running, open your web browser and navigate to:
# http://localhost:5028/

# ---

## 🛠 Tech Stack

# **Python + FastAPI:** For a high-performance and robust backend API.
# **Pandas:** Utilized for efficient in-memory data processing and filtering of CSV data.
# **TailwindCSS:** For a utility-first CSS framework that enables rapid UI development.
# **No Database:** All data processing is done in-memory, ensuring quick filtering and enhanced privacy as no data is persistently stored.

# ---

## 🛡️ Notes

# **Data Privacy:** This application prioritizes your privacy. No data is stored or persisted; all processing occurs in-memory, ensuring your information remains secure.
# **Extensibility:** The project can be further extended to include features like data export, user authentication, or more advanced filtering options.

# ---

## 📃 License

# This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it, crediting the original source.
