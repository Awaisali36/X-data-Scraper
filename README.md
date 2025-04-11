# 🐦 n8n X Data Scraper Workflow

This workflow scrapes data from **X (formerly Twitter)** using n8n. It fetches public information like tweet content, usernames, timestamps, and more (depending on how you configure it).

---

## 🚀 Features

- Scrapes tweets based on specific queries  
- Extracts tweet content, usernames, links, timestamps, etc.  
- Fully automated through n8n’s visual workflow editor

---

## 🧰 Prerequisites

Before running this workflow, make sure you have the following:

- **Node.js** (v18 or above recommended)  
  👉 [Install Node.js](https://nodejs.org)

- **n8n (self-hosted)**  
  Install it globally:
  ```bash
  npm install -g n8n
## 🛠️ Setup Instructions

### 1. Run n8n Locally

Start your local instance by running:
This will open the n8n editor at: [http://localhost:5678](http://localhost:5678)
```bash
n8n 

```
## 2. Import the Workflow JSON

- Open the **n8n Editor**
- Click on **Workflows > Import from File**
- Select the `.json` file you received or created
- Click **Import**

## 3. Configure Any Required Credentials

If the workflow uses any external APIs or authentication:

- Go to **Credentials > Create New**
- Fill in the required details (API keys, headers, etc.)
- Attach them to the appropriate **HTTP Request** or **scraping node**

## 4. Run the Workflow

- Click **Execute Node** or **Execute Workflow**
- You’ll see the scraped data in the output (**JSON format**)








