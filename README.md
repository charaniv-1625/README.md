

---

# 🏪 Store Management System (C Program)

A simple and efficient **Store Management System** built in C using loops, file handling, and structures.
The program allows users to **add products, view products, and save/load data** using a text file.

---

## 📌 **Abstract**

This project is a basic Store Management System developed in C language.
It enables the user to manage a collection of products by performing essential operations such as adding new products, displaying stored products, and saving/loading data from a file.
The program uses **structures** to store product details and **file handling** to maintain data persistence. It is designed for educational purposes, especially for students learning C programming, loops, and file operations.

---

## 🌟 **Features of the Program**

* ✔️ Add new products with name, price, and available stock
* ✔️ Display all stored products in a clean tabular format
* ✔️ Save product data permanently into `store_data.txt`
* ✔️ Load saved product data when the program starts
* ✔️ Error handling for missing files
* ✔️ Simple menu-driven interface
* ✔️ Beginner-friendly and easy to modify

---

## 🛠️ **Technical Requirements**

### **Software Requirements**

* A C compiler such as:

  * GCC (recommended)
  * MinGW
  * Turbo C / CodeBlocks / Dev-C++
  * Visual Studio Code with C extension

### **Hardware Requirements**

* Minimum 2 GB RAM
* Any processor capable of running C programs
* 5 MB free disk space

### **Programming Concepts Used**

* Structures
* Loops
* File Handling
* Conditional Statements
* Arrays
* Standard Input/Output

---

## ⚙️ **Functional Requirements**

### **1. Add Product**

* Program asks for:

  * Product name
  * Product price
  * Stock quantity
* Saves details into memory and increments the product count.

### **2. Display Products**

* Shows all stored products in a formatted table with:

  * Name
  * Price
  * Stock

### **3. Save Data**

* Writes all product details into `store_data.txt`
* Uses file handling (`fprintf`)

### **4. Load Data**

* Reads previously stored products from the text file
* Loads them into the program during startup

### **5. Exit Program**

* Terminates the application safely

---

## ▶️ **How to Run the Program**

### **Step 1: Save the Code**

Save your program in a file named:

```
store_management.c
```

### **Step 2: Compile the Code**

Using GCC:

```bash
gcc store_management.c -o store_management
```

### **Step 3: Run the Program**

```bash
./store_management
```

### **Step 4: Use the Menu**

You will see:

```
Store Management System Menu:
1. Add Product
2. Display Products
3. Save Data
4. Exit
```

Choose an option and follow the instructions.

---

## 📁 **Data Storage File**

All products are saved into:

```
store_data.txt
```

Format inside the file:

```
ProductName Price Stock
```

Example:

```
Milk 30.50 10
Bread 25.00 20
```

---

## 📷 **Sample Output**

```
Products in the store:
Name                 Price      Stock      
Milk                 $30.50     10         
Bread                $25.00     20         
```

Here are **clean, professional, GitHub-friendly side headings** you can use in your README file to add your **screenshots**.
These headings look attractive and are commonly used in GitHub projects.

---

# 📸 Screenshots

## 🖥️ **1. Program Menu Screen**

![main alt](

---

## ➕ **2. Add Product Screen**

![main alt](

---

## 📋 **3. Display Products Output**

![main alt](

---

## 💾 **4. Save Data Confirmation**

![main alt](

---

## 📂 **5. Load Data on Startup**

![main alt](

---

## 🔚 **6. Exit Message**

![main alt](

---

### 🔍 Additional Optional Sections

If you want more:

* **7. store_data.txt File Preview**
* **8. Full Program Execution Demo**
* **9. Error Handling Example**

---

If you want, I can also insert these headings directly into your full README file layout.



