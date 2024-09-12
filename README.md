# Question Answering (QA) on CoQA dataset

The goal of this study is to implement two transformers-based models, employing BERTTiny and DistilRoBERTa, for performing a Generative Question Answering task on [CoQA dataset](https://arxiv.org/pdf/1808.07042). 
Since questions may be dependent on previous dialogue turns, two versions of each model have been implemented, which differ in whether or not taking into account the conversation
history. 

## Repository structure

````
.
├── notebook                            # jupyter notebook containing the project's code                     
├── README.md
├── requirements.txt                    # necessary installations
├── report.pdf                          # Report of the project
````

## Required installations
To install the required packages to run the project, download the ````requirements.txt```` file and run the following:

````
pip install -r /path/to/requirements.txt
````
