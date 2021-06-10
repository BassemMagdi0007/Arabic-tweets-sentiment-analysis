# Sentiment_analysis_Dataset

## CLeaning Techniques
1. replace # with word "هاشتاج"
2. remove digits and non-Arabic letters
3. replace urls with word "رابط"
4. replace @mention with word "مستخدم"
5. keept stopwords for contexual meaning 
6. remove special characters
7. remove elongation
8. remove redundant punct


## To-do

Model | Done
------------ | -------------| 
Captum |  :heavy_check_mark:
Cross Entropy loss |  :heavy_check_mark:
Focal Loss | :heavy_check_mark:
Kfolds |:heavy_check_mark:
Few shot learning |
BI-Lstm Mazajk Embeddings |


## Results

Model |Test Acc | emoji |Done
------------ | -------------| ------------- | -------------|
Marbert | 0.881 |:heavy_check_mark: |:heavy_check_mark:
twitter-xlm-roberta-base |0.837 | :heavy_check_mark:|:heavy_check_mark:
arabertv02 | 0.858 |:heavy_multiplication_x:|:heavy_check_mark:


# Captum Interepertability 
Captum is a model interpretability and understanding library for PyTorch. Captum means comprehension in Latin and contains general purpose implementations of integrated gradients, saliency maps, smoothgrad, vargrad and others for PyTorch models. It has quick integration for models built with domain-specific libraries such as torchvision, torchtext, and others.
<br>

![image](https://user-images.githubusercontent.com/45721757/118771175-844f9780-b882-11eb-92f0-06d91f7a2683.png)


# Sweep for choosing  best hyperparameters
sweep probided by W&B , an open source library used for Build better models more efficiently with Weights & Biases experiment tracking.

![image](https://user-images.githubusercontent.com/45721757/118771255-a34e2980-b882-11eb-97e5-0a5c318237e7.png)
