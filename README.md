Here's a README file for your **Billing Software** project. It provides an overview of the features, technologies used, installation instructions, and usage guide.

---

# 🧾 Billing Software using Python & Tkinter

## 📌 Project Overview
This is a simple GUI-based **Billing Software** developed using **Python** and **Tkinter**. The software helps to generate itemized bills for medical, grocery, and cold drink items. It allows for customer information entry, automatic total and tax calculation, and saving/retrieving bills.

---

## 💻 Technologies Used

- **Python 3.x**
- **Tkinter (for GUI)**
- **OS module** (to handle file operations)
- **Random module** (to generate unique bill numbers)

---

## 🛠️ Features

- Item entry for **Medical**, **Grocery**, and **Cold Drink** products.
- **Customer information** input with phone number.
- **Auto-generated unique bill numbers**.
- **Bill calculation** including total and taxes.
- **Bill area** shows the final receipt-style output.
- Save bills as `.txt` files inside a `bills/` directory.
- **Search bills** by bill number.
- **Clear form** and **exit** functions.

---

## 📦 Products Covered

### 🏥 Medical Items
- Sanitizer
- Mask
- Hand Gloves
- Dettol
- Newsprin
- Thermal Gun

### 🛒 Grocery Items
- Rice
- Food Oil
- Wheat
- Daal
- Flour
- Maggi

### 🥤 Cold Drinks
- Sprite
- Limka
- Mazza
- Coke
- Fanta
- Mountain Duo

---

## 🧮 Taxes
- **Medical Tax**: 5%
- **Grocery Tax**: 500% (Seems unintended, might want to check this)
- **Cold Drinks Tax**: 10%

---

## 🖥️ How to Run

### Step 1: Clone or Download the Repository

```bash
git clone https://github.com/yourusername/billing-software.git
```

### Step 2: Make Sure Python is Installed

Check Python version:
```bash
python --version
```

### Step 3: Create Required Folder

Create a folder named `bills` in the same directory where the Python file is located. This is necessary to save the generated bills.

```bash
mkdir bills
```

### Step 4: Run the App

```bash
python billing_software.py
```

---

## 🖼️ Sample Output (Bill Area - GUI)

```
	Welcome Webcode Retail
 Bill Number:1098
Customer Name:John Doe
Phone Number:9876543210
================================
Products		QTY		Price
 Sanitizer		2		4
 Mask		3		15
 Hand Gloves		2		24
 Dettol		1		30
 Newsprin		1		5
 Thermal Gun		1		15
 Rice		2		20
 Food Oil		1		10
 Mazza		3		30
 Cold Drinks Tax			Rs.3.0
 Grocery Tax			Rs.300.0
 Medical Tax			Rs.4.45
 Total Bil:		 Rs.455.45
--------------------------------
```

---

## 📝 Notes

- Make sure to create the **bills/** folder in the root directory, or bill saving will fail.
- This software is mainly for **educational/demo purposes**, not for production use.
- Improve tax rates and item prices for real-world use.

---

## ✍️ Author

Developed by Manikanta Sangani

---

Would you like me to generate a sample screenshot/image of the **Bill Area Output** or embed that output as a visual representation? Let me know and I can generate it for you!
