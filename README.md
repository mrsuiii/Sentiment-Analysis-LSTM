# Amazon alexa 5 class sentiment classifier
This project builds a classifier that predicts the rating of Amazon Alexa product reviews, based on text input (user reviews). The model categorizes reviews into 5 classes (ratings 1 through 5), helping to analyze overall sentiment and user satisfaction regarding Alexa products.

## Library Requirements
 - Tensorflow
 - NLTK
 - Pandas
 - Numpy
 - Scikit-learn
 - Matplotlib
 - Seaborn
 

## Getting Started

This will help you understand how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

## Installation Steps

### Option 1: Installation from GitHub

Follow these steps to install and set up the project directly from the GitHub repository:

1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to install the project.
   - Run the following command to clone the GitHub repository:
     ```
     git clone https://github.com/mrsuiii/Sentiment-Analysis-LSTM.git
     ```

2. **Create a Virtual Environment** (Optional but recommended)
   - It's a good practice to create a virtual environment to manage project dependencies. Run the following command:
     ```
     conda create -p <Environment_Name> python==<python version> -y
     ```

3. **Activate the Virtual Environment** (Optional)
   - Activate the virtual environment based on your operating system:
       ```
       conda activate <Environment_Name>/
       ```

4. **Install Dependencies**
   - Navigate to the project directory:
     ```
     cd [project_directory]
     ```
   - Run the following command to install project dependencies:
     ```
     pip install -r requirements.txt
     ```

5. **Run the Notebook**
   - Just run the notebook like usual

## Training Log

Below is an example of the training log for our model:

![Training Log](training_log.png)
