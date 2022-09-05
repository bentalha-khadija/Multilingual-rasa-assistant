# Rasa-Chatbot

## 1. Installations and environment

> <br>
> First make sure you have python 3.8 and the visal studio build tools installed
> <br><br>
> 
> ### 1.1 Create a environment and activate it using conda :
> ```bash
> conda env create -f environment.yml
> conda activate rasabot
> ```
> ### 1.2 Create an environment and activate it using pip :
> ```bash
> pip install -r requirements.txt
> ```
> <br>

<hr>
<br>

## 2. Seting up Rasa

> ### 2.1 validate script :
> ```bash
> rasa data validate
> ```
> ### 2.2 train model :
> ```bash
> rasa train
> ```
> ### 2.3 link the html interface to the model :
> ```bash
> rasa run -m models --enable-api --cors "*"
> ```
> > and then open the index.html file in the browser
> Or 
> 
> ### 5. run the chatbot :
> ```bash
> rasa shell
> ```
> > and then talk to the bot in the terminal