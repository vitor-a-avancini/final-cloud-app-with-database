# 🌐 Final Cloud App with Database

![Status](https://img.shields.io/badge/status-stable-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 🚀 Overview

This repository contains a **cloud-based web application** demonstrating full-stack development using Python, Flask, and IBM Cloudant. The app enables users to interact with a web UI, perform CRUD operations, and store/retrieve data from a managed NoSQL database service in the cloud.


For reference, the ER diagram design is the following

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

---

## 📂 Repository Structure

```
.
├── static/                # CSS, images, and static web assets
├── templates/             # Flask HTML templates (Jinja2)
├── app.py                 # Main Flask app
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── .gitignore
```

---

## 🛠 Tech Stack

* **Backend**: Python, Flask
* **Frontend**: Jinja2 templates, HTML/CSS
* **Database**: IBM Cloudant (NoSQL)
* **Deployment**: IBM Cloud, local

---

## ✅ Prerequisites

* Python 3.x
* IBM Cloud account (for Cloudant setup)
* Cloudant service credentials (API key, URL, etc.)

---

## ⚙️ Setup & Run (Local)

1. **Clone the repository:**

   ```bash
   git clone https://github.com/vitor-a-avancini/final-cloud-app-with-database.git
   cd final-cloud-app-with-database
   ```
2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
3. **Configure Cloudant credentials:**

   * Set environment variables (`CLOUDANT_URL`, `CLOUDANT_USERNAME`, `CLOUDANT_APIKEY`) **or** edit directly in `app.py` if testing locally.
4. **Run the Flask app:**

   ```bash
   python app.py
   ```
5. **Open your browser:**

   * Go to [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🖥️ Features

* User-friendly web interface
* Add, view, update, and delete records (CRUD)
* Persistent storage with IBM Cloudant
* Simple, clean layout with Bootstrap CSS (via CDN)

---

## 📝 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork this repository or submit pull requests.

---

## 📚 References & Further Reading

* [IBM Cloudant Documentation](https://cloud.ibm.com/docs/Cloudant)
* [Flask Documentation](https://flask.palletsprojects.com/)

---

> **A clean, cloud-ready template for Flask apps with IBM Cloudant.**
