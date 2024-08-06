# DS_Industrial-Copper-Modeling_ML

The following project is the capstone project of GUVI DS course.

The python program is a ML algorith for prediction of copper selling price (Regression model) and status/outcome (Classification) of the problem.

First the data is imported and analysed. It is found that column header have spaces and are firstly renamed by replacing space with "_". Presence of invalid data in few columns are corrected and irrelevent columns are dropped. missing values are replaced with mode for categorical columns, mean for numerical values. Once all missing values are handeled we proceed with data type correction. Few new features are created and old ones are deleted. Outlers are removed EDA is performed and finally various regression and classification models are build.
