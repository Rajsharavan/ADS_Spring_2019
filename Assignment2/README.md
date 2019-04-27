# Feature Engineering and Exploratory Data Analysis
*******************************************************
The goal of this exercise is to build a dataset with features that can be used to analyze hiring trends in Fintech in the 24 largest banks by market cap in the United States. 

Primary tasks include:
1. Aggregation of multiple datasets into a single dataset

2. Build a list of 100 keywords in Fintech and assign Fintech categories to each keyword

3. Tag if a job is a fintech related job or not

4. Assign the categories as features to each job posting if it is a fintech related job

5. Analyze the final dataset and document insights.

### Claat
https://codelabs-preview.appspot.com/?file_id=1cwr2eN0y1F-XP3N0C8Y8hvvFrrLdNRP2uc0JpqfkvZ0#0

### Before execution install below libraries
•	pandas

•	nltk

•	boto3

•	xlwt

### Dataset
•	Final_Words.csv - List of final words

•	Cluster.csv - Clusters of different banking sectors and words belonging to each cluster

### Instruction to exceute files
#### Step 1 (Part 1):

Description_Final_S3.ipynb - File to convert all the CSV files of 12 Banking Companies into a standard format with four columns i.e. Job Urls, Job Title, Description and Bank Name.

#### Step 2 (Part 2):
Formed clusters of different banking sectors and grouped some fintech words under these clusters

#### Step 3 (Part 3):

Classifier_Final_S3.ipynb - Performed feature engineering to add 3 features 

•	Focused Area pertaining to the technology

•	Banking Sector (Cluster)

•	Job Category (Fintech/Non-Fintech)

#### Step 4 (Part4):
Performed detailed analysis and included demographics in the claat document.

#### Step 5 (Part 5):
Creating a pipeline with airflow and dockerize the entire pipeline.

