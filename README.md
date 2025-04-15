
# Customer 360 – Mini CRM with Django

This is a simple Customer Relationship Management (CRM) web application built using Django and SQLite3. The app allows users to manage customers and track their interactions through various communication channels.


## 📸 Preview

<div align="center"> <h3>🏠 Home</h3> <img src="https://i.imgur.com/i7KlkMy.png" width="80%" alt="Home Preview" /> </div>

<div align="center"> <h3>➕ Add a New Customer</h3> <img src="https://i.imgur.com/riEeBb8.png" width="80%" alt="Add Customer Preview" /> </div>

<div align="center"> <h3>📊 Summary</h3> <img src="https://i.imgur.com/OiHYh24.png" width="80%" alt="Summary Preview" /> </div>

<div align="center"> <h3>💬 Interact with Customer</h3> <img src="https://i.imgur.com/km8g7nF.png" width="80%" alt="Interact Preview" /> </div>

## 🚀 Features

- Add new customers with basic details
- Record and view customer interactions
- Interaction channels: Phone, SMS, Email, Letter, Social Media
- Summary view of interactions in the past 30 days
- Uses SQLite3 database for simplicity

## 📸 UI Preview

![UI Preview](path/to/your/image.png) <!-- Replace with your actual image path -->

## 🛠️ Technologies Used

- Python 3
- Django
- SQLite3
- HTML/CSS (Django Templates)

## 🏁 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/customer-360.git
cd customer-360
```
Install dependencies:

```bash
pip install -r requirements.txt
```
Run migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```
Start the development server:

```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ in your browser.

# 📂 Folder Structure
- **models.py**: Database models for Customer and Interaction

- **views.py**: Logic for handling customer creation, interaction, and summary

- **templates/**: HTML templates (index.html, add.html, interact.html, summary.html)
