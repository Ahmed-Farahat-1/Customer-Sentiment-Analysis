# Customer Sentiment and Trend Analysis

![Project Logo](./images/Project_logo.jpg)

### Overview
This project analyzes customer feedback in both English and Arabic from various datasets to classify sentiment (positive, negative, or neutral) and identify trends. We apply a range of traditional machine learning and deep learning models.

---

## Datasets Used
1. [Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
2. [Amazon Product Reviews](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews/data)
3. [IMDB Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
4. [Arabic Sentiment Analysis](https://www.kaggle.com/code/rehab8reda/arabic-sentiment-analysis)

---

## Key Features

### Data Preprocessing
- Cleaning and normalizing text data (removing stop words, punctuation, etc.).
- Tokenization and feature extraction using techniques like TF-IDF, CountVectorizer, and GloVe embeddings.
![Preprocessing Workflow](./images/Preprocessing.png)
![Preprocessing Workflow](./images/Preprocessing2.png)

### Modeling
- Traditional models: Logistic Regression, Random Forest, SVM.
- Deep learning models: LSTM, DistilBERT for improved accuracy.
![Model Architecture](./images/Model.jpg)

---

## Evaluation
The models were evaluated using metrics such as:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix and Loss/Accuracy Graphs
![Confusion Matrix](./images/Confusion_matrix.png)

---

## Team Members

| Name          | Role                 | LinkedIn |
| ------------- | -------------------- | --------------- |
| **[Ahmed Samy Farahat]** | Machine Learning Engineer | [LinkedIn](www.linkedin.com/in/ahmed-s-farahat-437b14222) |
| **[mohamed wael khalifa]** | Machine Learning Engineer | [LinkedIn](www.linkedin.com/in/mohamed-wael-82b4342a2) |
| **[Ahmed Awad Ata]** | Machine Learning Engineer | [LinkedIn]([link_to_profile](https://www.linkedin.com/in/ahmed-awad-148079286?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)) |
| **[Amr Maher Abdallah]** | Machine Learning Engineer | [LinkedIn](https://www.linkedin.com/me?trk=p_mwlite_feed-secondary_nav) |
| **[Ahmed Emad]** | Machine Learning Engineer | [LinkedIn]([link_to_profile](https://www.linkedin.com/in/ahmed-emad-702396283/)) |
| **[Ahmed Abdelhamed Hussein]** | Machine Learning Engineer | [LinkedIn]([link_to_profile](https://www.linkedin.com/in/ahmed-abdelhameed-589bb6237)) |

---

## Technologies Used
- **Python Libraries**: Pandas, Scikit-learn, TensorFlow, Keras, SpaCy, NLTK
- **Tools**: MLflow, DAGsHub for version control and experiment tracking
- **Azure Cloud Services**: Model deployment

---

## Institution/Training Organization
![Institution Logo](./images/proAr.png)
This project was developed as part of the [Initiative Name]([link_to_initiative_website](https://www.depi.gov.eg/)).

---

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo-link.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebooks to reproduce the results.
