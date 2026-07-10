# 🎓 Certificate Generator and Email Automation

## 📖 Overview

The **Certificate Generator and Email Automation** project is a Python-based application that automates the process of creating personalized certificates and sending them via email. It reads participant details from an Excel file, generates PDF certificates using a predefined template, and emails each certificate to the respective recipient.

This project eliminates the need for manual certificate creation, making it ideal for workshops, seminars, training programs, college events, and online courses.

---

## ✨ Features

* Generate personalized certificates automatically.
* Read participant details from an Excel spreadsheet.
* Create certificates in PDF format.
* Automatically send certificates via email.
* Support bulk certificate generation.
* Reduce manual effort and human errors.
* Easy to customize the certificate template.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Read participant data from Excel
* **ReportLab** – Generate PDF certificates
* **OpenPyXL** – Process Excel files
* **smtplib** – Send emails through SMTP
* **email** – Create email messages with attachments
* **os** – File and directory management

---

## 📂 Project Structure

```text
certificate_project/
│
├── main.py
├── students.xlsx
├── certificate_template.jpg
├── README.md
├── requirements.txt
├── .gitignore
│
├── output/
│   ├── cert_M_PRANATHI.pdf
│   ├── cert_R.SHALINI.pdf
│   ├── cert_T_BHAGYA_.pdf
│   └── ...
```

---

## ⚙️ How It Works

1. Prepare an Excel file containing participant names and email addresses.
2. Place the certificate template image in the project folder.
3. Run the Python application.
4. The application reads participant information from the Excel file.
5. A personalized PDF certificate is generated for each participant.
6. The generated certificate is saved automatically.
7. The application connects to the email server.
8. Each certificate is attached to an email and sent to the corresponding participant.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Deepika-799/certificate-generator.git
```

Move into the project directory:

```bash
cd certificate-generator
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the application:

```bash
python main.py
```

After execution:

* PDF certificates are generated.
* Certificates are automatically emailed to participants.

---

## 📋 Sample Input

The application reads participant details from **students.xlsx**.

| Name       | Email                                       |
| ---------- | ------------------------------------------- |
| John Doe   | [john@example.com](mailto:john@example.com) |
| Jane Smith | [jane@example.com](mailto:jane@example.com) |

---

## 📄 Output

* Personalized PDF certificates.
* Automatic email delivery to all participants.

---

## 🌟 Future Enhancements

* Web interface using Flask or Django.
* QR code verification for certificates.
* Multiple certificate templates.
* Database integration.
* Email delivery tracking.
* Certificate verification portal.

---

## 💡 Applications

This project can be used for:

* College Events
* Workshops
* Training Programs
* Online Courses
* Webinars
* Corporate Training
* Certificate Distribution Systems

---

## 👩‍💻 Author

**Sai Sri Naga Deepika Kunkatla**

* GitHub: https://github.com/Deepika-799
* LinkedIn: https://www.linkedin.com/in/sai-sri-naga-deepika-kunkatla/

---

## 📜 License

This project is intended for educational and learning purposes. Feel free to modify and extend it for your own use.
