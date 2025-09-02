# ⚡ Automated File Processing Workflow – Lawazia Tech (P1)

This project was developed during my internship at **Lawazia Tech**.  
It automates the process of handling file uploads from **Google Drive** and integrates with **AWS S3** and email notifications.  

---

## 📌 Workflow Overview  

1. **File Upload to Google Drive**  
   - The workflow is triggered whenever a new file is uploaded.  

2. **File Verification with AI Agent**  
   - The system checks whether the uploaded file is in **HTML format**.  

3. **Conditional Processing**  
   - ✅ If the file is HTML:  
     - Upload the file to **AWS S3**  
     - Send a **success email notification** to the user  
   - ❌ If the file is NOT HTML:  
     - Send a **failure email notification**  
     - Delete the invalid file from **Google Drive**  

---

## 🛠️ Tech Stack  

- **Google Drive API** – File upload monitoring  
- **AI Agent** – File type verification  
- **AWS S3** – Storage for valid HTML files  
- **Email Service** – Success & failure notifications (e.g., AWS SES / SMTP)  
- **Automation Workflow** – Integrated to ensure seamless end-to-end execution  

---

## 🚀 Key Features  

- Automatic monitoring of Google Drive uploads  
- AI-powered validation of file format  
- Secure transfer of valid files to AWS S3  
- Instant email feedback to users  
- Cleanup of invalid files from Google Drive  

---

## 📚 Learning Outcomes  

- Cloud integration with **Google Drive API & AWS S3**  
- File validation using **AI models**  
- Automated email notification systems  
- Error handling & workflow automation  

---

## 🏅 Internship Project  

This project (**PJ1**) was completed as part of my internship at **Lawazia Tech**.  
