
## Goal/Motivation
The goal of this project was to identify the most in-demand skills, tools, frameworks, and programming languages in the field of Data Science. To achieve this, I scraped job postings from TimesJobs and analyzed the data to uncover current market trends. This project helps aspiring data professionals align their learning paths with real-world industry demands.er

## Data Collection
The data was scraped from TimesJobs using Python. I collected key job-related information including:

- Job Type
- Experience Required
- Company Name
- Location
- Job Description
- Skills
- Salary

This data formed the foundation for analyzing the most frequently mentioned skills, tools, and technologies in Data Science job listings.
Code use for scrapping can be found [here](https://github.com/Fatimarz/Data-Analytics-Portfolio/blob/main/Data_science_job_analysis/DS_jobs_scrapping.ipynb)

## Tech Stack
- Python: Core programming language used throughout the project

- Requests & BeautifulSoup: For scraping job listings from TimesJobs

- Pandas & NumPy: For data cleaning and analysis

- Jupyter Notebook: For writing and running the analysis 

- Streamlit: To build and deploy an interactive dashboard
## Data Cleaning & Preprocessing

Several preprocessing steps were applied to make the data analysis-ready:

- Category Mapping: Merged similar job titles into unified categories:

  "Data Science", "Data Science Analytics Manager", etc. → Data Science

  "Machine Learning Engineer", "Machine Learning Specialist" → Machine Learning

  "Data Science Internship", "Data Science Internship in Pune" → Data Science Internship

- Text Cleaning:

  Converted text to lowercase

  Removed extra spaces and unwanted characters

- Experience Grouping:

  Transformed experience ranges into three levels: Junior, Mid-level, Senior


-  Missing Values Handling:

   Cleaned and imputed missing data where needed, including removing symbols $ etc
   
## Dashboard Overview
The dashboard below displays visual insights from the cleaned dataset.
![image](https://github.com/user-attachments/assets/b7aaaf81-8b0f-4092-ad10-93ebcf6eb1dd)


## Key Insights
This analysis dives into the in-demand skills, tools, and technologies in the current data science job market. Here are the key takeaways:

🧠 *Top Data Science Skills*
- Deep Learning (26.7%) leads the charge, highlighting the growing focus on AI-powered solutions.

- NLP (20%) and Computer Vision (20%) are also highly sought after, showing a rise in the demand for technologies that process unstructured data.

- Machine Learning (13.3%) and Data Analytics (13.3%) continue to be foundational, reflecting the core skills needed in data science.

- Big Data (6.7%) is less frequently mentioned, suggesting a shift toward cloud-native or more lightweight solutions.

💻 *Popular Programming Languages*
- Python dominates with a massive 79%, reinforcing its position as the primary language for data science.

- Java (13%), R (5%), and SQL (3%) still maintain relevance, especially in enterprise or legacy systems.

🛠️ *Most Mentioned Tools & Frameworks*
- Tools like Hive (16%), QlikView (12%), and Excel (12%) top the list, showing a strong demand for data querying, visualization, and reporting tools.

- Big data and cloud technologies like Spark, Hadoop, Cassandra, and Azure are also prominent.

- Other tools like GitHub, Docker, and MongoDB reflect the growing importance of version control, containerization, and NoSQL databases.

☁️ *Skills Word Cloud*
The word cloud emphasizes essential technical skills like Machine Learning, Logistic Regression, Neural Networks, and Python, while also highlighting the importance of data quality. Soft skills like communication are also present, underscoring the interdisciplinary nature of data science roles that require both technical and interpersonal skills.



## Conclusion
The analysis reveals key trends in the data science job market, emphasizing the growing demand for deep learning, NLP, and computer vision skills. Python remains the dominant programming language, while traditional tools like Excel and newer technologies like Spark and Docker are crucial in the industry.

The data also highlights the need for both technical proficiency and strong communication skills, suggesting that future data scientists must focus on a blend of expertise in AI tools and the ability to work in interdisciplinary teams.


