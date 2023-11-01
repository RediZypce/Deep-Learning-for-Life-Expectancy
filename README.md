# Predicting Life Expectancy with Deep Learning
![image](https://github.com/RediZypce/Deep-Learning-for-Life-Expectancy/assets/109640560/300c873f-b6ee-4237-b45b-84ecfbf49c21)

### Project Description
This project aims to predict life expectancy using a deep learning model. It utilizes a dataset containing various features that can impact life expectancy and follows a structured workflow to preprocess the data, build a deep learning model, and visualize the results. [Link to Jupyter Notebook](Predicting_Life_Expectancy_With_Deep_Learning.ipynb)

### Dataset
The dataset used in this project, "life_expectancy.csv," contains various factors that can impact life expectancy. These factors include information about countries, years, health-related metrics, economic indicators, and more.

### Project Structure
The project is organized into the following sections within the Jupyter Notebook:

#### 1. Data Exploration

Initial exploration of the dataset, including data types, missing values, and summary statistics.
Visualization of the correlation matrix using a heatmap.
Histograms of numerical columns for data visualization.

#### 2. Data Preprocessing

Data preparation steps, including dropping unnecessary columns and performing one-hot encoding on categorical variables.
Splitting the dataset into training and testing sets.
Scaling the numeric features using StandardScaler.
Preparing the target variable ("Life expectancy").

#### 3. Model Building

Construction of a deep learning model using the Keras library.
Compilation of the model with relevant loss functions and evaluation metrics.
Training of the model with the training data.

#### 4. Model Evaluation

Evaluation of the deep learning model's performance using the testing dataset.
Calculation and display of Mean Squared Error (MSE) and Mean Absolute Error (MAE) results.

#### 5. Visualizations

Presentation of three visualizations: a histogram of life expectancy, a scatter plot of life expectancy vs. GDP, and a box plot of life expectancy by "Status."

#### 6. Feature Selection

Application of feature selection using the SelectKBest method with f_regression scoring.

#### 7. Hyperparameter Tuning

Tuning of hyperparameters for the model using the Keras Tuner library. Tuned hyperparameters include the number of units in the hidden layer and the learning rate.
Display of the best hyperparameters and the corresponding MSE and MAE results.
Training of the best model with the tuned hyperparameters.

#### 8. Training History Plot

Visualization of the training history of the best model, showing training and validation loss across epochs.

#### 9. Prediction

Demonstration of making predictions with the trained model. A sample prediction is shown using new data.

### Usage
Clone this repository to your local environment:

bash
Copy code
git clone https://github.com/your-username/predicting-life-expectancy.git
Install the required libraries by running the following command:

bash
Copy code
pip install -r requirements.txt
Upload the dataset, "life_expectancy.csv," to the repository.

Open the Jupyter Notebook, "Predicting_Life_Expectancy.ipynb," in your Jupyter Notebook environment to execute and explore the project.


### Requirements
Python 3
Jupyter Notebook
Libraries specified in Jupyter Notebook

