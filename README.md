# Fake News Detection

## Overview

This project aims to analyze and classify news articles as either "fake" or "true" using various machine learning algorithms. We will use Logistic Regression, Random Forest, and Decision Tree classifiers to build and evaluate our models. The dataset comprises two CSV files: one containing fake news articles and the other containing true news articles.

## Project Structure

```
fake-news-detection/
│
├── data/
│   ├── fake_news.csv
│   └── true_news.csv
│
├── notebooks/
│   └── fake_news_analysis.ipynb
│
├── README.md
└── requirements.txt
```

## Files

- `data/fake_news.csv`: Contains fake news articles.
- `data/true_news.csv`: Contains true news articles.
- `notebooks/fake_news_analysis.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `README.md`: This readme file.
- `requirements.txt`: List of dependencies required to run the notebook.

## Setup

1. **Clone the Repository**: Clone this repository to your local machine.
   ```bash
   git clone <repository-url>
   ```

2. **Upload to Colab**: Open Google Colab and upload the `fake_news_analysis.ipynb` notebook along with the `data` folder containing the CSV files.

3. **Install Dependencies**: Install the required dependencies by running the following command in a Colab cell:
   ```python
   !pip install -r requirements.txt
   ```

## Data Description

### fake_news.csv

| Column Name | Description                     |
|-------------|---------------------------------|
| id          | Unique identifier for each news |
| title       | Title of the news article       |
| text        | Full text of the news article   |
| subject     | Subject category of the news    |
| date        | Publication date of the news    |

### true_news.csv

| Column Name | Description                     |
|-------------|---------------------------------|
| id          | Unique identifier for each news |
| title       | Title of the news article       |
| text        | Full text of the news article   |
| subject     | Subject category of the news    |
| date        | Publication date of the news    |

## Steps in the Notebook

1. **Import Libraries**: Import necessary libraries such as pandas, numpy, sklearn, etc.
2. **Load Data**: Load the datasets from the CSV files.
3. **Data Preprocessing**:
    - Combine the datasets and create a label column.
    - Handle missing values.
    - Perform text preprocessing (e.g., removing stop words, punctuation).
4. **Feature Extraction**: Convert text data into numerical features using techniques like TF-IDF Vectorization.
5. **Split Data**: Split the data into training and testing sets.
6. **Model Training**:
    - Logistic Regression
    - Random Forest
    - Decision Tree
7. **Model Evaluation**: Evaluate the models using metrics such as accuracy, precision, recall, and F1 score.
8. **Comparison of Models**: Compare the performance of the models and determine the best performing model.

## Usage

1. **Run the Notebook**: Execute each cell in the notebook sequentially to perform the fake news analysis.
2. **Model Predictions**: Use the trained models to make predictions on new data.
3. **Evaluation**: Evaluate and compare the performance of the models.

## Results

The results section in the notebook will contain the evaluation metrics for each model, including accuracy, precision, recall, and F1 score. The model with the best performance will be identified based on these metrics.

#Contributing
If you would like to contribute to this project, please follow these steps:

1.Fork the repository.
2.Create a new branch.
3.Make your changes.
4.Submit a pull request.



## License

This project is licensed under the MIT License.

---

Feel free to explore and contribute to this project. If you encounter any issues or have any suggestions, please open an issue on GitHub.

Happy coding!
