# Machine-Learning-Roadmap
Starting from Basics, including mathematics required along the way. With an end goal of Learning LLMs(Transformers)


MLDLC- Machine Learning Development Life Cycle 

Steps in a MLDLC: 
1. Frame the Problem
2. Gathering Data
3. Data pre-processing
4. Exploratory Data Analysis
5. Feature Engineering and Selection
6. Model Training, Evaluation and Selection
7. Model Development
8. Testing 
9. Optimize


1. Frame the problem:
What are we trying to solve
Are we gonna use Supervised or un-supervised learning model,
What are we solving here.

2. Gathering Data:

Formats: 
CSV, 
API, 
Web-Scrapping
Database: Not allowed to run on ML
Data Warehouse: ETL
Spark(Clusters/Big Data)

3. Data Pre-processing:

Data could have noise, could have garbage in data, could not be clean.
Steps:
- Remove Duplicates
- Remove Missing Values
- Remove Outliers
- Scale Values(Standardisation)

4. EDA(Exploratory Data Analysis):

Try to learn the relation between Input and Output, and try to extract relations.
- Do Visualisations, 
- do analysis, 
- Uni-Variant Analysis.
- Bi-Variant Analysis
- Outlier Detection
- Balance the data(if data is not balanced basis the Input we have)


5. Feature Engineering and Selection:

Select the Input(Features), create features, change in features so that we get a better input. 
Then select the correct features, and find the correct ones.

6. Model Training, Evaluation and Selection:

Now bring in all algos and find the right one by training multiple algos, 
- Cramer based, Linear regression, 

Now Evaluate the results from the models and select the best one:
MVE: Regression
Accuracy: Classification
Etc.

Now Tune the parameters, 


Ensemble learning: 
Multiple ML algos are combined, by diff techniques to find the most powerful model

7. Model Development:

Now, create a file from the Model- Usually binary file (using pickle), convert it into API. Which creates the JSON, now using a form lets say the user send an input, now the model will be used to make a prediction, showing the JSON as response.

8. Testing:

Now do beta - testing 

9. Optimize:

Load-Balancing
Backup
Data management
Re-train(rotting)





**Tensors:**

-> 0-dimension (tensor) is called Scalar
[ndim] function gives us the number of dimension of the tensor.

[1,2,3,4] -> 1-D Tensor, nDim=1

Number of Axis = Rank = Dimensions of the Tensor

1-D Tensor = [1,2,3,4] = this vector has 4 Dimensions
> Every Vector is a Tensor, but not every Tensor  is a Vector


Google-Collab:  https://colab.research.google.com/drive/1jFBHbKSKyMPFZDvI6qynMZdV0tVBz-1T?authuser=0#scrollTo=hIJyPD7VXQjD

