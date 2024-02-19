All credit for this project goes to Alejandro AO (https://www.youtube.com/watch?v=dXxQ0LR-3Hg&t=1471s).  He is the author of this work.  I simply worked through the project on his channel and was able to get it to work. 
Also, I used two different models:  for the embedding model i used  sentence-transformers/all-mpnet-base-v2 and for the language model I used  google/flan-t5-base.  I was not signed up to OPENAI to use their paid models, so
I used open source Huggingface Models. 

Also, my code didn't work on the latest Streamlit version (1.31.0 I think).  So based on Alejandro's advice, I downgraded to 1.29.0 and then the program worked.

Other issues I found with other HuggingFace open source embedding models was xthat some were limited to only a few input tokens when inputting the question.  So the current model I have seems to solve that issue.

This project shows the use of LLMs, Embedding Models, Streamlit and VS Code.
