Box Office Revenue Prediction Model

A machine learning model that predicts movie box office revenues using data scraped from the Rotten Tomatoes website and provides a user-friendly interface through Python widgets.

Project Overview

This project aims to predict movie box office revenues using data collected from Rotten Tomatoes. Additionally, a simple graphical user interface (GUI) has been developed using Python widgets, allowing users to easily test the prediction model.

Features

	•	Web Scraping:
Data such as movie genres, cast, scores, and release dates were scraped from Rotten Tomatoes using BeautifulSoup.
	•	Data Cleaning and Engineering:
The scraped data was cleaned, and feature engineering processes were applied.
	•	Machine Learning Model:
Algorithms like XGBoost and linear regression were utilized to predict box office revenues.
	•	Widget-Based Interface:
Python widgets were used to create a simple GUI that allows users to test model outputs easily.

Technologies Used

	•	Programming Language: Python
	•	Libraries:
	•	Data Processing: Pandas, NumPy
	•	Web Scraping: BeautifulSoup, Requests
	•	Data Visualization: Matplotlib, Seaborn
	•	Machine Learning: Scikit-learn, XGBoost
	•	Interface Development: ipywidgets, tkinter, or PyQt
	•	Tools: Jupyter Notebook

Web Scraping Process

	•	Data such as genres, cast, Rotten Tomatoes Audience Score, and release dates were scraped using BeautifulSoup.
	•	The scraped data was stored in .csv format.

Data Cleaning and Modeling Process

	•	Missing and inconsistent data were cleaned, and features were refined.
	•	Machine learning models were used to predict box office revenues.

Interface (GUI) Features

	•	Input Movie Details:
Users can input details such as movie genre, Rotten Tomatoes Audience Score, number of cast members, and more to generate predictions.
	•	Live Predictions:
Prediction results update dynamically as input values are adjusted.
	•	Ease of Use:
Simple and user-friendly design.

Results

	•	The model demonstrated high accuracy in predicting box office revenues.
	•	The Python widget-based interface enables users to easily test the model.

Future Improvements

	•	A more advanced GUI can be created using tools like PyQt.
	•	Dynamic graphs to visualize prediction results can be added.

Acknowledgments

	•	Thanks to Rotten Tomatoes for providing the data used in this project.
	•	Special thanks to the community for enabling the integration of Python widgets into the project to create a user-friendly interface.

 created by azadhalhalli
