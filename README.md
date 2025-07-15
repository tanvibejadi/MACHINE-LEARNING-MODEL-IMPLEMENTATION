# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: TANVI BEJADI

INTERN ID: CT04DH2184

DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

Project Description:
This project is about creating a machine learning model that can predict outcomes based on data. In this case, we built a model that can classify whether a breast tumor is cancerous (malignant) or not (benign). We used Python programming and a few popular tools from the field of data science. The model was created using a classification algorithm and was tested for how well it performs on real-world data.

Platform and Editor Used:
We used Jupyter Notebook to write and run our code. Jupyter is a tool that lets you write Python code and explanations in the same place. It is a browser-based tool, meaning it runs in your web browser but uses your computer's Python installation. It is commonly used by data scientists and students because it allows easy testing, documentation, and data visualization.

The notebook was opened using the Command Prompt (CMD) on a Windows computer. First, we navigated to the folder where the notebook was saved, and then we ran the command jupyter notebook to launch the interface.

Tools and Libraries Used:
We used the following tools (called libraries in Python):

NumPy: Used for working with numbers and arrays.

Pandas: Helps to load and work with tabular data (like rows and columns).

Matplotlib: A library used to draw graphs and plots.

Scikit-learn: The main machine learning library used to build and test the model.

All of these tools are free and widely used in machine learning projects.

Working Procedure:
Here’s how the project was done, step by step:

Load the Dataset:
We used a built-in dataset from Scikit-learn called the Breast Cancer Wisconsin dataset. It includes information about tumors, such as size, shape, and texture.

Explore the Data:
We viewed the data using Pandas to understand what kind of information it has — 30 input features and 1 target label (0 = malignant, 1 = benign).

Split the Data:
The data was split into two parts — one for training the model (80%) and one for testing it (20%). This helps us see how well the model can perform on new, unseen data.

Build the Pipeline:
We used a pipeline to organize our steps. First, we scaled the data using StandardScaler to ensure all values are in the same range. Then we trained a Random Forest Classifier, which is a model made of many decision trees.

Train the Model:
The model was trained using the training data.

Make Predictions:
After training, the model made predictions on the test data.

Evaluate the Model:
We checked how accurate the predictions were using:

Accuracy score: The percentage of correct results.

Confusion matrix: Shows correct vs. incorrect predictions.

ROC curve and AUC score: Graph that shows how well the model separates the two classes.

Cross-validation: The model was tested using 5-fold validation to confirm it performs consistently.

Applications of This Project:
This kind of machine learning model can be useful in many real-life situations:

Healthcare: Predict if a person has a disease or not based on test results.

Banking: Detect if a transaction is fraud or not.

E-commerce: Predict if a customer will buy a product.

Education: Predict student performance based on their activity.

Security: Detect spam messages or fake login attempts.

Conclusion:
This project shows a complete machine learning workflow — from loading data to making predictions and evaluating results. It uses simple tools and code that can be reused for many other projects. The same process can be applied to different kinds of data to solve different problems.

#OUTPUT

<img width="1784" height="270" alt="Image" src="https://github.com/user-attachments/assets/e770a457-d335-407f-9e87-4b2b7da2ed52" />

<img width="685" height="331" alt="Image" src="https://github.com/user-attachments/assets/b3e3203f-51bd-4da2-be43-15c085ca09b0" />

<img width="958" height="903" alt="Image" src="https://github.com/user-attachments/assets/5ba8820a-436e-4706-9543-04716a4f075c" />

<img width="902" height="863" alt="Image" src="https://github.com/user-attachments/assets/e298b395-a953-44ba-ac65-dc144b2e47bc" />
