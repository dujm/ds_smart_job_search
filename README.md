# ds_smart_job_search
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Build Status](https://travis-ci.org/dj/ds_smart_job_search.svg?branch=master)](https://travis-ci.org/dj/ds_smart_job_search) [![Updates](https://pyup.io/repos/github/dj/ds_smart_job_search/shield.svg)](https://pyup.io/repos/github/dj/ds_smart_job_search/) [![Python 3](https://pyup.io/repos/github/dj/ds_smart_job_search/python-3-shield.svg)](https://pyup.io/repos/github/dj/ds_smart_job_search/) [![Coverage](https://codecov.io/github/dj/ds_smart_job_search/coverage.svg?branch=master)](https://codecov.io/github/dj/ds_smart_job_search?branch=master) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)


A short description of the project.
---
## 1. Use the app online

 * [App V3](https://ai-companies.herokuapp.com/)  

![ScreenShot](Screen_shot_app.png)

---

## 2. Make your personalized job search app
### Build your app

```shell
# Clone the repo
git clone git@github.com:dujm/ds_smart_job_search.git
rm .git

# Modify scraping conditions
cd app
vim scrape_de.py
# Modify "url_de", "My_City", "max_results_my_city", and "page"

# Web scrape from indeed.de
python scrape_de.py

# Run the app
python app.py

# Visit http://127.0.0.1:5000
```

### Pin your dependencies
```shell
pip freeze > requirements.txt
```

### Deploy on Heroku
Follow the [Dash deployment guide](https://dash.plot.ly/deployment) or have a look at the [dash-heroku-template](https://github.com/plotly/dash-heroku-template)  

---

## 3. Legality
 * Users may be subject to legal ramifications depending on where and how they attempt to scrape information.
 * Respect the Indeed [Terms of Service](https://www.indeed.com/legal)
 * Respect the rules of robots.txt.
 * Use a reasonable crawl rate
