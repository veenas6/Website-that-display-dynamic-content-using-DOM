### Title: Registration Form using HTML, CSS and JavaScript

---


---

#Objective

To design a **web-based registration form** that:

* Validates user input using **JavaScript**
* Dynamically changes page content
* Allows users to **add graduation entries dynamically**

---

#Technologies Used

* **HTML** – Structure of the webpage
* **CSS** – Styling and layout
* **JavaScript** – Form validation and dynamic interaction

---

#Features of the Program

### 1️⃣ Form Validation

The form validates:

* **Name field** cannot be empty
* **Email field** cannot be empty
* Email must follow a **valid email format**

If validation passes, a success message appears.

---

### 2️⃣ Change Heading Button

* Button changes heading text from
  **"Registration Form" → "NEET Form"**

Implemented using JavaScript DOM manipulation.

---

### 3️⃣ Change Background Color

* Generates a **random background color** when clicked.

Uses:

```javascript
Math.random()
```

to create random hex colors.

---

### 4️⃣ Add Graduation Dynamically

Users can:

* Enter graduation qualification
* Click **Add**
* The qualification is added to the list below.

Example:

```
B.Sc
B.Tech
MCA
```

---

#Functions Used

## 1. `validateForm()`

Validates the form fields before submission.

Checks:

* Empty name
* Empty email
* Invalid email format

Returns:

* `true` → form submits
* `false` → form stops submission

---

## 2. `changeHeading()`

Changes the page heading.

```javascript
document.getElementById("heading").innerHTML="NEET Form";
```

---

## 3. `changeBackground()`

Changes the background color randomly.

```javascript
document.body.style.backgroundColor =
"#" + Math.floor(Math.random()*16777215).toString(16)
```

---

## 4. `addGraduation()`

Adds graduation qualification to a list dynamically.

Steps:

1. Get input value
2. Create `<li>` element
3. Insert into `<ul>`
4. Clear input box

---

#Form Fields

| Field         | Type                      |
| ------------- | ------------------------- |
| Name          | Text                      |
| Email         | Email                     |
| Gender        | Radio buttons             |
| Graduation    | Text input + dynamic list |
| Date of Birth | Date picker               |
| Submit        | Submit button             |

---

#Program Flow

```
Start
 ↓
Display Registration Form
 ↓
User enters details
 ↓
Buttons provide dynamic functions
 ↓
Form validation checks input
 ↓
If valid → Form submitted
Else → Error message
```

---

#Example Output

### Initial Page

```
Registration Form
[Change Heading]
[Change Background Colour]

Name: ______
Email: ______
Gender: ( )Male ( )Female ( )Other
```

### Graduation Section

```
Add Graduation
[Enter Graduation] [Add]

B.Sc
MCA
B.Tech
```

---

#Conclusion

This project demonstrates:

* **Form creation using HTML**
* **Styling with CSS**
* **Client-side validation with JavaScript**
* **Dynamic DOM manipulation**

It helps understand **interactive web page development**.
