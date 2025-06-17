# -Noisy-Customer-Loan-Data-Cleaning-Analysis
This project focuses on cleaning and analyzing a noisy text file containing intermixed customer and loan data. The goal was to extract structured insights from raw, unformatted information and perform exploratory analysis to understand customer and loan behavior.

📁 Dataset Overview
The file contained a mix of customer records (with fields like name, gender, DOB, PAN, etc.) and loan records (in JSON format).

Data was heavily noisy, with random characters, missing values, and inconsistent structure.

🛠️ Tools & Technologies
Python (Pandas, Regex, JSON)

Data Visualization: Matplotlib, Seaborn

(Optional) SQL-like queries using Pandas or SQLite

🔧 Key Steps
Load and Separate Data

Read raw .txt file line-by-line

Separate customer vs. loan entries using regex and structured conditions

Clean the Data

Remove junk characters and format inconsistencies

Normalize and convert into two structured DataFrames

Join the Data

Merged customer and loan data using index or generated surrogate keys

Exploratory Data Analysis

Loan distribution by gender and status

DPD (Days Past Due) trends

Loan amount patterns by tenure

Visualization

Countplots, boxplots, and distribution charts to communicate findings

Exported Cleaned Dataset

Final structured dataset saved as CSV (joined_data.csv)

📈 Insights
Identified default trends by gender and loan status

Highlighted tenure patterns and high-risk customer segments

Ready for future ML tasks like risk prediction

📂 Files
load_clean.py: Complete cleaning and analysis pipeline

joined_data.csv: Final cleaned dataset

visualizations.png: Graphical output of key insights

🤝 Let's Collaborate
Feel free to fork the repo, explore the data, or suggest improvements!
For collaboration or feedback, reach out via LinkedIn or open an issue.

