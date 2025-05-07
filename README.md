# The Real Truth: Fake News Detector 📰

A machine learning-powered web application that helps users identify potential fake news articles using Natural Language Processing (NLP) and a Naive Bayes classifier.

## Features

- **Real-time News Analysis**: Input any news text and get instant predictions
- **Interactive UI**: Clean and user-friendly interface built with Streamlit
- **Model Performance Metrics**: View accuracy, confusion matrix, and classification reports
- **Analytics Dashboard**: Track prediction statistics and user feedback
- **Dataset Management**: Upload and manage custom training datasets
- **Educational Resources**: Learn about fake news detection and best practices

## Installation

1. Clone the repository:
```sh
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector
```

2. Install dependencies:
```sh
pip install -r requirements.txt
```

3. Run the application:
```sh
streamlit run app.py
```

## Project Structure

```
├── app.py                 # Main Streamlit application
├── model_utils.py         # ML model utilities and preprocessing
├── db_utils.py           # Database operations
├── init_database.py      # Database initialization
├── data/                 # Dataset directory
│   └── fake_or_real_news.csv
└── .streamlit/           # Streamlit configuration
```

## Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python
- **Machine Learning**: scikit-learn, NLTK
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Database**: SQLAlchemy

## How It Works

1. **Text Preprocessing**:
   - Lowercase conversion
   - Punctuation removal
   - Stopword removal
   - Word stemming

2. **Feature Extraction**:
   - TF-IDF Vectorization
   - Bag-of-words representation

3. **Classification**:
   - Multinomial Naive Bayes
   - Probability-based predictions

## Usage

1. Launch the application and navigate to http://localhost:8501
2. Upload your dataset or use the default one
3. Train the model using the sidebar
4. Input news text in the prediction tab
5. View analytics and manage datasets in their respective sections

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Contact

For questions or feedback, please open an issue on GitHub.
