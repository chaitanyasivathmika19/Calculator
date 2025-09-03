
---

## ⚙️ How It Works
1. **HTML** defines the calculator layout with display and keys.
2. **CSS** styles the calculator for a neat and responsive design.
3. **JavaScript** (`main.js`) handles:
   - Input validation
   - Cleaning and formatting user input
   - Performing calculations using `eval` (after sanitization)
   - Output formatting with commas for readability

---

## ▶️ Usage
1. Open `index.html` in your browser.
2. Click the buttons to enter numbers and operators.
3. Use:
   - `AC` → clear everything  
   - `DEL` → remove last digit  
   - `%` → percentage  
   - `( )` → insert brackets  
   - `=` → calculate result  

---

## 🛠️ Example Calculations
- `12 + 5 = 17`
- `50 % = 0.5`
- `(25 + 5) * 2 = 60`
- `1000 / 25 = 40`

---

## 📌 Notes
- Only valid operator sequences are allowed.
- Consecutive operators like `++`, `--`, `*/` are automatically prevented.
- Percentage is internally converted to `/100`.

---

## 📷 Screenshot 

---

## 📄 License
This project is open-source and free to use for learning purposes.
