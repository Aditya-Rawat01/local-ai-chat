Steps to run this locally:
pull this repo.
Then install all dependencies.
Create a gemini 1.5 flash key for free from google ai studio and put that key in .env file.
thats it, it should run locally.


considerations:
output tokens are capped to 250 tokens per message so that free tier dont get exhausted easily. It can also cause abrupt end to messages.

no db is used, model remembers recent 11 messages in each new chat
