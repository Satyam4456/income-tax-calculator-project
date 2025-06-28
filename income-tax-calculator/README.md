# 🧾 Income Tax Calculator (India – Old Regime)

This folder contains both the **console-based** and **Flask-based** versions of an Indian Income Tax Calculator based on the **Old Regime (as per Income Tax Act, 1961)**.

---

## 📂 Folder Structure

```
income-tax-calculator/
├── console_version/
│   └── tax_calculator.py
├── flask_version/
│   ├── main.py
│   ├── pyproject.toml / requirements.txt
│   └── templates/
│       ├── tax_form.html
│       ├── tax_result.html
│       ├── 404.html
│       └── 500.html
```

---

## 🧾 Console Version

- Pure Python script
- Runs in terminal
- Fully interactive with input-based flow
- No external libraries required

### ▶️ Run:
```bash
cd console_version
python tax_calculator.py
```

---

## 🌐 Flask Web App Version

- Web-based interface using Flask
- Input via HTML form, result shown as rendered HTML
- Handles surcharge, cess, and all income components

### ▶️ Run:
```bash
cd flask_version
pip install flask
python main.py
```

Visit: https://replit.com/join/idtzrvdtnm-satyamjhaa81 (for review)

---

## 👨‍💻 Created By

**Satyam Jha**  
Aspiring Data Analyst | Python & SQL Learner  
📧 satyamjhaa81@gmail.com
