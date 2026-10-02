# Selenium & Python Practice Scripts

A small collection of practice scripts: Selenium browser-automation tests and a few basic Python programs.

| File | What it does |
|------|--------------|
| `index.js` | Minimal Selenium WebDriver script (Node.js): opens Google in Chrome and searches for "Selenium" |
| `exp.js` | Selenium script with four checks against Google (page title, search, results count, search box visible); prints pass/fail for each |
| `prime.py` | Prints the prime numbers in a given range |
| `reg.py` | Tkinter registration form that shows the submitted details |
| `welcome.html` | Simple static test page |

## Run
Selenium scripts need Node.js, `npm install selenium-webdriver` and Chrome with a matching ChromeDriver:
```bash
node exp.js
```
Python scripts need only Python 3 (`tkinter` ships with the standard installer):
```bash
python prime.py
python reg.py
```
