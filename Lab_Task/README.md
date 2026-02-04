# Agentic AI – Lab Task 1  
## Fine-Tuning a Small Language Model (SLM)

This lab task focuses on fine-tuning a Small Language Model (SLM) on a text dataset using Google Colab and the Hugging Face ecosystem. The objective is to understand the end-to-end process of adapting a pretrained language model to a new text dataset and evaluating its performance.

### Dataset
The AG News dataset is a publicly available text dataset consisting of news articles from different categories. It was used for causal language modeling by training the model directly on raw text data.

### Model
DistilGPT-2 was selected as the Small Language Model for this task. It is a lightweight language model with fewer than 3 billion parameters, making it suitable for fine-tuning on limited computational resources such as Google Colab.

### Methodology
The task involved loading and preprocessing the dataset, tokenizing the text data, and fine-tuning the pretrained DistilGPT-2 model using causal language modeling. During training, input tokens were used as labels to enable next-token prediction.

### Evaluation
Model performance was evaluated using evaluation loss. Lower loss values indicate better language understanding and improved predictive capability on unseen text data.

### Observations
After fine-tuning, the model generated more coherent and context-aware text compared to the base pretrained model, demonstrating effective learning from the dataset.

### Conclusion
This experiment demonstrates how a small language model can be fine-tuned efficiently on a text dataset using modern AI frameworks. The results highlight the effectiveness of transfer learning in adapting pretrained models to new domains.
