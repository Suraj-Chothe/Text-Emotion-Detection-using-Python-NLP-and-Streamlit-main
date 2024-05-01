# Text-Emotion-Detection-using-Python-NLP-and-Streamlit
I have build a web application for Text emotion detection/ Text emotion classification using Streamlit and Python. In this project we will be taking text as an input and classifying that text into emotions like- joy, sadness, fear, neutral, anger, shame, etc. using  Natural Language Processing.

Steps for the Implementation :

1. Download the csv file from repo.

2. create  a jupyter notebook file inside the model folder for the preprocessing.

	1. Import Neccessary Libraries .
	
	2. download the neattext pakage .It is used for the cleaning and preprocessing data.Extract           emails,emojis,phone numbers,weblinks from text
			                          pip install neattext

	3. Remove user Handle, Stopwords.

	4. Split the data into input variable and target variable .

	5. Split the dataset into training and testing dataset .

	6. Try the dataset for various ML algorithms for checking the accuracy .

	7. Save the model which shows the higher accuracy using joblib .

3. Deployment of model using stramlit.
