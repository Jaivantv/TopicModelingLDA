# Topic Modeling Using LDA Model

Our project ‘Topic Modelling using LDA Model’ tackles the problem of inefficient search results in the case of localized search engines. Companies, industries, websites, educational institutions etc. house a large amount of textual data which is impossible to classify and index according to topics. Furthermore, search results on such documents return only the most keyword heavy result whereas in some cases the user would require related topics to a certain document. This may be achieved through the use of topic modelling wherein the relationship between words and phrases are analyzed algorithmically. There are several algorithms which can help achieve this, but the most accurate and efficient algorithm is LDA, which we have used in our implementation. LDA is a topic modelling algorithm that stands for Latent Dirichlet Allocation. The goal of LDA is to learn the representation of a fixed number of topics, as well as the topic distribution of each document in a collection of documents. In our approach we have focused on the case of research documents. Most specific and non-specific online libraries for research papers are designed to return keyword-based results. In our project we have used a dataset containing research papers from multiple topics and we aim to use the LDA model to determine the most probabilistically related documents to an unseen document. The model achieves this by finding the hidden relationships between the documents that would not be identifiable by traditional search algorithms. With this we’ve been able to identify related documents with a very high accuracy as well as accurately classify a document to certain topics in the process. We have implemented an interface through which any unseen document can be run through the model which then presents the most related documents to the user. The amount of relevant results would only increase with a larger dataset. Thus, this shows that this may be applied to specific cases in different industries with good results.

Running the code(Using Google Colab):
1. Go to https://colab.research.google.com/ and sign into your account
2. From the prompt choose the 'New notebook' option
3. Go to File > Upload Notebook and choose the 'Topic_Modeling_Using_LDA_Model.ipynb' file
4. Open your Google Drive and upload the 'trainldaf.csv' file
5. Create a folder called 'templates' and upload the 'index.html' file to the folder
6. In the Colab notebook go to Runtime > Run all
7. In the second cell, click on the URL when prompted and sign in to your Google Account
8. Copy the authorization code and paste it into the prompt in the notebook
9. Once the cells run, in the final cell click on the ngrok.io link displayed in the output
10. Enter a document of two or three lines into the text area and click submit
11. The topic distribution and relevant topics are displayed
