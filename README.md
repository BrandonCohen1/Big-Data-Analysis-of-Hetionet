Using the Hetionet dataset, I used Python to connect to Neo4j and MongoDB with py2neo and pymongo respectively. 

With Neo4j, I was able to represent the data as a graph finding connections between diseases, compounds, anatomy location that the disease is located, and genes. 
With MongoDB, I was able to represent the data as documents allowing for fast searches. 
I answered two main questions using both Neo4j and MongoDB:
  1. What compounds treat or palliate a disease? With this information, where is the disease located (anatomy), and what gene is associated with the disease?
  2. From the current data, it is clear what compounds treat or palliate a disease, but are there other diseases that the compounds can treat or palliate that are hidden within the data?

With PySpark, I answered three questions:
  1. What compounds have the most associations with different genes? Given by compound id.
  2. What is the count of compounds that are associated with a certain number of diseases? For example, methotrexate is the only drug that is associated with 19 diseases.
  3. What are the top 5 gene associations of compounds using the compound name?

Cancer Diagnosis
I used a Random Forest and Logistic Regression model using the PySpark machine learning library to predict the diagnosis of cancer based on the measurements of a piece of skin.

Based on all of the big data techniques, the goal of this project was to find novel compounds that could be treated for new diseases as well as for cancer.
