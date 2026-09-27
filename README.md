# 📧 Email Extractor using Python

A simple and efficient Python application that extracts email addresses from a text file using **Regular Expressions (Regex)** and saves the extracted emails into a separate output file.

## ✨ Features

-  Reads text from an input file
-  Extracts valid email addresses using Regex
-  Removes duplicate email addresses while preserving order
-  Saves extracted emails into an output file
-  Automatically creates a sample input file if none exists
-  Displays extraction results in a clean console output

---

## 🛠️ Technologies Used

- Python 3
- Regular Expressions (`re`)
- Pathlib (`pathlib`)

---

## 📝 Example Input (`input.txt`)

```
Please contact hr@company.com

You can also reach manager@yahoo.in

Support Email: support@gmail.com
```

---

## ✅ Example Output (`extracted_emails.txt`)

```
hr@company.com
manager@yahoo.in
support@gmail.com
```

---

## 💻 Console Output

```
==================================================
EMAIL EXTRACTION COMPLETED
==================================================
Total Emails Found : 3
Saved To           : extracted_emails.txt

Extracted Emails:
--------------------------------------------------
1. hr@company.com
2. manager@yahoo.in
3. support@gmail.com
```

---

## 🎯 Learning Objectives

This project demonstrates:

- File Handling in Python
- Object-Oriented Programming (OOP)
- Regular Expressions (Regex)
- Exception Handling
- Working with `pathlib`
- Writing clean and maintainable Python code

---

## 🚀 Future Improvements

- Support for PDF and Word documents
- GUI using Tkinter
- Drag-and-drop file support
- Export results to CSV or Excel
- Email validation with advanced Regex

---

## 👨‍💻 Author

**Madala Tharun Kumar**

If you found this project helpful, feel free to ⭐ the repository!
