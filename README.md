# Data-cleaning-using-Excel-Netflix-dataset
📁Dataset Used

Netflix Movies and TV Shows Dataset (CSV format from Kaggle)

---

🎯 Objective

The objective of this task was to clean and standardize a real-world dataset using Microsoft Excel and prepare it for further analysis.


---

🛠 Tools Used

Microsoft Excel

CSV Dataset (Kaggle)



---

🔍 Steps Performed

1️⃣ Imported Dataset

Downloaded dataset in CSV format

Opened in Excel

Ensured first row was recognized as column headers

Saved as Raw_Data.xlsx



---

2️⃣ Data Exploration

Applied Freeze Panes to lock header row

Enabled Filters on all columns for easier exploration



---

3️⃣ Identified Missing Values

Used Filter → (Blanks) to detect missing data

Highlighted blank cells using Conditional Formatting

Reviewed missing values before making decisions



---

4️⃣ Handled Missing Data

Kept missing values in descriptive columns like:

.director

.cast

.country


Ensured no missing values in key columns such as:

.show_id

.title

.type

.release_year


Added a new column Data_Quality_Notes to document observations



---

5️⃣ Removed Duplicates

Created a backup sheet before removing duplicates

Used Remove Duplicates based on key columns (show_id, title)



---

6️⃣ Standardized Text Data

Used Excel functions:

TRIM() to remove extra spaces

PROPER() to standardize capitalization


Ensured consistent formatting in categorical columns



---

7️⃣ Converted Date Format

Converted text dates into proper Excel date format

Standardized format to:

yyyy-mm-dd



---

8️⃣ Created Cleaned Dataset

Created a new sheet named Cleaned_Data

Copied only cleaned values

Saved final outputs as:

Cleaned_dataset.xlsx

cleaned_dataset.csv




---

📦 Deliverables

Raw_Data.xlsx

Cleaned_dataset.xlsx

cleaned_dataset.csv

README.md



---

🧠 Key Learnings

Importance of separating raw and cleaned data

Identifying and handling missing values

Removing duplicates carefully

Standardizing inconsistent text data

Converting text fields into proper data types



---

✅ Final Outcome

A clean, structured dataset ready for analysis and visualization.

