# 📝 Form Validator

A simple **JavaScript-based form validation system** that ensures user inputs are correct before submission.  
This project validates **name, phone number, email, and message fields** with clear error messages and visual feedback.

---
## 🎥 Demo Here’s a quick demo of the Form Validator in action: [Form Validator Demo](https://form-validator-three-rust.vercel.app/)

## 🚀 Features
- ✅ Name Validation  
  - Requires full name (first and last).  
  - Only alphabetic characters allowed.  

- 📱 Phone Validation  
  - Must be exactly 10 digits.  
  - Only numeric values accepted.  

- 📧 Email Validation  
  - Checks for proper email format (e.g., example@domain.com).  
  - Displays error if invalid.  

- 💬 Message Validation  
  - Requires at least 30 characters.  
  - Shows how many characters are still needed.  

- 🔔 Form Submission Check  
  - Prevents submission until all fields are valid.  
  - Displays a temporary error message if validation fails.  

---

## 🛠️ Technologies Used
- HTML – Form structure  
- CSS – Styling and error display  
- JavaScript (Vanilla JS) – Validation logic  

---

## 📂 Project Structure
```
form-validator/
│── index.html         # Form UI
│── style.css          # Styling for form and error messages
│── form.js            # Validation logic
│── README.md          # Project documentation
```
## ⚙️ How It Works
1. User enters details in the form.  
2. Each field is validated when the user interacts with it.  
3. If invalid, an error message is shown below the field.  
4. If valid, a checkmark icon (`ri-checkbox-circle-fill`) appears.  
5. On submission, all fields are checked again.  
6. If any field is invalid, submission is blocked and an error message is displayed.
