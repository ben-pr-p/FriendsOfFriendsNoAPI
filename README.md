# selenium-friends-scraper

If you're somebody trying to get their friends of friends to play with it in Gephi, this is for you. It still works, but it's pretty slow and the Selenium config is a bit odd, and I don't have time to make it work right at this moment.

### Usage
The current version is written using Selenium's Firefox web driver, which means you need Firefox installed. 

Download the Geckodriver for Firefox here: https://github.com/mozilla/geckodriver/releases Download and install the exe file (for Windows) into the C:\Windows\System32 folder.

Soon, versions will be rewritten for use with Chrome, Safari, and maybe IE.

### Installation

Either run:

```sh
$ git clone https://github.com/ben-pr-p/selenium-friends-scraper.git
$ cd selenium-friends-scraper
$ source venv/bin/activate
(venv)$ python main.py
```
or, if you have `pip`
```sh
$ git clone https://github.com/ben-pr-p/selenium-friends-scraper.git
$ cd selenium-friends-scraper
$ pip install selenium
$ python main.py
```
