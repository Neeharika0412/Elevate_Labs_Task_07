# 🛒 TASK 7: Basic Sales Summary from SQLite Database using Python  
**Data Analyst Internship - MSME**

##  Objective  
Use SQL inside Python to:
- Pull basic sales info (total quantity sold, total revenue)
- Display results using print statements
- Visualize the results with a simple matplotlib bar chart

---

## 🛠 Tools Used  
- **Python** (`sqlite3`, `pandas`, `matplotlib`)  
- **SQLite** (built into Python, no setup needed)  
- **Jupyter Notebook** for development  
- **HTML Export** for easy viewing without running code  

---

##  Files in This Repository  
- **TASK7.ipynb** → Jupyter Notebook with all code and explanations  
- **TASK7.html** → Exported HTML version of the notebook for quick view in any browser (no Jupyter required)  
- **sales_data.db** → SQLite database containing the sample sales data  
- **README.md** → This file, explaining the project  

---

##  Steps Performed  

### **Step 1: Create and Populate SQLite Database**  
- Created a database `sales_data.db`
- Added a `sales` table with columns:  
  - `product` (TEXT)  
  - `quantity` (INTEGER)  
  - `price` (REAL)  
- Populated it with an **expanded dataset** covering multiple products and repeated entries

### **Step 2: Query Data using SQL in Python**  
- Connected to the database using `sqlite3`  
- Used an SQL query with `GROUP BY` to get:
  - Total quantity sold per product
  - Total revenue per product (`SUM(quantity * price)`)

### **Step 3: Data Visualization**  
- Loaded query results into a `pandas DataFrame`  
- Plotted a **bar chart** of revenue by product using `matplotlib`

---

## 📷 How to View the Results  
** Easiest way:** Open `TASK7.html` in any browser — you’ll see the code, output, and charts without installing anything.  

** To run the notebook yourself:**

3. Open `TASK7.ipynb` in Jupyter Notebook and run all cells

---

##  What I Learned  
- Connecting Python to SQLite databases  
- Writing SQL queries inside Python  
- Using `GROUP BY` to summarize data  
- Using pandas for easy data handling  
- Creating visualizations with matplotlib  

---



1. Clone/download this repository
2. Install dependencies:
