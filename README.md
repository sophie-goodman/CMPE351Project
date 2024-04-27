# Harnessing Review Insights: Identifying key aspects in customer feedback to highlight descriptive features

## Description
This project utilizes Natural Language Processing to analyze Airbnb reviews for sentiment and geospatial patterns in Toronto. The goal is to enhance Airbnb guest experiences by identifying key aspects of guest reviews that influence satisfaction.

## Prerequisites
- A Google account
- Access to Google Colab
- Basic knowledge of Python programming

## Installation
1. **Download the Required Datasets**:
   - Visit the Inside Airbnb website.
   - Navigate to the Toronto section and download the `listings.csv` and `reviews.csv` files.

2. **Google Drive Setup**:
   - Log into your Google Drive account.
   - Create a new folder named `CMPE372Project`.
   - Upload the downloaded `listings.csv` and `reviews.csv` files to this folder.

## Running the Code
1. **Open Google Colab**:
   - Visit [Google Colab](https://colab.research.google.com/).
   - Sign in with your Google account.

2. **Mount Google Drive**:
   - Open a new notebook.
   - Run the following code to mount your Google Drive:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
   - Follow the prompts to authorize access to your Google Drive.

3. **Access the Notebook**:
   - Upload the `.ipynb` notebook provided in this repository to Google Colab.
   - Move the notebook to the directory where you have your data, or adjust the file paths in the notebook to match your Google Drive structure.

4. **Install Required Libraries**:
   - Ensure your notebook installs any required libraries using pip. Add cells at the beginning of your notebook to install libraries as needed, for example:
     ```python
     !pip install pandas spacy geopandas matplotlib
     ```
   - You might need to restart the runtime in Google Colab after installing libraries for the first time (`Runtime` > `Restart runtime`).

5. **Run the Notebook**:
   - Execute the cells after sequentially in the notebook to analyze the Airbnb data 

## Usage
This project is intended for educational purposes and to provide insights to Airbnb hosts about guest preferences in Toronto. By understanding sentiment and geospatial trends, hosts can improve their listings and guest satisfaction.

## Support
For support, please open an issue in the GitHub repository or contact one of the contributors via email.

## Authors and acknowledgment
- Dilly Ejeh : 18ccte@queensu.ca
- Aaliyah Chang : 19aoc2@queensu.ca
- Sophie Goodman : 19slg7@queensu.ca
- Maahum Khan : 20mk@queensu.ca		
- Ishami Rulinda : 18ir@queensu.ca


