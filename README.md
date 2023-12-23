# LLM-Detect-AI-Generated-Text
## Data
1. **Volume** - 10000 essays
2. **Categories** - Generated(1) and Not Generated(0)


### File and Fields

1. 1. test|train_essays.csv
   2. train_prompts.csv
   3. sample_submission.csv
## Preprocessing

When looking at the `train_essays.csv` our distribution of the data is looking skewed

![image](https://github.com/Alton1998/LLM-Detect-AI-Generated-Text/assets/39479720/2077b664-df03-4cb5-b7c8-e6fc373030f6)

So we will need external data one such promising data set found was [DeepFakeText](https://github.com/yafuly/DeepfakeTextDetect) there are others as well listed [here](https://github.com/NLP2CT/LLM-generated-Text-Detection?tab=readme-ov-file#datasets).

This dataset is loaded using the [Hugging face API](https://huggingface.co/docs/datasets/load_hub)



