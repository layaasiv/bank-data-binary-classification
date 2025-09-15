# Binary Classification of Bank Marketing Data 

This project was completed for a Kaggle competition. The dataset contains information about clients of a Portuguese banking institution. The goal is to predict whether a client will subscribe to a bank term deposit (variable ```y```). The data was obtained from a direct marketing campaign, and each entry corresponds to a single client.

Here is a summary of all the features present in the dataset:

* ```age```: Age of the client (numeric)
* ```job```: Type of job (categorical: "admin.", "blue-collar", "entrepreneur", etc.)
* ```marital```: Marital status (categorical: "married", "single", "divorced")
* ```education```: Level of education (categorical: "primary", "secondary", "tertiary", "unknown")
* ```default```: Has credit in default? (categorical: "yes", "no")
* ```balance```: Average yearly balance in euros (numeric)
* ```housing```: Has a housing loan? (categorical: "yes", "no")
* ```loan```: Has a personal loan? (categorical: "yes", "no")
* ```contact```: Type of communication contact (categorical: "unknown", "telephone", "cellular")
* ```day```: Last contact day of the month (numeric, 1-31)
* ```month```: Last contact month of the year (categorical: "jan", "feb", "mar", …, "dec")
* ```duration```: Last contact duration in seconds (numeric)
* ```campaign```: Number of contacts performed during this campaign (numeric)
* ```pdays```: Number of days since the client was last contacted from a previous campaign (numeric; -1 means the client was not previously contacted)
* ```previous```: Number of contacts performed before this campaign (numeric)
* ```poutcome```: Outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")
* ```y```: The target variable, whether the client subscribed to a term deposit (binary: "yes", "no")

I applied a linear model, decision tree, random forest and gradient boosting models to predict whether clients will subscribe to a term deposit using this data. 

I achieved a final accuracy of 0.96.
