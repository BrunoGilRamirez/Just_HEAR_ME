# Sólo Escúchame: Spanish Emotional Accompaniment Chatbot 💬🤖

Welcome to **Sólo Escúchame** – an open-source Spanish emotional assistance chatbot powered by the LLaMA-2-7b-Chat model. Our goal is to provide emotional support through advanced AI. 💡

## Models in HuggingFace 🤗

**Sólo Escúchame** is an enhanced, fine-tuned model based on LLaMA-2-7b-Chat, meticulously trained using the datasets outlined in the next section. You can download the model and find detailed specifications by clicking [here](https://huggingface.co/BrunoGR/Just_HEAR_Me).

Additionally, we offer another version of this model, also fine-tuned on LLaMA-2-7b-Chat, utilizing the PEFT Adapter. This version is optimized for broader accessibility, requiring fewer computational resources. For more details and to download this model, [click here](https://huggingface.co/BrunoGR/JUST_HEAR_ME-PEFT_Adapter).


## About This Repository 👋

In this repository, you'll find:

- **Fine-Tuning Scripts:** Explore the scripts we use to fine-tune the LLaMA-2-7b-Chat model with our custom datasets.

- **Datasets:** Access links to our curated datasets.

- **Research Paper:** Read our detailed research paper to understand the methodology and findings.

- **Additional Details:** Discover other relevant information and updates.

### Datasets 📚

At the core of our work lies the data. We have introduced two essential datasets:

> - [**Hispanic Emotion Recognition Based on Plutchik’s Wheel (HRECPW)**](https://huggingface.co/datasets/BrunoGR/HRECPW-Hispanic_Responses_for_Emotional_Classification_based_on_Plutchik_Wheel) -  is designed for training models in the task of emotional classification. This dataset allows models to identify and classify various emotional categories based on the Plutchik wheel, with a particular focus on the Spanish language. 


> - [**HEAR (Hispanic Emotional Accompaniment Responses)**](https://huggingface.co/datasets/BrunoGR/HEAR-Hispanic_Emotional_Accompaniment_Responses) - is designed to train language models in the task of emotionally accompanying users. This dataset enables models to generate empathetic and appropriate responses in Spanish, understanding and responding to different emotional situations.

### Research Paper 📖

Our paper has been accepted in the at the **23rd Mexican International Conference on Artificial Intelligence** ([MICAI 2024](http://www.micai.org/2024/)). You can also find our work on [arxiv](https://arxiv.org/).

If you use this code or find our work helpful, please cite our paper:

> ```bibtex
> @article{Gil2024,
>   title={Sólo Escúchame: Spanish Emotional Accompaniment Chatbot},
>   author={Gil Ramírez, Bruno and López Espejel, Jessica and Santiago Díaz, María del Carmen and Rubín Linares, Gustavo Trinidad},
>   journal={arxiv},
>   year={2024}
> }
> ```

### Ongoing Work 💻

> We are working on the chatbot interface ...
