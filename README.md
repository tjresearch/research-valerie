# SeniorResearch

My repo for 2019-2020 TJ Computer Systems Research. All senior research files will go here.

## Project Overview
1. Title: Natural Language Processing to Answer Questions Based on Informative Text <br>
2. Overview/Proposal: In my project, I will create a recurrent neural network model (RNN) that can answer questions based on an informational passage. I will train my model with the Stanford Question Answering Dataset (SQuAD), which contains Wikipedia passages as well as questions/answer pairs associated with the passages. I also plan on building off of BERT, a bidirectionally trained set of word vectors created by Google. BERT has been pretrained for text classification tasks. <br>
3. Requirements: As of right now, the code for my actual project is in Jupyter Notebooks. I've been running them on the cluster at TJ. To run the code, you need to clone NVIDIA's apex repo (please see Project heading below). You will also need to install fast-bert, created by huggingface on GitHub. Here's the repo: https://github.com/huggingface/transformers.git. These installations can be found in the Jupyter notebook fastBERT_test.ipynb.<br>
The files from the folder "Stanford Class" have separate installation needs, and these files are python files that I ran in PyCharm (which created all the extra folders/files). However, these files were all for my own learning purposes and not part of my actual project. <br><br>

## Folders

### Journals
The journals that I turned in every week in class go into this folder. They include my progress, what I learned that week, and my future goals.

### Project
All the files that are associated with my actual question answering project (as opposed to files I created for my online class) will end up in this folder. <br>
Inside the project folder, you will see that there's a folder called apex that doesn't open here. This is another GitHub repo that I had to clone for use in my project, and it can be found here: https://github.com/NVIDIA/apex.git

### Stanford Class
These are all the documents from an online class I followed through Stanford that teaches natural langugae processing with deep learning. The course is called CS224n, and their web page contains all the course notes. All the lecture videos (about 1.5 hrs each) are on YouTube. This is where I learned all the foundational material for my project, such as word embeddings, text generation/prediction, and types of recurrent neural networks.
