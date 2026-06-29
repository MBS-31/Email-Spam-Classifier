# Email Spam Classifier

A Machine Learning-based Email Spam Classification web application that predicts whether an email/message is **Spam** or **Not Spam (Ham)**. The project uses Natural Language Processing (NLP) techniques and a trained machine learning model to classify text efficiently.

## Internship Project Details

- **Intern ID:** CITS1938
- **Name:** Madhav B Sheshwani
- **Project Name:** Email Spam Classifier
- **Project Duration:** 6 Weeks

## Project Overview

Email spam is a major issue in digital communication. This project helps identify unwanted or fraudulent emails automatically using Machine Learning and text processing techniques.

The application provides a simple web interface where users can enter an email message and instantly receive a prediction.

## Features

- Spam and Ham email classification
- User-friendly web interface
- Machine Learning-based prediction
- Fast and accurate results
- Flask-powered backend
- Responsive design using HTML and CSS

## Technologies Used

- Python
- Flask
- Scikit-learn
- HTML5
- CSS3
- Pickle
- Natural Language Processing (NLP)

## Project Structure

```
Email-Spam-Classifier/
│
├── app.py
├── train_model.py
├── spam_model.pkl
├── vectorizer.pkl
├── documentation.txt
├── README.md
│
├── templates/
│   └── index.html
│
├── static/
│   ├── style.css
│   └── download.jpg
│
└── screenshots/
```

## Installation

### Clone Repository

```bash
https://github.com/MBS-31/Email-Spam-Classifier Email-Spam-Classifier
```

### Install Dependencies

```bash
pip install flask scikit-learn pandas numpy
```

### Run Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Model Training

To train the model again:

```bash
python train_model.py
```

This generates:

- spam_model.pkl
- vectorizer.pkl

## Working Process

1. User enters an email/message.
2. The text is preprocessed.
3. The vectorizer converts text into numerical features.
4. The trained model predicts the category.
5. The result is displayed as:
   - Spam
   - Not Spam (Ham)

## Applications

- Email filtering systems
- Business communication platforms
- Personal email management
- Cybersecurity and phishing detection

## Future Enhancements

- Improve model accuracy
- Support multiple languages
- Email attachment analysis
- Cloud deployment
- Real-time spam monitoring

## Screenshots

Add project screenshots in the `screenshots` folder and include them here.

## Author

**Madhav B Sheshwani**

## Internship ID

**CITS1938**

## License

This project is created for educational and internship purposes.