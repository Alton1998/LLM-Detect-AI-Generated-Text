# LLM-Detect-AI-Generated-Text
## Data
1. **Volume** - 10000 essays
2. **Categories** - Generated(1) and Not Generated(0)


### File and Fields

1. 1. test|train_essays.csv
   2. train_prompts.csv
   3. sample_submission.csv
## Preprocessing

Below are some of the preprocessing options:
1. Word Embedding
2. Word2Vec
3. Word C
4. ounts, Stop word Counts, punctuation counts and uniqueness factors
5. Removing Stop words
6. Split words as tokens
7. Vecotorizing the tokens using 

## Creating a Pretrained Model

When looking at the `train_essays.csv` our distribution of the data is looking skewed

![image](https://github.com/Alton1998/LLM-Detect-AI-Generated-Text/assets/39479720/2077b664-df03-4cb5-b7c8-e6fc373030f6)

So we will need external data one such promising data set found was [DeepFakeText](https://github.com/yafuly/DeepfakeTextDetect) there are others as well listed [here](https://github.com/NLP2CT/LLM-generated-Text-Detection?tab=readme-ov-file#datasets).

This dataset is loaded using the [Hugging face API](https://huggingface.co/docs/datasets/load_hub)

### Which model do we choose?

Lets consider two types of models:
1. Machine Learning Models
2. Deep Learning Models

#### Machine Learning Models
1. Bayesian Filtering classifiers used to detect sentiments in an email and classify emails as HAM and SPAM.
2. 

#### Deep Learning Models.

1. CNN used for Sentence Classification
2. Bi directional LSTM(BiLSTM) that is used for sequence tagging
3. Attention Based bidirectional LSTM for relational Classificaition and topic based sentiment analysis
4. BERT for word embedding taking into account left and right semantic contexts
5. THEMIS an RCNN model used to recognise phishing messages
6. Hybrid CNN Model used for both images and texts

## References

1. [Yaseen, Qussai. "Spam email detection using deep learning techniques." Procedia Computer Science 184 (2021): 853-858.](https://www.sciencedirect.com/science/article/pii/S1877050921007493)






