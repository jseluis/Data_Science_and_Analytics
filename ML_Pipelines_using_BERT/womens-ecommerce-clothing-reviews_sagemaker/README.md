# Feature transformation with Amazon SageMaker processing job and Feature Store

### My Quick Lab from Practical Data Science Specializastion, Coursera.

Start with  the raw [Women's Clothing Reviews](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews) dataset and prepare it to train a BERT-based natural language processing (NLP) model. The model will be used to classify customer reviews into positive (1), neutral (0) and negative (-1) sentiment.

Convert the original review text into machine-readable features used by BERT. To perform the required feature transformation you will configure an Amazon SageMaker processing job, which will be running a custom Python script.

Steps:

    1. Configure the SageMaker Feature Store

    2. Transform the dataset

    3. Inspect the transformed data

    4. Query the Feature Store
