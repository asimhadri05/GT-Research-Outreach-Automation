# GT-Research-Outreach-Automation
Python tool for GT students to fully automate professor outreach

This tool automates the process of identifying and emailing Georgia Tech College of Computing faculty for research outreach. It scrapes faculty profiles, extracts emails, filters professors based on research relevance, and sends personalized emails with your resume attached.

## Features
- Scrapes all 24 pages of the [GT CoC faculty directory](https://www.cc.gatech.edu/people/faculty)
- Extracts name, email, profile URL, and matched research keywords
- Filters relevant professors using customizable keyword matching
- Sends personalized emails using Python's `smtplib`
- Saves results to CSV for manual review or tracking

## Tech Stack
- Python, BeautifulSoup, pandas, smtplib

## Setup
1. Clone the repo and install dependencies (`pip install -r requirements.txt`)
2. Add your resume as `YourResume.pdf`
3. Update placeholders in the script:
   - `sender_email`
   - `app_password` (use Gmail app password)
4. Run the script in Google Colab or locally

## Notes
- Use responsibly — add delays between sends to avoid spam filters
- Track replies manually or extend with Gmail API for response logging
