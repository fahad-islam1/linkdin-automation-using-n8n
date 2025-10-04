LinkedIn Automation with n8n

Automate your LinkedIn posting workflow using n8n, Google Sheets, Trwly AI, and OpenAI.
This project fetches topics from Google Sheets, generates content & images (if missing), schedules posts, and publishes them directly on LinkedIn.

🚀 Features

Google Sheets Integration – Store topics, captions, images, and scheduling info in a sheet.

Scheduled Posting – Automatically schedule posts at predefined times.

AI-Powered Content – Generate engaging LinkedIn content using Trwly AI and OpenAI.

AI Image Generation – Create visuals if no image is provided.

Seamless LinkedIn Publishing – Post both text and images automatically.

Error Handling & Logs – Track results and troubleshoot easily.

🛠️ Tech Stack

n8n
 – Workflow automation

Google Sheets – Content & schedule source

Tavily AI
 – Content generator

OpenAI
 – Text & image generation

LinkedIn API – Publishing posts

📂 Workflow Overview

Trigger – Reads data from Google Sheets.

Scheduler – Checks scheduled posting time.

AI Content – Generates LinkedIn post content if empty.

AI Image – Creates an image if missing.

LinkedIn API – Publishes the post.

Logging – Updates Google Sheet with results or errors.

⚙️ Setup Instructions
1. Clone Repo

cd linkedin-automation

2. Setup n8n

Install n8n locally or deploy on server/Docker.

Import the provided workflow JSON.

3. Configure Credentials

Add Google Sheets API credentials.

Add Trwly AI / OpenAI API key.

Add LinkedIn API token.

4. Update Google Sheet


5. Run Workflow

Start n8n.

Workflow will automatically check your sheet and post to LinkedIn.

🌐 Use Cases

Marketing agencies automating LinkedIn campaigns

Personal branding with consistent AI-powered posts

Teams managing multiple client accounts
