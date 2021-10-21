# IBM Data Science Professional Certificate 

---

## Applied Data Science Capstone Project
### Prerequisite:
```
Python, Jupyter Notebook, Db2 on IBM Cloud
```
### Summary:
In April 1961, Human civilization first encountered traveling to space. Fast forward to a half-century later, various companies are now aiming for commercial space travel and SpaceX is one of them. This company’s goal is to make commercial space travel more affordable for everyone. SpaceX can launch rockets in a relatively high cost-efficient manner by reusing the first stage of the rocket Falcon 9 (the first orbital-class rocket capable of re-flight). 

In this project, a company named Space Y is planning to compete with SpaceX. The goal is to find the cost of each launch. And this cost primarily depends on the successful landing of the first stage. Hence, a classification analysis on whether the first stage would be successful or not is present here along with various exploratory and visual analytics of the SpaceX Falcon 9 Launch Dataset.

### Data Collection:
The dataset was collected into two stages:

1. **By using SpaceX API:** This API will provide data about launches, including information about the rocket used, payload delivered, launch specifications, landing specifications, and landing outcome. The goal is to use this data to predict whether SpaceX will attempt to land a rocket or not.


2. **By web-scraping Falcon 9 and Falcon Heavy launches Wiki Page:** This will provide launch data for Falcon 9.

### Data Wrangling:
After collecting the dataset, it was stored in a CSV file. Later on, the dataset was filtered by removing irrelevant information, replacing missing values, converting categorical variables to one-hot encoding, typecasting all numeric variables into the correct type, and finally, creating a Landing Outcome Label for the predictive analysis. 

### Exploratory Data Analysis:
EDA was performed on the dataset to learn more about the important factors of a successful landing. It was done by utilizing two approaches:
1. **Visualization using Pandas Dataframe and Seaborn**
2. **SQL query using Db2 Database**

### Interactive Visual Analytics:
With the help of interactive visual analytics, users can understand the patterns and insights of the data in an effective and faster manner. In order to create this, Folium and Plotly Dash were used.
- **Folium:** It was used to create a Map describing the proximities i.e., the distance from the nearest railway, coastline, highway, and locality or city of different launch sites, and establish a pattern among them. Which will ultimately help to choose future locations for new launch sites. 


- **Plotly Dash:** Often times for stakeholders, an interactive dashboard usually tells a more appealing story about the dataset rather than a notebook filled with codes of mathematical or statistical plots. 

### Predictive Analysis:
It is done by implementing various classification models to determine whether the outcome of a launch would be successful or not. After evaluating the models upon their performances, a best model is chosen for the task.


