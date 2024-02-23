# ActionBot Contact
ActionBot Contact is a Contextual AI Chatbot built for Airport Usecases.<br>
It was presented in the Unisys Cloud 20/20 Year 11 Competition and placed 1st Runners Up.<br>

## Setup
* Open two terminals and change directory to 'rasa_files'
* run command 'rasa run actions' in one terminal and 'rasa run -m models --enable-api --cors "*" --debug' in the other
* Open another terminal, cd to 'flask_server'
* run command 'python dummy_api.py'
* open another terminal and run command 'sudo docker run -p 8000:8000 rasa/duckling'
* To allow integration with other services like Telegram and Google Assistant, you will need to use ngrok to allow port forwarding. Look into the ngrok and rasa documentation for more details.
  
## Folder Description
**Dashboard:** Frontend for the Chatbot built using ReactJS<br>
**flask_server:** Flask Server to host the website<br>
**rasa_files:** Code for the Chatbot built using Rasa Framework<br>

## Features

![image1](https://github.com/pranavh4/ActionBot_Contact/assets/45517185/26ddf465-7759-4da9-8fc2-4de02bfedb39)
