# NordicMafia_rankingBot
A simple  ranking bot for the game "Nordic mafia". 
The script uses the pack multiprocessing to parallelize each instant of the bot-class. This way the timing for the different bot's won't interfere with each other.

The first thing you need to do is to install selenium and download chromedriver. When you have downloaded chromedriver, you need to either move the the .exe file to the same place as your python code, or open the code and change so that self.chromeDrivePath = "C:/user/<me>/Where/chromedriver/is_located/chromedriver.exe" (this is at line 14 or so). I personally recomend changing self.chromeDrivePath. 
