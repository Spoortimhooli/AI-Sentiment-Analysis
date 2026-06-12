# AI-Powered Sentiment Analysis Application

## Project Overview

This project is an AI-powered Sentiment Analysis Application developed using Python, Streamlit, Pandas, and Hugging Face Transformers. The application analyzes customer reviews and predicts their sentiment using a pre-trained DistilBERT transformer model.

The system supports both single-review analysis and bulk sentiment analysis through CSV file uploads.

---

## Features

* Analyze individual customer reviews
* Upload CSV datasets for bulk sentiment analysis
* Display sentiment labels and confidence scores
* Visualize sentiment distribution using charts
* Download processed datasets with sentiment predictions

---

## Technologies Used

* Python
* Streamlit
* Pandas
* Transformers (Hugging Face)
* DistilBERT Multilingual Sentiment Model

---

## Project Structure

AI_Sentiment_Analysis_Project/

├── app.py

├── requirements.txt

├── README.md

├── AI_Sentiment_Analysis_Project_Report.pdf

├── screenshots/

└── dataset/

---

## Installation

Install the required libraries:

pip install -r requirements.txt

---

## Running the Application

Run the following command:

streamlit run app.py

The application will open in your browser.

---

## How to Use

### Single Review Analysis

1. Open the application.
2. Enter a customer review.
3. Click "Analyze sentiment".
4. View the predicted sentiment and confidence score.

### CSV Dataset Analysis

1. Upload a CSV file containing a column named:

review_text

2. Click "Analyze the entire dataset".
3. View sentiment predictions.
4. Download the processed dataset.

---

## AI Model Used

Model Name:

lxyuan/distilbert-base-multilingual-cased-sentiments-student

This pre-trained transformer model supports multilingual sentiment classification and provides efficient sentiment prediction.

---

## Sample Output

Input:

The service was amazing and I loved it.

Output:

Sentiment: Positive

Confidence Score: 0.99

---

## Future Enhancements

* Emotion Detection
* Social Media Sentiment Analysis
* Dashboard Analytics
* Cloud Deployment
* Multilingual Reporting

---

## Author

Spoorti Hooli

Artificial Intelligence Internship Project
# AI-Sentiment-Analysis
