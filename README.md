

# 🧮 Python GUI Calculator

A simple and modern **GUI Calculator** built using **Tkinter in Python**.
It supports basic arithmetic operations along with extra functions like square root, square, and percentage.

---

## 🚀 Features

* Basic operations: `+`, `-`, `*`, `/`
* Decimal support
* Square (`x²`)
* Square root (`√`)
* Percentage (`%`)
* Clear button (`C`)
* Error handling for invalid inputs
* Clean and modern dark UI

---

## 🛠️ Technologies Used

* Python
* Tkinter (for GUI)
* Math module

---

## 📂 Project Structure

```
calculator.py
README.md
```

---

## ▶️ How to Run

1. Install Python (if not already installed)
2. Download or clone this project
3. Open terminal/command prompt
4. Run:

```bash
python calculator.py
```

---

## 💡 How It Works

* The calculator uses a **Tkinter window** as the interface.
* Button clicks update the display using `entry_var`.
* Expressions are evaluated using Python’s `eval()` function.
* Additional math functions use the `math` module.

---

## ⚠️ Note

* Avoid entering invalid expressions (like `++`, `//`) as it may show an error popup.
* `eval()` is used, so this calculator is intended for **learning purposes only**.

---

## 📸 Output

A simple calculator window with:

* Number buttons
* Operator buttons
* Function buttons (√, x², %)
* Clean dark theme

---

## ✨ Future Improvements

* Add keyboard support
* Add scientific functions (sin, cos, log)
* Improve UI animations
* Replace `eval()` with safer parsing

