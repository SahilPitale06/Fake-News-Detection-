# Fake News Detection

This repository contains the code and resources for a fake news detection project developed as a mini project during the 6th semester. The project aims to classify news articles as genuine or fake using machine learning techniques.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributors](#contributors)
- [License](#license)

## Overview

The proliferation of fake news has become a significant concern in today's digital age. This project utilizes Natural Language Processing (NLP) and machine learning algorithms to detect fake news based on the content of news articles. The system is built using Python and Jupyter Notebook, with a web interface implemented using Flask.

## Dataset

The dataset used for this project is `fakeNews1.csv`, which contains labeled news articles. Each entry includes:

- `title`: The title of the news article.
- `text`: The main content of the article.
- `label`: Indicates whether the news is fake (`1`) or real (`0`).

## Installation

To run this project locally, ensure you have Python installed. Then, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SahilPitale06/Fake-News-Detection-.git
   cd Fake-News-Detection-
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

   *Note: If `requirements.txt` is not available, manually install the necessary packages:*

   ```bash
   pip install numpy pandas scikit-learn flask
   ```

## Usage

1. **Run the Flask application:**

   ```bash
   python app.py
   ```

2. **Access the web interface:**

   Open a web browser and navigate to `http://127.0.0.1:5000/`. You can input news article text to check whether it's classified as fake or real.

## Model Training

The model training process is documented in the Jupyter Notebook `fake news.ipynb`. It includes:

- Data preprocessing: Cleaning and preparing the text data.
- Feature extraction: Converting text data into numerical features using techniques like TF-IDF Vectorization.
- Model selection: Training machine learning models such as Logistic Regression and Naive Bayes.
- Model serialization: Saving the trained model (`model.pkl`) and vectorizer (`vector.pkl`) for future use.

## Evaluation

The trained model's performance is evaluated using metrics like accuracy, precision, recall, and F1-score. Detailed evaluation results and visualizations are available in the Jupyter Notebook.

## Contributors

- [Sahil Pitale](https://github.com/SahilPitale06)
- [Sanket Pawar](https://github.com/Sankkkett)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

*Note: This README provides a general overview. For detailed code explanations and insights, refer to the Jupyter Notebook and Python scripts in the repository.*
