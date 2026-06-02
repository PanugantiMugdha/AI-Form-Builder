# 🤖 AI-Powered Form Builder & Document Autofill

## 📌 Project Overview

AI-Powered Form Builder & Document Autofill is a web application that enables users to dynamically create custom forms and automatically populate them using information extracted from uploaded documents.

The application demonstrates how AI-assisted document processing can reduce manual data entry and improve workflow efficiency.

---

## ✨ Features

### 🛠 Dynamic Form Builder

- Create forms completely from scratch
- Add custom field labels
- Define field requirements
- Real-time form preview
- User-defined form schema

Supported field types:

✅ Single Line Text  
✅ Multi Line Text  
✅ Number  
✅ Date  
✅ Dropdown  
✅ Checkbox

---

### 📄 Document Upload

Supported file formats:

- PDF
- PNG
- JPG
- JPEG

Features:

- File validation
- Success confirmation
- Error handling for unsupported files

---

### 🤖 AI-Powered Autofill (Prototype)

The system simulates an AI extraction workflow:

1. Upload a document
2. AI reads document content
3. Extracts structured information
4. Matches extracted values with form fields
5. Autofills corresponding fields
6. Highlights missing information for review

Example:

| Field | Extracted Value |
|---------|---------|
| Candidate Name | John Doe |
| Email Address | john@email.com |
| Skills | React, Node.js, Python |
| Years of Experience | 4 |

---

### 👥 Role-Based Access

#### Admin

- Create forms
- Add form fields
- Configure field types
- Define required fields

#### User

- View generated forms
- Upload documents
- Review extracted information
- Submit completed forms

---

### 💾 Review & Save

- Review extracted values
- Edit autofilled fields manually
- Validate required fields
- Save completed forms

---

## 🏗 Architecture

```text
Admin Creates Form
         │
         ▼
 Dynamic Form Schema
         │
         ▼
   Upload Document
         │
         ▼
 AI Extraction Layer
         │
         ▼
 Structured JSON Data
         │
         ▼
 Automatic Autofill
         │
         ▼
 User Review & Edit
         │
         ▼
      Save Form
```

---

## 📂 Project Structure

```text
AI-Form-Builder
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🚀 Technologies Used

| Technology | Purpose |
|------------|----------|
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript | Functionality |
| Git | Version Control |
| GitHub | Repository Hosting |

---

## 🔮 Future Enhancements

- Real AI API Integration
- OCR Support
- Database Integration
- User Authentication
- Form Templates
- PDF Export
- JSON Export
- Cloud Deployment
- Analytics Dashboard

---

## 📸 Key Functionalities

✔ Dynamic Form Creation

✔ Live Preview

✔ File Upload Validation

✔ AI Extraction Workflow

✔ Autofill Functionality

✔ Missing Field Detection

✔ Review & Save

✔ Admin/User Views

---

## 👩‍💻 Author

### Mugdha Panuganti

📧 panugantimugdha@gmail.com

🔗 GitHub: https://github.com/PanugantiMugdha

---

