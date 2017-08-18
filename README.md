# Python3-Wappalyzer

Python3 driver for Wappalyzer, a web application detection utility. 

Use code from https://github.com/chorsley/python-Wappalyzer, make it suitable for python3.

## Usage

```
>>> from Wappalyzer import WebPage
>>> WebPage("https://github.com").info()
{'apps': 'Twitter Bootstrap', 'title': "The world's leading software development platform · GitHub"}
```