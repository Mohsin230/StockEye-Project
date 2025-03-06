# StockEye

## Twitter sentiments analysis web application

StockEye - Twitter Sentiment Analysis for Stock Trends

# Description

StockEye is a Twitter sentiment analysis web application that collects tweets about stocks, analyzes their sentiment (positive, negative, neutral), and displays the results. This project provides insights into public opinion about specific stocks, which can be useful for investors.

# Technologies Used:

Python: Main programming language.

Tweepy: For accessing Twitter's API and fetching tweets.

TextBlob: For sentiment analysis of the tweets.

Flask: Web framework for running the web application.

HTML/CSS: Frontend for displaying the results.

JavaScript: For dynamic frontend interactions.

# Prerequisites:

Before running the project, ensure you have the following installed:

Python 3.x

pip (Python package installer)

Step-by-Step Instructions

# 1. Clone the repository:
Open your terminal in Visual Studio Code and clone the repository:


git clone https://github.com/LeronBergelson/StockEye.git
cd StockEye

or

git clone https://github.com/Mohsin230/StockEye-Project.git cd StockEye-Project

# 2. Install dependencies:
Make sure to install the necessary Python libraries. You can use a virtual environment for better management of dependencies.

First, install virtualenv (if not already installed):


pip install virtualenv

Then create a virtual environment:


python -m venv venv

Activate the virtual environment:

Windows:
bash
Copy

.\venv\Scripts\activate

Mac/Linux:
bash
Copy

source venv/bin/activate

Now install the required libraries:

bash
Copy

pip install -r requirements.txt

# 3. Set up Twitter API credentials:
To collect tweets, you need to access the Twitter API. Follow these steps to obtain your Twitter Developer credentials:

Go to Twitter Developer Portal and create a new app.

Get your API_KEY, API_SECRET_KEY, ACCESS_TOKEN, and ACCESS_TOKEN_SECRET.

Update the Twitter credentials in the code:

Open TweetStream.py

Replace placeholders with your actual credentials.

python
Copy

API_KEY = 'your_api_key'

API_SECRET_KEY = 'your_api_secret_key'

ACCESS_TOKEN = 'your_access_token'

ACCESS_TOKEN_SECRET = 'your_access_token_secret'

# 4. Run the application:
To run the web application, use the following command:

bash
Copy

python TweetStream.py

This script will start the Flask web application. You can access the app on your local server at:

cpp
Copy

http://127.0.0.1:5000
# 5. View the results:
Once the server is running, you can use the web interface to search for stocks by their ticker symbol (e.g., "AAPL" for Apple). The application will display the sentiment analysis results for recent tweets related to that stock.

# 6. Optional - Running Machine Learning Models:
If you're interested in running additional machine learning models (e.g., for more advanced sentiment analysis), you can modify and run the MachineLearning.py script. This script may include model training or evaluation steps.

# To execute it:

bash
Copy

python MachineLearning.py

Troubleshooting:

Missing Dependencies: Ensure all libraries are installed by checking the requirements.txt file.

Twitter API Issues: If you receive errors while accessing the Twitter API, verify that your credentials are correct and have the necessary access.

# Contributing:
Feel free to fork this repository, open issues, and contribute. Pull requests are welcome!
