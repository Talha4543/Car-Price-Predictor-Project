# Car-Price-Predictor-Project
Car Price Predictor Project Report
----------------------------------

This report provides a detailed overview of the Car Price Predictor project, based on the GitHub repository provided.

### Project Aim and Overview

The main goal of this project is to build a machine learning model that can **predict the selling price of a used car**. The prediction is based on several key factors, including the car's company, model, year of purchase, fuel type, and kilometers driven. The project utilizes a dataset scraped from Quikr.com.

### Technical Stack and Tools

The project is built using a combination of data science and web development technologies:

*   **Languages:** Python
    
*   **Libraries:**
    
    *   **Pandas:** For data manipulation and analysis.
        
    *   **NumPy:** For numerical operations.
        
    *   **scikit-learn:** To build and train the machine learning model.
        
    *   **Flask:** A micro-web framework used to create the web application interface for the predictor.
        
*   **Environment:** Jupyter Notebook was used for data analysis and model building.
    

### Project Workflow

The project follows a standard machine learning pipeline:

1.  **Data Scraping and Cleaning:** The initial dataset was scraped from Quikr.com. The data was "super unclean" and required significant cleaning and preprocessing to be usable for the model.
    
2.  **Exploratory Data Analysis (EDA):** The cleaned data was analyzed to understand the relationships between different features (e.g., fuel type, age, and kilometers driven) and the car's price.
    
3.  **Model Building:** A **Linear Regression** model was chosen and trained on the preprocessed data. The model achieved a high R² score, indicating a good fit and accuracy in its predictions.
    
4.  **Web Application:** A web application was built using the Flask framework. This application provides a user-friendly interface where users can input car details and receive an instant price prediction.
    

### Key Features

*   **User-friendly Interface:** The web application allows users to easily select car details from drop-down menus and enter the kilometers driven.
    
*   **Instant Predictions:** The application provides an instant price prediction after the user clicks the "Predict Price" button.
    
*   **Demonstration:** The repository includes images and a video demonstrating the project's functionality.
    

### How to Use

To run this project, you need to:

1.  Clone the repository from GitHub.
    
2.  Install the required Python packages listed in the requirements.txt file.
    
3.  Run the application.py file to start the Flask web server.
