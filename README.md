### Selenium on Python: Web Scraping Prosple Australia

![[Scraping Output Preview]](scraping-output-preview.png)

I'm attempting to generate a repository of job data for fellow 485 Visa holders and International Students in Australia who are looking for graduate jobs.

It is **VERY** barebone, but have a look at it:

- `job_scraping.ipynb` is the main notebook
- `requirements.txt` lists out the libraries existed in my environment (it's not really clean so as I've shared this environment with some other tasks related to postgresql management)

Main library used to take note are:
```
urllib3=1.26.16  // must be paired with selenium 3.141.0, really don't know why so if someone do know about it plz lmk)
selenium=3.141.0
webdriver-manager=4.0.1=pypi_0  //if you don't want to install the browser driver by yourself
pandas=2.2.1
python-dateutil=2.8.2 // maybe?
```

05/04/2024 Export can be found in *Releases* or at a shared [Google Sheets sheet](https://docs.google.com/spreadsheets/d/1H0tS18Z9MoDLWJrzFrewn-RRKWKG-AqXB3DNz0uu2xg/edit?usp=sharing)

Thank you and Happy Job Hunting!

*May the odds be in your favour~~*
