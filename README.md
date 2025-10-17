# Customer360 – Django Full Stack Application

A full-stack web application built with **Django**, **Bootstrap**, and **SQLite** that manages customer data, interactions, and business insights.  
Developed as part of the *Practice Lab for Django Full Stack Application Certification (Oct 2025)*.

---

## 🧩 Features

- **Customer Management:** Create, view, update, and delete customer records.  
- **Interaction Tracking:** Log communications and activity per customer.  
- **Summary Dashboard:** Visualize customer engagement and key metrics.  
- **Responsive Design:** Front-end styled with Bootstrap for consistent UX across devices.  
- **Modular Architecture:** Implements Django’s MVT pattern (Model-View-Template) for clarity and scalability.

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|---------------|
| Front-end | HTML5, CSS3, Bootstrap 3 |
| Back-end | Django 5.x (Python 3) |
| Database | SQLite 3 |
| Tools | Git & GitHub, VS Code, Python venv |
| Deployment | Localhost / Heroku (optional) |

---

## 📁 Project Structure

```
customer360/
│
├── customer360/          # Core project folder
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── customers/            # Main Django app
│   ├── templates/
│   │   ├── index.html
│   │   ├── create.html
│   │   ├── interact.html
│   │   └── summary.html
│   ├── views.py
│   ├── models.py
│   └── forms.py
│
├── static/
│   └── css/
│       └── main.css
│
└── manage.py
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YourUsername/customer360.git
cd customer360
```

### 2. Create & activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run database migrations
```bash
python manage.py migrate
```

### 5. Launch the server
```bash
python manage.py runserver
```

Visit **http://127.0.0.1:8000/** to view the app.

---

## 📸 Screenshots

*(Add screenshots of your main pages: Home, New Customer, Interaction Log, Summary Dashboard.)*

---

## 📜 Certification Reference

This project was developed as part of the  
**Practice Lab – Django Full Stack Application Certification (October 2025)**.

---

## 👨‍💻 Author

**Gonzalo Patino Castillo**  
Embedded & Software Engineer | IoT & AI Systems Developer  
[LinkedIn](https://www.linkedin.com/in/gonzalopatinocastillo) | [GitHub](https://github.com/YourUsername)

---

## 🧠 Future Enhancements

- Authentication system with role-based access  
- REST API integration for mobile clients  
- Data visualization dashboards using Chart.js  
- Dockerized deployment
