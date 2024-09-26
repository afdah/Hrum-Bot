# Hrum-Bot
Hrum Bot that mines hrum cookies <br>
Link: https://t.me/hrummebot/game?startapp=ref761561340

# Requirements
**Python 3.10 is required**

# Installing
Clone the repository
```shell
git clone git@github.com:Cherimolah/Hrum-Bot.git
cd Hrum-Bot
```
Copy the `.env` file and edit it. Use API_ID and API HASH from here https://my.telegram.org/apps
```shell
cp .env-sample .env
nano .env
```
Create the virtual environment
```shell
python -m venv venv
venv\Scripts\activate # For Windows
source venv/bin/activate # For Linux
pip install -r requirements.txt
```

# Run the bot

```shell
python main.py
```
You can use the `-a` or `-action` to choose the option
```shell
python main.py -a 2 # Run all sessions
```


