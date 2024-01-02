# nagad_version_7
# github : https://github.com/RH-NAYM/nagad_version_7.git

sudo apt install iproute2 && sudo apt install wget && sudo apt install unzip && apt install nvtop 

apt-get update && apt-get install libgl1


wget "not updated yet" && unzip "not updated yet" && pip install -r requirements.txt

sudo apt update && sudo apt upgrade

python "nagad_main_API.py"


curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok

ngrok config add-authtoken 2Qm8hS1zPhVXiLjEdlI4738tLzF_2QJwGJMK5oTbQD33QSVXS && ngrok http --domain=hasb.nagadpulse.com 4444



         **********************************************************************************


### OLD : # ngrok http --domain=facedetection.ngrok.dev 8000 /// # ngrok http --domain=hawkeyes.ngrok.app 8020 /// # ngrok http --domain=nagadpulse.ngrok.app 4444


***	uvicorn nagad_main_API:app --reload --port 8000		***
