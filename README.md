## To install dependencies:
`pip3 install -r requirements.txt`

## To run:
`python scrape.py`

Note: You will have to fill out your username and password in the script.

**In some cases, the sign-in process may hang on a reCAPTCHA on the sign-in page and scraping will not progress. No error will be thrown when this happen. The scraper will instead hang on the first company. If you suspect that this has happened, disable headless browser scraping by commenting out line 22 and manually approving the reCAPTCHA on the sign-in page.**

Feel free to message me with questions. Last used and tested on April 27, 2020 to scrape all questions by company from Leetcode.
