# Sentiment Analysis of Tweets About Anitta

The goal of this project was to develop a sentiment analyzer, specifically a classification model, to understand the sentiment expressed in tweets about the artist Anitta. 

>[!NOTE]
>The sentiment analysis in this project is binary, focusing on classifying tweets as either positive or negative.

The project involved several key steps typical of a data science workflow:

1. **Data Collection**: The process began with scraping tweets related to Anitta using the Twitter API. This step involved gathering a substantial amount of data for analysis.

2. **Data Cleaning and Preprocessing**: After collecting the raw data, it was cleaned and preprocessed. This included handling missing values, removing irrelevant information, and preparing the data for labeling.

3. **Data Labeling**: The collected tweets were labeled for sentiment using the LabelStudio tool. The sentiment analysis in this project is binary, classifying tweets as either positive or negative.

4. **Model Training and Evaluation**: A sentiment classification model was then trained using the labeled data. The model's performance was evaluated to ensure accuracy and effectiveness in classifying tweet sentiments.

---
## Requirements

To run this project, you will need the following Python libraries:

- `torch`
- `re`
- `transformers`
- `sklearn`
- `torch.nn`
- `numpy`
- `pandas`
- `tensorflow`
- `seaborn`
- `matplotlib`
- `torch.nn.functional`
- `google.colab`
- `snscrape`

Install the necessary dependencies with the following command:

```bash
pip install torch transformers sklearn numpy pandas tensorflow seaborn matplotlib snscrape
```

---
## Project Structure

- **`scraping.ipynb`**: Notebook containing the code used to perform data scraping from Twitter. This notebook is responsible for collecting tweets about Anitta and saving the collected data.

- **`scraping/`**: Folder containing all the collected Twitter data. The files in this folder are the results of the scraping process and are used for subsequent analysis.

- **`data/`**: Folder containing the labeled data after collection. These data were labeled using the LabelStudio tool to create a dataset suitable for model training and evaluation.

- **`sentiment-analysis.ipynb`**: Notebook with the classifier implementation and other requirements of the project. It includes tweet analysis and the application of the sentiment classification model.

---
## How to Use

1. **Data Collection**:
   - Run the `scraping.ipynb` notebook to collect tweets. Make sure you have the necessary credentials to access the Twitter API.

2. **Data Labeling**:
   - After collecting the tweets, use the LabelStudio tool to label the data and save them in the `data/` folder.

3. **Sentiment Classification**:
   - Open the `sentiment-analysis.ipynb` notebook and run the cells to train and evaluate the sentiment classifier. The trained model will be saved in the `model/` folder. Ensure that all necessary data is correctly saved in the appropriate folders.

---
## Project by

[Alexandre Diniz](https://github.com/alexandredsz), Computer Science student at UFMS
