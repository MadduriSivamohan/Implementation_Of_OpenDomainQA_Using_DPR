This zip file contains 3 python notebooks.
- NLP_DPR is the main file containing the inference part of our model, with both retriever and reader models.The retriever is part of the dual encoder class. We also showcased the similarity between predicted and ground truth passages in this file. The reader will print the question, passage and top 5 answers. We used k=1 in retriever.
- Bi-encoder Training is the training file which uses the NQ_small dataset to train the dualencoder model using triplet loss function.
- Reader file showcases the working of the model for smaller texts as an example.
- For more info refer to the slides and report shared.
- Thank you