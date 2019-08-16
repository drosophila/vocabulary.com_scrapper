## Webscrapping using BeautifulSoup and ChromeDriver 

1. check the version of Chrome that you've installed on your system. You can find your version by clicking the three little dots on the top right of your browser > **Help** > **About Google Chrome**
It should look like this 

[chrome version](https://github.com/drosophila/vocabulary.com_scrapper/blob/master/docs/_static/chrome_version.PNG)

2. depending on your Chrome version and your OS go the ChromeDriver [Downloads](https://chromedriver.chromium.org/downloads) page and download the **.zip** file   

3. Unzip the downloaded file which results in a folder of the same name **chromedriver_win32** that contains the chromedriver engine.   

In the example provided I use BeautifulSoup and ChromeDriver to log into my [Vocabulary.com](https://www.vocabulary.com) account, navigate to the _Words I've Mastered_ page, scroll all the way down the parse html class containing all the words/definitions into a pandas dataframe and save it.

My log in credentials are saved within the _vcblry_creds.py_ file in my `lib/python/site-packages` folder. 