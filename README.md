 #COMPANY: CODTECH IT SOLUTIONS

*NAME*:Kumkum C. Bhanarkar

*INTERN ID*: CT08DN279

*DOMAIN*: BIG DATA

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

For this task, I worked on cleaning a large dataset using PySpark, Apache Spark’s Python API, which is built to handle big data efficiently. The aim was to tackle common real-world issues like missing values and duplicate records, which can affect the quality of any data analysis or machine learning work.

I started by setting up PySpark in Google Colab, then created a SparkSession, which is needed to run any operations on Spark. I loaded the dataset (converted to CSV format) using PySpark’s read.csv() method, with schema inference enabled to automatically detect data types.

Next, I explored the structure of the dataset and checked each column for null or empty values. I used a Spark expression that scanned all columns and showed me how many missing values existed in each. To keep things simple and ensure clean data, I used the dropna() method to remove rows with null values. While in real-world projects you might fill these gaps with averages or default values, for this internship task I focused on maintaining clarity.

After cleaning the missing data, I also removed duplicate records using dropDuplicates(). This is important because duplicates can skew results and lead to misleading insights. Once the data was cleaned, I previewed it using show() and then saved the cleaned version as a new CSV file using PySpark’s write.csv() function.

Overall, this task gave me a solid understanding of how to clean and prepare large datasets using PySpark. Unlike tools like Excel or Pandas, which work well for small data, PySpark is designed to scale and can handle millions of records across multiple machines. I learned not just the technical methods, but also the importance of thinking critically about data quality, especially when preparing for deeper analysis or machine learning.



#Output
<img width="1920" height="647" alt="Image" src="https://github.com/user-attachments/assets/9d0bab5b-83c1-4002-9e24-8318a02ce729" />
<img width="1920" height="154" alt="Image" src="https://github.com/user-attachments/assets/a15a39ca-5f3c-45fe-8556-78fb6ef88df1" />
<img width="1920" height="312" alt="Image" src="https://github.com/user-attachments/assets/16c44767-19dd-4b94-8b32-fc902ada6fa3" />
