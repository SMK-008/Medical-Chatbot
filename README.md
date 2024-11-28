# Medical-Chatbot
## Setup guide
- Clone the repo
```
git clone https://github.com/SMK-008/Medical-Chatbot.git
cd Medical-Chatbot/
```
- Create a virtual environment
```
python -m venv myvenv
source myvenv/bin/activate
```
- Download necessary packages in the virtual environment
```
pip install -r requirements.txt
```
## Groq API key generation
- Create an account in Groq.
- Generate an API key.
- Create a .env file in the root directory. In that file enter the following code:
```
GROQ_API_KEY=YOUR_API_KEY
```
- Replace YOUR_API_KEY with your Groq API key.
  
## Running guide
-To run the app, enter the following commands:
```
python3 ingest.py
chainlit run model.py -w
```
## License
This project is licensed under MIT License.
