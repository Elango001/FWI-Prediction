## 📁 Repository Contents

### **`elangovan_milestone_1.ipynb`**
The main Jupyter Notebook includes:
- Data loading  
- Cleaning and preprocessing  
- Exploratory data analysis  
- Visualizations  

---

## 🛠 Dependencies

To run this notebook, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### **Libraries Used**
- **Pandas** – Data manipulation and cleaning  
- **NumPy** – Numerical computations  
- **Matplotlib & Seaborn** – Visualizations  
- **Jupyter Notebook** – Running `.ipynb` files  

---

## 📑 Data Schema (Inferred)

| Column Name | Description             | Data Type |
| ----------- | ----------------------- | --------- |
| day         | Day of month            | Integer   |
| month       | Month of year           | Integer   |
| year        | Year of observation     | Integer   |
| Temperature | Air temperature (°C)    | Float     |
| RH          | Relative Humidity (%)   | Float     |
| Ws          | Wind Speed              | Float     |
| Rain        | Rainfall (mm)           | Float     |
| FFMC        | Fine Fuel Moisture Code | Float     |
| DMC         | Duff Moisture Code      | Float     |
| DC          | Drought Code            | Float     |
| ISI         | Initial Spread Index    | Float     |
| BUI         | Buildup Index           | Float     |
| FWI         | Fire Weather Index      | Float     |

---

## 📊 Analysis Overview

The notebook follows a complete data analysis workflow:

### **1. Data Loading & Inspection**
- Load dataset  
- Inspect structure, column names, types  
- View initial records  

### **2. Data Cleaning / Preprocessing**
- Handle missing values  
- Convert data types  
- Parse dates (if applicable)  
- Fix inconsistent entries  

### **3. Exploratory Data Analysis (EDA)**
Includes analysis of:
- Temperature  
- Relative Humidity (RH)  
- Wind Speed (Ws)  
- Rain  

And analysis of Fire Weather Index components:
- FFMC  
- DMC  
- DC  
- ISI  
- BUI  
- FWI  

### **4. Visualization**
Visuals generated include:
- Histograms  
- Box plots  
- Correlation heatmap  
- Time-series line plots  

These help identify trends, anomalies, and feature relationships.

---

