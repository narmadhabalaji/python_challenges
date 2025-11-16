# ⭐ Python Challenges Repository

A beginner-friendly collection of small Python projects designed to strengthen core programming skills. These challenges cover fundamental concepts such as variables, strings, lists, tuples, dictionaries, slicing, loops, and user input. Ideal for students and beginners practicing Python basics.

---

## 📌 Table of Contents
- [About the Project](#about-the-project)
- [Projects Included](#projects-included)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

## 📖 About the Project

This repository contains **five short Python challenges** designed to help beginners learn and apply core Python concepts using simple real-life scenarios.  
Each project is structured to be easy to read, run, and modify — making it perfect for practice, self-learning, or teaching.

---

## 🗂️ Projects Included

### **1️⃣ Student Information System**
- Concepts: variables, lists, append, input, print formatting  
- Task: Gather and display student information in a structured format  
- File: `challenge_1_student_info.ipynb`

---

### **2️⃣ Secret Message Decoder**
- Concepts: strings, slicing, case methods, text transformation  
- Task: Encode/decode a message by reversing/slicing and applying string methods  
- File: `challenge_2_secret_message.ipynb`

---

### **3️⃣ Retail Inventory Manager**
- Concepts: tuples, lists, indexing, append/pop  
- Task: Manage a simple store inventory and update stock  
- File: `challenge_3_inventory_manager.ipynb`

---

### **4️⃣ Student Grades & Hobbies Tracker**
- Concepts: dictionaries, lists, loops, averages, input handling  
- Task: Store student details, calculate average grades, and list hobbies  
- File: `challenge_4_grades_hobbies.ipynb`

---

### **5️⃣ BMI Calculator (Body Mass Index)**
- Concepts: input handling, arithmetic, conditional statements  
- Task: Take weight & height as input, calculate BMI, classify the category  
- Code:

```python
#getting input
weight=int(input('Enter your weight(in kg):'))
height=float(input('Enter your height (in meter):'))

BMI=weight/(height*height)

#categorizing BMI
if BMI < 18.5:
  category="Under Weight"
elif BMI <= 24.9:
  category="Normal Weight"
elif BMI <= 29.9 :
  category="Over Weight"
elif BMI <= 34.9: 
  category="Obesity Class 1"
elif BMI <= 39.9:
  category="Obesity Class 2"
else:
  category="Extreme Obesity"

print('\nYour BMI is:',round(BMI,2))
print("Your BMI Category is:", category)
```

---

## 🛠️ Built With
- **Python 3.x**
- **Jupyter Notebook (ipynb)**  
- Works on:
  - Google Colab  
  - VS Code  
  - Jupyter Lab / Notebook  

---

## 🚀 Getting Started

### Prerequisites
You need Python and Jupyter Notebook (or Google Colab) to run these challenges.

```bash
pip install notebook
```

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/narmadhabalaji/python_challenges.git
```

Navigate to the folder:

```bash
cd python_challenges
```

Open any challenge in Jupyter:

```bash
jupyter notebook
```

---

## ▶️ Usage

You can run these challenges in:
- Jupyter Notebook  
- Google Colab  
- VS Code (with Python + Jupyter extensions)

Simply open the `.ipynb` file and run the cells one by one.

---

