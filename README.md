**EXP 19 : Data Preprocessing and Data Cleaning**

**Theory**

**Data Preprocessing**

Data preprocessing is the process of preparing raw data for analysis. It involves cleaning, transforming, and organizing data to improve its quality and usability. Proper preprocessing ensures accurate and reliable results in data analysis.

**Handling Missing Values**

Missing values occur when no data is stored for a variable in an observation. These can be handled by:

* Removing rows or columns containing missing values
* Filling missing values using mean, median, or mode
  This helps in maintaining dataset consistency.

**Dropping Missing Values (dropna())**

The dropna() function is used to remove rows or columns that contain null or missing values. It is useful when missing data is minimal and does not significantly affect the dataset.

**Filling Missing Values (fillna())**

The fillna() function is used to replace missing values with a specified value such as mean, median, or a constant. This prevents loss of data and maintains dataset size.

**Data Cleaning**

Data cleaning involves detecting and correcting errors, inconsistencies, and inaccuracies in the dataset. It includes removing duplicates, correcting data types, and fixing invalid entries.

**Removing Duplicates (drop_duplicates())**

The drop_duplicates() function is used to remove duplicate rows from the dataset. This ensures that each data entry is unique and prevents biased analysis.

**Data Type Conversion**

Sometimes data is stored in incorrect formats. Converting data types (e.g., string to integer) helps in performing correct operations and analysis.

**Feature Scaling**

Feature scaling is used to normalize or standardize data so that all variables are on a similar scale. This improves the performance of machine learning algorithms and data analysis.

---

**Conclusion**

Thus, data preprocessing and data cleaning techniques were studied and implemented successfully. Various operations such as handling missing values, removing duplicates, converting data types, and scaling features were performed. The experiment demonstrated the importance of clean and well-structured data for accurate and efficient analysis.
