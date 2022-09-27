# Character_ChatBot
### This bot adapts behaviour of given character and immitates in the same way

## *Data*
A dataframe of movie script is used to extract the table of character and their dialouges

## *Libraries/Tools used* 
- Transformers by HuggingFace<br/>
- TensorFlow<br/>
- Torch
- Pickle

## **The basic idea**
1. the core idea behind this project was to build a chatbot that can replicate like a targeted entity <br/>
2. This was done by taking input the messages and their reply converting it into a dataframe <br/> 
3. Converting text into numbers using "toknizers"
4. Training a model using the converted dataframe
5. This chatbot not only gives fixed replies but also learns from its previous execution

## Deployment
the model form the process is uploaded to a file using "Pikle" which is then used to deploy the bot on the huggingface app
![chatbot](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpQk4eI1yIBp6rumONUm0ZrjTmW5vgYa40IQ&usqp=CAU)
