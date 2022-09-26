# stream-flask-twilio-video
Sistema de salas de transmissão de vídeo utilizando Python e JavaScript.


Principais instruções:
Installation Instructions
To install the application on your system follow these steps:

Create a Twilio account (if you don't have one yet). It's free!
Generate an API Key for your account.
Clone this repository
Create a virtualenv and install the requirements
Create a .env file by copying the .env.template file. Fill out the values for your Twilio account's SID, API Key SID and API Key Secret.
Execute python app.py to start the server.
Navigate to http://localhost:5000 on your web browser. Connecting to the service from a phone or another computer may not work, as browsers require a secure (HTTPS) connection to give access to the media APIs. In that case, I suggest you use ngrok to give your application a temporary HTTPS URL.

Projeto original disponível em:
https://github.com/miguelgrinberg/flask-twilio-video
https://www.twilio.com/blog/crie-um-aplicativo-de-chat-por-video-usando-python-javascript-e-twilio-programmable-video
