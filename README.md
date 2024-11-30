# Fake News Classification Project

This project focuses on detecting fake news by leveraging machine learning. We trained a model using Gradient Boosting, a powerful ensemble learning method, to classify articles as either fake or true.

## Datasets
- **Fake.csv**: Contains fake news articles.
- **True.csv**: Contains authentic news articles.

The datasets are publicly available and can be downloaded from [here](https://drive.google.com/drive/folders/1ByadNwMrPyds53cA6SDCHLelTAvIdoF_?usp=sharing).

## Steps:
1. **Data Preprocessing**:
    - Combined both datasets into a single DataFrame.
    - Cleaned and prepared the text for training (e.g., removed special characters, tokenized words).

2. **Model Training**:
    - Used Gradient Boosting for classification.
    - Trained the model to distinguish between fake and true news articles.
    - Evaluated the model using metrics like accuracy, precision, recall, and F1-score.

3. **Prediction**:
    - Developed a prediction pipeline to classify new articles as fake or true.

## Running the Project
1. Open the `notebook.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Upload the `Fake.csv` and `True.csv` datasets when prompted.
3. Execute the cells step-by-step to see data preprocessing, model training, and evaluation.

## Results
Our Gradient Boosting model achieved an accuracy of XX% on the test dataset.

## Acknowledgments
Datasets sourced from [Kaggle/Drive](https://drive.google.com/drive/folders/1ByadNwMrPyds53cA6SDCHLelTAvIdoF_?usp=sharing).

## Contributing
Feel free to fork this repository and suggest improvements or report issues.
