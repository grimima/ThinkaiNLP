# ThinkaiNLP
Personalizing AI to fit the moroccan community

The team solvers, consisted of 3 ESI students, are presenting you their project in aim to win the THINKAI HACKATHON.
<h2> Situation </h2>

Amina is a young motivated moroccan who is intrested in self improvement industry. Along hitting the gym and eating healthy, she wishes to start reading more self help books. Since the books are mainly written in a foreign language, she thinks if only they were written in her native language so they would speak to her more and they would help her with her inconsistency.

<p>
"Nowadays, informing about the world is a must" says Omar to his friend at the coffee shop. He also claims that it is hard to keep up with the international news especially when hard concepts such as inflation or price cap on Russia are exposed. Omar thinks it would be intresting if the news articles were written in moroccan Darija to help understand what is going on in the world.
</p>
<p> And we, as proud moroccans, want to include our culture into the new world of digitalization that includes the AI revolution we are witnessing these days. Given this, we have tried to develop a NLP model that is able to translate english sentences to the moroccan dialect, THE DARIJA </p>
<p>This repository is meant to showcase our work while trying to make a NLP model able to translate english sentences to a darija one</p>

<h2>Along the 1st model  <h2>
  <h3>The dataset </h3>
  We have employed the open-source dataset we have been provided in the name of DODA. Here is the link:https://github.com/darija-open-dataset/dataset
  It contains 10002 rows that we have divided by 80% for training and 20% of testing. Says 7996 training rows and 2000 testing rows. 
  <h3>The model we have used </h3>
  The T5-flat model is what the project mainly relied on. You can find the link here:https://github.com/huggingface/notebooks/blob/main/examples/translation.ipynb
  <h3>Strategie </h3>
  <ul>
  <li><h4>Preprocessing</h4>
  the preprocessing phase consists of tokenization of the dataset and clean it.
  <li><h4>Fine-tuning</h4>
  We tried to adjust the pre-existing model to our dataset by setting our current dataset to the model.
  '''python 
  '''
  
  
  



