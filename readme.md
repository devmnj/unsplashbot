# unsplashbot
![Python package](https://github.com/manojap/wallspyder/workflows/Python%20package/badge.svg)

This is a automation scripts whihc using selenium package and Webdriver. You can search 
and download stock free image/resources from unsplash.com, in a single line of `brilliant python code`

## Requirements
- Python 3.7 or later
- Windows/Linux/Mac
- Python Modules
    - Selenium
    - webdriver-manager
    

## On Windows
In Windows you can just install the pacakge from github git with `pip` command as follows

```python
# Install the package
pip install unsplashbot
or
pip install git+https://github.com/manojap/unsplashbot.git

from unsplashbot import unsplash
unsplash.search('fruits').download()
```

## On Linux or Mac

On linux and Mac you need to clone the repo and install requirements

```python
# clone the repo

git clone https://github.com/manojap/unsplashbot.git

pip install -r requirements.txt

from unsplashbot import unsplash
unsplash.search('fruits').download()
```

# Default Save location  - Firefox

Make sure your save location is set to `default [Firefox]` or do it for the `first time`, after the 
automation process begins and pop up window for file action. I recommend use Chrome 

# Delaying download

`Use delay` for adjust elapse time for loading downloading button in slower internet connection.

