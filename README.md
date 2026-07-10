# Certificate Generator and Email Automation

## 📌 Project Overview

The Certificate Generator and Email Automation project is a Python-based application that automates the process of generating personalized certificates in PDF format and sending them directly to recipients via email. The system reads participant information from an Excel file, creates customized certificates, and emails them automatically, reducing manual effort and improving accuracy.

---

## 🚀 Features

* Generate personalized PDF certificates.
* Read participant details from an Excel file.
* Automatically send certificates via email.
* Support bulk certificate generation.
* Reduce manual work and human errors.
* Easy to customize certificate templates.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Read participant data from Excel
* **ReportLab** – Generate PDF certificates
* **smtplib** – Send emails using SMTP
* **email** – Create email messages with attachments
* **OpenPyXL** – Read and write Excel files
* **OS** – File and directory operations

---

## 📂 Project Structure

```text
certificate_project/
│── certificates/          # Generated PDF certificates
│── templates/             # Certificate template
│── data/                  # Excel files containing participant details
│── generate_certificate.py
│── send_email.py
│── requirements.txt
│── README.md
```

---

## ⚙️ How It Works

1. Prepare an Excel file containing participant names and email addresses.
2. Place the certificate template in the templates folder.
3. Run the certificate generation script.
4. Personalized PDF certificates are created automatically.
5. The application connects to the email server.
6. Each certificate is attached to an email.
7. Certificates are sent automatically to all participants.

---

## 📋 Prerequisites

* Python 3.10 or later
* pip package manager

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Generate certificates:

```bash
python generate_certificate.py
```

Send certificates via email:

```bash
python send_email.py
```

---

## 📈 Future Enhancements

* Web interface using Flask or Django
* QR code verification on certificates
* Certificate tracking dashboard
* Multiple certificate templates
* Database integration
* Email delivery status reports

---

## 👩‍💻 Author

**Sai Sri Naga Deepika Kunkatla**

* GitHub: https://github.com/Deepika-799
* LinkedIn: https://www.linkedin.com/in/sai-sri-naga-deepika-kunkatla/

---

## 📄 License

This project is developed for educational and learning purposes.
