# 🌐 Registration Form using HTML, CSS & JavaScript

## 📌 Project Overview

This project implements an **interactive Registration Form** using **HTML, CSS, and JavaScript**.
The form includes **input validation, dynamic DOM manipulation, and user-friendly features** to improve the user experience.

The application ensures that users provide valid information before submitting the form and allows dynamic interaction such as changing the page appearance and adding graduation details.

---

# 🎯 Objectives

* Design a **user-friendly registration form**.
* Implement **client-side form validation** using JavaScript.
* Demonstrate **DOM manipulation**.
* Provide **interactive UI features** like dynamic background color and dynamic list addition.

---

# 🛠 Technologies Used

| Technology     | Purpose                                 |
| -------------- | --------------------------------------- |
| **HTML**       | Structure of the webpage                |
| **CSS**        | Styling and layout                      |
| **JavaScript** | Form validation and dynamic interaction |

---

# ✨ Key Features

## 1️⃣ Form Validation

The form performs validation before submission to ensure correct user input.

Validation checks:

* Name field **cannot be empty**
* Email field **cannot be empty**
* Email must follow a **valid email format**

If validation fails, an **alert message** is displayed.

---

## 2️⃣ Dynamic Heading Change

Users can change the heading of the page by clicking a button.

Example:

```
Registration Form → NEET Form
```

This demonstrates **DOM content manipulation**.

---

## 3️⃣ Random Background Color

A button allows users to change the **background color randomly**, making the interface more interactive.

The color is generated dynamically using JavaScript's `Math.random()` function.

---

## 4️⃣ Add Graduation Details Dynamically

Users can enter graduation qualifications and add them to a list.

Example list:

```
B.Sc
B.Tech
MCA
MBA
```

Each entry is added dynamically using JavaScript DOM functions.

---

# 🧠 JavaScript Functions Used

### `validateForm()`

Validates the form fields before submission.

Checks:

* Empty name
* Empty email
* Invalid email format

---

### `changeHeading()`

Updates the page heading dynamically.

---

### `changeBackground()`

Generates and applies a **random background color** to the page.

---

### `addGraduation()`

Adds graduation entries to a list dynamically.

Steps:

1. Read user input
2. Create a new list item
3. Append it to the graduation list
4. Clear the input field

---

# 📋 Form Fields

| Field             | Description                |
| ----------------- | -------------------------- |
| **Name**          | User's full name           |
| **Email**         | Valid email address        |
| **Gender**        | Male / Female / Other      |
| **Graduation**    | Dynamic qualification list |
| **Date of Birth** | Date picker                |
| **Submit**        | Submit form                |

---

# 🔄 Program Flow

```
Start
 ↓
Display Registration Form
 ↓
User enters details
 ↓
Dynamic features available (buttons)
 ↓
JavaScript validation
 ↓
If valid → Form submitted
If invalid → Error message
```

---

# 📷 Expected Output

### Registration Form Interface

* Heading
* Name and Email input
* Gender selection
* Graduation list section
* Date of birth picker
* Submit button

Users can also:

* Change heading
* Change background color
* Add graduation entries dynamically

---

# ✅ Conclusion

This project demonstrates how **HTML, CSS, and JavaScript work together** to create an interactive and user-friendly web form.
It highlights **client-side validation, dynamic DOM manipulation, and responsive user interface features**, which are fundamental concepts in modern web development.
