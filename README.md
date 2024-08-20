# Lead-Scoring-Case-Study

## Problem Statement: 
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone. A typical lead conversion process can be represented using the following funnel:

Lead Conversion Process - Demonstrated as a funnel As you can see, there are a lot of leads generated in the initial stage (top) but only a few of them come out as paying customers from the bottom. In the middle stage, you need to nurture the potential leads well (i.e. educating the leads about the product, constantly communicating etc. ) in order to get a higher lead conversion.

X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.
## Objective
BDevelop a logistic regression model to assign a lead score between 0 and 100 to each lead. This score will help the company prioritize potential leads, with higher scores indicating "hot" leads that are more likely to convert, and lower scores indicating "cold" leads that are less likely to convert.

In addition, the company has outlined several potential challenges that your model should be flexible enough to accommodate in the future. These challenges are detailed in a separate document. You'll need to address these issues using your logistic regression model and include your findings in the final PowerPoint presentation, along with your recommendations.
## Steps Followed
- Reading Data: Load the dataset and inspect its structure, including the features and the target variable.

- Cleaning Data: Handle missing values, remove duplicates, and ensure data consistency for accurate analysis.

- Exploratory Data Analysis (EDA): Explore and visualize the data to understand patterns, distributions, and relationships between variables.

- Creating Dummy Variables: Convert categorical variables into a format suitable for modeling by creating dummy variables.

- Splitting Data into Training and Testing Sets: Divide the data into training and testing sets to evaluate model performance on unseen data.

- Building the Model: Develop a logistic regression model using the training data to predict lead conversion.

- Making Predictions: Use the trained model to predict the probability of conversion for each lead.

- Model Evaluation: Assess the model's performance using metrics such as accuracy, precision, recall, and F1-score.

- ROC Curve Analysis: Plot the ROC curve and calculate the AUC to evaluate the model’s ability to discriminate between classes.

- Predictions on Test Set: Apply the model to the test set to predict lead scores and compare them with actual outcomes.

- Precision-Recall Analysis: Analyze precision and recall to understand the trade-offs between identifying true positives and avoiding false positives.
## Details of files given
- Lead Score Case Study.ipynb: The Jupyter notebook containing the code and data analysis.
- Assignment Subjective Questions.pdf: A document with responses to subjective questions.
- Lead Score Case Study.pdf: The final presentation summarizing the project.
- Summary.pdf: A summary document outlining the key steps and outcomes of the Python file.









