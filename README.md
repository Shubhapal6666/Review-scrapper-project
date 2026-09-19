# 🛍️ Review Scraper

A Python-based web scraping project that collects product reviews and related information from e-commerce websites. The project uses Selenium and BeautifulSoup to automate web browsing and extract useful review data.

The project also includes a web application for working with the scraped data.

## 🚀 Features

- 🔎 Scrape product reviews from e-commerce websites
- 🌐 Automate browser interaction using Selenium
- 🧹 Extract web page data using BeautifulSoup
- 📊 Process and analyze scraped data
- 🖥️ Web application using Flask
- 📓 Jupyter Notebook for development and experimentation
- 📈 Data visualization and analysis
- 🗂️ Organized project structure for easy development

## 🛠️ Technologies Used

- Python
- Selenium
- BeautifulSoup
- Flask
- Streamlit
- Pandas
- NumPy
- Plotly
- Jupyter Notebook
- HTML
- CSS

## 📂 Project Structure

    review-scrapper-main/
    │
    ├── pages/
    ├── src/
    ├── static/
    ├── templates/
    │
    ├── myntra.ipynb
    ├── app.py
    ├── application.py
    ├── requirements.txt
    ├── setup.py
    ├── README.md
    └── .gitignore

## ⚙️ Installation

### 1. Clone the Repository

    git clone YOUR_GITHUB_REPOSITORY_URL

### 2. Open the Project Folder

    cd review-scrapper-main

### 3. Create a Virtual Environment

    python -m venv .venv

### 4. Activate the Virtual Environment

For Windows PowerShell:

    .\.venv\Scripts\Activate.ps1

If PowerShell does not allow script activation, use:

    .\.venv\Scripts\python.exe -m pip install -r requirements.txt

### 5. Install Required Dependencies

    pip install -r requirements.txt

## ▶️ Running the Project

### Jupyter Notebook

Start Jupyter Notebook using:

    jupyter notebook

Then open:

    myntra.ipynb

Run the notebook cells from top to bottom using:

    Shift + Enter

### Flask Application

Run the Flask application using:

    python app.py

Then open the application in your browser:

    http://127.0.0.1:5000/

## 🔄 Project Workflow

    Product / Website
           ↓
        Selenium
           ↓
       Web Page
           ↓
     BeautifulSoup
           ↓
    Review Extraction
           ↓
     Data Processing
           ↓
     Analysis / Display
           ↓
      Web Application

## 📌 Project Applications

This project can be used for:

- Product review collection
- E-commerce data scraping
- Web scraping practice
- Review data processing
- Data analysis
- Learning Selenium
- Learning BeautifulSoup
- Building Python web applications

## 🔮 Future Improvements

- Add sentiment analysis for reviews
- Add support for additional e-commerce websites
- Store scraped reviews in a database
- Add advanced review filtering
- Add interactive dashboards
- Improve scraping performance
- Add automated data cleaning
- Deploy the application online
