# Covid19-Data-Analysis

# Description
This project explores COVID-19 case trends using Python. It includes full data cleaning, exploratory data analysis (EDA), and visualizations to understand patterns such as confirmed cases, recoveries, fatalities, and country-by-country comparisons.
The goal of this project is to practice handling real-world data while developing analytical and visualization skills essential for data science.


# Project Features
-Cleaning and preprocessing large COVID-19 datasets
-Generating country-level summaries
-Visualizing confirmed cases, recovered cases, and deaths
-Identifying trends and patterns across time
-Extracting insights from noisy real-world data
-Using industry-standard Python libraries

# Technologies Used
-Python
-Pandas
-NumPy
-Matplotlib

Jupyter Notebook / Python Script

📁 Project Structure
covid19-analysis/
│── data/
│   └── covid_19_data.csv      # Not included due to GitHub 25MB limit
│── notebooks/
│   └── covid_analysis.ipynb
│── scripts/
│   └── covid_analysis.py
│── README.md
│── requirements.txt

🚫 Why the Dataset is Not Included

GitHub does not allow uploading files larger than 25MB, and many COVID-19 datasets exceed this size.
To run this project:

🔗 Option 1 — Download the dataset manually

You can download a COVID-19 dataset from:

Johns Hopkins CSSE:
https://github.com/CSSEGISandData/COVID-19

or

Kaggle:
https://www.kaggle.com/datasets

After downloading, place the CSV file here:

/data/covid_19_data.csv

▶️ How to Run the Project

Clone the repository:

git clone <your-repo-link>


Navigate into the folder:

cd covid19-analysis


Install dependencies:

pip install -r requirements.txt


Run the script:

python scripts/covid_analysis.py


Or open the notebook inside Jupyter.

📌 Skills Demonstrated

Data wrangling

Handling large datasets

Exploratory Data Analysis (EDA)

Data visualization

Insight extraction

Writing clean, reusable Python code

📝 requirements.txt

Paste this into your requirements.txt:

pandas
numpy
matplotlib

🧩 SOLUTION FOR THE 25MB ERROR

GitHub CANNOT accept any file bigger than 25MB.

So you have three options, choose the one you like:

✔ OPTION 1: Put the dataset on Kaggle or Google Drive

Then add this to your README:

📥 Download Dataset  
Google Drive Link: <paste-your-drive-link-here>  


This is the easiest and the best method.

✔ OPTION 2: Compress the CSV (ZIP it)

But GitHub still won’t allow it if the ZIP > 25MB.
So this only works if your ZIP file is smaller than 25MB.

✔ OPTION 3: Ignore the dataset — users download it themselves

This is the most professional and most common option.

Just create a data/ folder and leave it empty,
add a note in README telling users where to download the CSV.
