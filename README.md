# Impelox-tech-task

**Task 1**

**Employee-Salary-Prediction**

**🎯 Objective:**

Build a machine learning model to predict employee base salaries using the provided dataset. The goal is to perform data exploration, preprocessing, feature engineering, model building, and evaluation.

**🛠️ Built With:**

**Pandas** - Data manipulation and analysis

**Scikit-learn** - Machine learning library

**matplotlib, seaborn** - Data visualization

**📊 Data Exploration:**

Gain insights into the dataset by performing,

**Statistical Analysis:**   Uncover key features through univariate, bivariate, and multivariate analysis.

**Visualizations:**

**Histogram:**   Understand the distribution of each variable and identify if they are normally distributed.

**Heatmap:**     Measure the strength of relationships between variables, highlighting highly correlated features like Division and Department.

**Boxplot:**     Detect outliers in columns such as Base_Salary, Overtime_Pay, and Longevity_Pay.

**🛠️ Data Preprocessing:**

Prepare the dataset for model training using the following steps,

**Handling Missing Values:**   Utilize pandas' fillna method to fill missing values.

**Addressing Outliers:**    Apply capping methods to correct outlier values.

**Encoding Categorical Variables: **  Convert categorical values to numerical format using sklearn's LabelEncoder.

**Data Splitting:**    Split the dataset into training and testing sets with sklearn's train_test_split.

**🔍 Feature Engineering:**

Engineer features to enhance model performance, focusing on [Base_Salary] and other relevant features, for improve our model performance.

**🧩 Model Building:**

Experiment with various machine learning algorithms to identify the best-performing model,

**Linear Regression:**   Achieved the highest accuracy with sklearn's LinearRegression.

MSE: 0.0095,

R²: 0.9999

**Decision Tree:**   Implemented using sklearn's DecisionTreeRegressor.

MSE: 6350.4278,

R²: 0.6236

**Random Forest:**   Applied using sklearn's RandomForestRegressor.

MSE: 2621.7932,

R²: 0.8446

**Gradient Boosting:**   Utilized sklearn's GradientBoostingRegressor.

MSE: 1234.7530,

R²: 0.9268

Linear regression got accuracy compared to other model perfomance.

--------------------------------------------------------------------------------------TASK 1-------------------------------------------------------------

**TASK 2**

**Retrieval-Augmented Generation With Langchain**

**🌟 Components of RAG with LangChain and OpenAI**


**🗂️ Document Retrieval System**

Indexing and Search,

**Tool:**   FAISS (Facebook AI Similarity Search)

**Purpose:**   Efficiently index your documents or knowledge base to enable quick retrieval based on queries.

LangChain Integration,

**Functionality:**   Seamlessly integrate the retrieval system with LangChain, allowing for easy querying and management of documents.

**🤖 Generative Model:**

OpenAI API,

**Model:** GPT-3 or GPT-4

**Access:**   Use the OpenAI API with your API key for the generative component.

Prompt Engineering,

**Strategy:**   Design prompts that effectively utilize the retrieved information to generate accurate and contextually relevant responses.
   
**🛠️ Workflow**

Query Handling,

**Step:** Upon receiving a query, use LangChain to first retrieve relevant documents or information.

Contextual Generation,

**Step:** Input the retrieved information into the generative model via the OpenAI API, guiding the model’s output to ensure accurate and relevant responses.

Response Generation,

**Outcome:**   The system produces a response that blends the retrieved information with the generative model's capabilities.

**🔍 Implementation Details**

**📦 Setting Up LangChain and OpenAI API**

	**LangChain Installation:**   Install LangChain and any necessary dependencies.

  	-	pip install langchain

	OpenAI API Key,

**Setup:** Configure your OpenAI API key in your environment or directly in your code to access OpenAI models.

**🏗️ Building the RAG Pipeline**

**Document Retrieval:**

o	Index your documents using a retrieval system.

o	Use LangChain to integrate and query this system.

**Generative Response:**

o	Use the retrieved documents to craft prompts.

o	Send these prompts to the OpenAI API and get the generated response.

**Handling Responses:**

o	Process and format the response as needed for your application.
----------------------------------------------------------------------------------------TASK 2-----------------------------------------------------------------
