# Split Bill App

Welcome to the **Split Bill App project**! This simple and useful utility helps users quickly calculate how to split a total bill amount — including a tip — evenly among a group of people.

---

## 🚀 Project Overview

This is a **single-component** project with the following prebuilt components:
- ✅ A **fully designed HTML form** with inputs for:
  - **Bill amount**
  - **Tip percentage**
  - **Number of people**
- ✅ A **CSS file** that provides styling for a clean and user-friendly interface.
- ✅ A **partially written JavaScript file** with a `calculateSplit()` function.

Your task is to:
- **Complete the `calculateSplit()` function** to:
  - Read and validate the user inputs.
  - Calculate the **tip amount**, **total bill**, and **per person share**.
  - Display the final result on the page.

---

## 🎯 Functionality Requirements

- Read the **bill amount**, **tip percentage**, and **number of people**.
- Validate the inputs:
  - If any input is missing, not a number, or the number of people is less than or equal to zero, display:
    ```
    Please enter valid inputs.
    ```
- Perform the calculation:
  - **Tip Amount** = `(tip percentage / 100) * bill amount`
  - **Total Amount** = `bill amount + tip amount`
  - **Per Person Share** = `total amount / number of people`
- Display the result:
    ```
    Each person pays: ₹<amount>
    ```
  - The amount should be **rounded to two decimal places**.

---

## 🛠️ Technologies Used

- **HTML**: For structuring the form and input fields.
- **CSS**: For styling the application.
- **JavaScript**: For implementing the core calculation logic.

---

## 🧩 How to Run

1. Open the `index.html` file in your browser.
2. Enter:
   - The **bill amount**.
   - The **tip percentage** (optional, defaults to 0 if not provided).
   - The **number of people** to split the bill.
3. Click the **"Calculate"** button.
4. The app will display the amount each person needs to pay.

---

## ✅ Expected Output Example

| Bill Amount | Tip (%) | People | Output                    |
|-------------|---------|--------|---------------------------|
| 1000        | 10      | 2      | Each person pays: ₹550.00 |

---

Happy Coding! 🚀
