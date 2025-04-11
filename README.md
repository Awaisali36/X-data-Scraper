# X-data-Scraper
#🐦 n8n X Data Scraper Workflow
-This workflow scrapes data from X (formerly Twitter) using n8n. It fetches public information like tweet content, usernames, timestamps, and more (depending on how you configure it).

#🚀 Features
-Scrapes tweets based on specific queries

-Extracts tweet content, usernames, links, timestamps, etc.

-Fully automated through n8n’s visual workflow editor

#🧰 Prerequisites
Before running this workflow, make sure you have the following:

Node.js (v18 or above recommended)
Install Node.js

n8n (self-hosted)
You can install it globally using:

bash
Copy
Edit
npm install -g n8n
🛠️ Setup Instructions
1. Run n8n Locally
Start your local instance by running:

bash
Copy
Edit
n8n
This will open the n8n editor at: http://localhost:5678

2. Import the Workflow JSON
Open the n8n Editor

Click on Workflows > Import from File

Select the .json file you received or created

Click Import

3. Configure Any Required Credentials
If the workflow uses any external APIs or authentication (like a browser session or HTTP request headers), you may need to:

Set up credentials under Credentials > Create New

Update those inside the workflow's HTTP Request node(s)

4. Run the Workflow
Once configured:

Click Execute Node or Execute Workflow

You’ll see the scraped data in the output of the final node (JSON format)

📝 Notes
You can customize the target usernames, hashtags, or topics directly in the workflow nodes.

If you're scraping dynamic content, consider adding delay/timers to avoid hitting rate limits.
