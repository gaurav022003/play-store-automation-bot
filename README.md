# play-store-automation-bot
<p>This a python automation script for playstore scrapping. You can deploy this script and select a target app. Then, it scrape its version from playstore and if it's version changes it will send you an email.</p>

<p><b>python libraries you have to install</b>
<ol>
<li>pymongo</li>
<li>selenium</li></ol>
</p>


<p>
<b>Steps to use this code:</b>
<ol>
<li>Fork this repo.</li>
<li>Make a mongodb database named as scraper and two collection inside it named as playstore,All</li>
<li>Paste the mongodb connection link in database.py</li>
<li>In email.py change the reqired fields</li>
<li>Run the script</li>
</ol>
</p>
<p>
<b>Possible errors:</b>
<ol>
<li>pymongodb library: Try doing 'pip install pymongo[srv]'.</li>
<li>webdriver: Try having a downgraded version of chrome as mentioned in the error code message.</li>
<li>email.py: Use your app password given by google for third party apps.</li>
<li>package name: Package name of an app is unique which start with 'com'.</li>
</ol>
</p>
