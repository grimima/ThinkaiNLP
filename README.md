# Derej M3aya
![image](https://user-images.githubusercontent.com/132778772/236659379-4cc5c906-592a-4d08-be3d-1c63e52bcfa3.png)


- Derej with me is here to help 

---

## The Team

- The team solvers, consisted of 3 ESI students, are presenting you their project in aim to win the THINKAI HACKATHON.

---

## Situation

Amina is a young motivated moroccan who is intrested in self improvement industry. Along hitting the gym and eating healthy, she wishes to start reading more self help books. Since the books are mainly written in a foreign language, she thinks if only they were written in her native language so they would speak to her more and they would help her with her inconsistency.

"Nowadays, informing about the world is a must" says Omar to his friend at the coffee shop. He also claims that it is hard to keep up with the international news especially when hard concepts such as inflation or price cap on Russia are exposed. Omar thinks it would be intresting if the news articles were written in moroccan Darija to help understand what is going on in the world.

And we, as proud moroccans, want to include our culture into the new world of digitalization that includes the AI revolution we are witnessing these days. Given this, we have tried to develop a NLP model that is able to translate english sentences to the moroccan dialect, THE DARIJA.

---

## Purpose

- This repository is meant to showcase our work while trying to train two NLP models able to translate english sentences to a darija one.

- while looking for the best fit for our NLP product, we found many options from which we have choosen to test two models in which one is **FLAN T5** and the other is **MT0**.

---

## The dataset

- We have employed the open-source dataset we have been provided in the name of DODA. Here is the link: https://github.com/darija-open-dataset/dataset .
It contains 10002 rows that we have divided by 80% for training and 20% of testing. Says 7996 training rows and 2000 testing rows.
 
---

## Preprocessing

- Since the dataset is compound of sentences in both languages we had to tokenize it and after that we cleaned it.

```Python

from transformers import AutoTokenizer
tokenizer = AutoTokenizer.from_pretrained(model_checkpoint)
```

---

## Fine tuning

```Python 
model = AutoModelForseq2SeqLm.from_pretrained(model_checkpoint)
```

## Models

