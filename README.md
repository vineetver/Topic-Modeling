The dataset is from [webrobots.io](https://webrobots.io/indiegogo-dataset/). The dataset contains data from all the projects hosted on the Indiegogo platform. 

In this particular project, I implemented topic modelling on the project descriptions of all the projects hosted on Indiegogo. Topic modeling is used to cluster similar documents together. 

I used Latent Semantic Analysis (LSA) and  Latent Dirichlet Allocation (LDA) to cluster the project descriptions.   

LSA is a statistical technique used to analyze relationships between documents and the terms they contain by producing a set of concepts related to the documents and terms. In contrast, LDA is a statistical technique used to automatically discover the topics represented in a collection of documents. 

### Requirements 
```
pandas,
numpy,
matplotlib.pyplot,
seaborn,
nltk,
types
 ```
### Running the code  

The LDA and LSA models are in the `ip.ipynb` notebook. 

First, the data is loaded from the `/data` dictionary. Followed by these preprocessing steps:  - Tokenization - Lemmatization - Removal of stopwords - Removal of punctuations  

After the preprocessing, LSA and LDA models are built and visualized using dendrograms.

### View the code

[NBviewer](https://nbviewer.org/github/vineetver/Indiegogo-Topic-Modelling/blob/main/tp.ipynb)
