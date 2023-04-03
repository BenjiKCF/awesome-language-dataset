# awesome-language-dataset
Collection of all language dataset for finetuning LLM

A quick repo to download all the dataset to finetune your LLM. Pull requests are welcome.


| Data                  | Quantity |                             Source                             | Description                                                    |
| ---------------------- | :--: | :----------------------------------------------------------: | ------------------------------------------------------- |
| AlpacaGPT3.5Customized | 56k |       [Link](https://huggingface.co/datasets/whitefox44/AlpacaGPT3.5Customized)                    | generated from GPT-3.5 and extreme content filtering removed and replace with relevant generated outputs, specifically designed for training Alpaca-like models     |
| Chinese- English Translation dataset    | 500K | [Link](https://github.com/brightmart/nlp_chinese_corpus#5翻译语料translation2019zh) | 	Sampled and filtered based on the original dataset                 |
| GPT4all (Without P3) | ~440k |       [Link](https://huggingface.co/datasets/nomic-ai/gpt4all_prompt_generations)                    | Contains Laion OIG unified chip2, stackoverflow questions and Bigscience/P3 and pruned the P3 dataset     |
| pCLUE dataset            | 300K |        [Link](https://github.com/CLUEbenchmark/pCLUE)        | Sampled and filtered based on the original dataset               |
| ShareGPT_Vicuna_unfiltered | 48K  |     [Link](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered)     | ShareGPT conversations       |
| Stanford Alpaca dataset (English) | 50K  |     [Link](https://github.com/tatsu-lab/stanford_alpaca)     | Original Stanford Alpaca training data        |
| Stanford Alpaca dataset (Cantonese) | 50K  |    To be released  | Translated from the Chinese version using the ChatGPT interface  |
| Stanford Alpaca dataset (Chinese) | 50K  |                 [Link](https://github.com/ymcui/Chinese-LLaMA-Alpaca/blob/main/data/alpaca_data_zh_51k.json)     | Translated from the English version using the ChatGPT interface (with some parts discarded) |
| Stanford Alpaca dataset (French) | 50K  |                 [Link]([https://github.com/masa3141/japanese-alpaca-lora/tree/main/data](https://github.com/bofenghuang/vigogne/blob/main/data/vigogne_data_cleaned.json))     | Translated from the English version  |
| Stanford Alpaca dataset (Japanese) | 50K  |                 [Link](https://github.com/masa3141/japanese-alpaca-lora/tree/main/data)     | Translated from the English version  |
| Laion OIG | ~44M  |       [Link](https://huggingface.co/datasets/laion/OIG )                    |  large instruction dataset of medium quality along with a smaller high quality instruciton dataset        |
