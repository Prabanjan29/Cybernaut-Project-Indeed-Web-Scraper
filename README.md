Indeed Job Scraper with Apify 🤖

This project automates scraping job postings from Indeed using the Apify API. It extracts job details, cleans descriptions, detects relevant skills, and saves the results into structured Excel and CSV files for easy analysis.

✨ Key Features

✅ Automated Scraping – Fetches job postings from Indeed via Apify Actor.

🧹 Data Cleaning – Removes HTML tags, cleans text, and organizes results.

🧑‍💻 Skill Detection – Automatically highlights skills like Python, SQL, AWS, Django, Excel, etc.

📄 Structured Output – Saves job data in both .xlsx (formatted) and .csv.

🎨 Excel Styling – Adds header colors, bold fonts, centered text, and auto column width.

🔐 Secure Credentials – Keeps API keys safe in a .env file.

📂 Project Structure
.
├── job_scraper.py       
├── .env                 
├── requirements.txt     
└── README.md            

🚀 Getting Started
Prerequisites

Python 3.x

An Apify account
 (free tier available)

🛠️ Installation & Setup

Clone the Repository

git clone https://github.com/Prabanjan29/Indeed-Job-Scraper.git
cd Indeed-Job-Scraper


Install Dependencies

pip install -r requirements.txt


Configure Environment Variables

Log in to Apify
.

Get your API Token and Actor ID from the Indeed Scraper Actor
.

Create a .env file in the project root:

APIFY_TOKEN="your_personal_api_token"
ACTOR_ID="your_actor_id_for_indeed_scraper"

💻 How to Run

Run the script:

python job_scraper.py


Enter a job title when prompted (e.g., Python Developer).

Wait for the scraping process to complete.

Find your results in:

JobTitle_cleaned_jobs.xlsx → Formatted Excel file

JobTitle_cleaned_jobs.csv → Raw CSV file

📊 Sample Output
Excel / CSV Columns

Job ID

Job Title

Company

Location

Remote

Salary

Job Type

Rating

Reviews

Posted

Benefits

Skills (detected)

Apply Link

Description

⚠️ Important Notes

⏳ First Run Delay – Apify may take a minute to initialize.

💰 Apify Credits – Free accounts have limited usage.

🔒 Security – Never commit your .env file or expose API keys.

👤 Author

Prabanjan S

GitHub: @Prabanjan29
