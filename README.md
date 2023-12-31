# ExtractiveQA
Fine-tuning masked language models to perform extractive question answering.

We finetune RoBERTa Base and Large for the SQuAD extractive question answering task, where models have to answer questions about a passage by citing an excerpt of the passage. We use LoRA, Adapters (Original adapters configuration from (Houlsby et al. 2019)), and Parallel Adapters to limit the number of fine-tuned parameters. On SQuADv1, finetuning RoBERTa-Large with 7.9M new params gives a dev set F1 of 93.72, #8 on the public SQuADv1 leaderboard. On SQuADv2, finetuning RoBERTa-Large with 14.2M new params gives a dev set F1 of 84.83, in the top 40% of models on the public SQuADv2 leaderboard.

Finetuned parameters for SQuADv2 model are provided.
