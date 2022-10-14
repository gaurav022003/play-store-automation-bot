# play-store-automation-bot

**python libraries you have to install**\n
pymongo
selenium

This a python automation script for playstore scrapping. You can deploy this script and select a target app. Then, it scrape its version from playstore and if it's version changes it will send you an email.

Steps to use this code:
1.Fork this repo.
2.Make a mongodb database named as scraper and two collection inside it named as playstore,All
3.Paste the mongodb connection link in database.py
4.In email.py change the reqired fields
5.Run the script

Possible errors:
1.pymongodb library: Try doing 'pip install pymongo[srv]'.
2.webdriver: Try having a downgraded version of chrome as mentioned in the error code message.
3.email.py: Use your app password given by google for third party apps.
4.package name: Package name of an app is unique which start with 'com'.
