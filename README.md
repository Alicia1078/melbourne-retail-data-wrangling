# melbourne-retail-data-wrangling
## 📂 Tasks Overview

### 🗃️ Task 1: Parsing Raw Files
- Parsed and converted raw `.txt` and `.xlsx` review files into structured `.csv` and `.json` formats.
- Applied regular expressions to extract meaningful fields like Google Map ID, review, and response.
- Merged multiple data sources and produced final unified outputs (`task1.csv` and `task1_output.json`) for analysis and reporting.

📁 Folder: `Task 1. Parsing Raw Files`

---

### 📊 Task 2: Exploratory Data Analysis
- Performed exploratory analysis on Google Review and auxiliary datasets to uncover review behavior patterns.
- Discovered insights such as the relationship between business categories and review frequency, and the impact of MISC values on reviews.
- Analyzed merged datasets to explore store types with the highest review rates and possible correlations between response rates and ratings.

📁 Folder: `Task 2. Exploratory Data Analysis`  
📁 Dataset: [meta-California.json (Google Drive)](https://drive.google.com/file/d/1coUVfJ66VV0cuFz9Yl_oypaQVE_wmBgX/view?usp=drive_link)

---

### 🧹 Task 3: Comprehensive Data Cleansing
- Addressed dirty data issues such as inconsistent formatting, incorrect values, and invalid coordinates.
- Imputed missing values in fields like delivery charges, customer satisfaction, and distances using statistical and domain-informed methods.
- Detected and removed outliers using multiple statistical techniques (3-sigma, Hampel, boxplots), ultimately validating performance through linear regression models.

📁 Folder: `Task 3. Comprehensive Data Cleaning`

