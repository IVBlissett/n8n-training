# n8n-training
# Instagram Post Scheduler

This is an automation workflow built with n8n.  
The goal is to schedule and organize Instagram posts using a Google Sheet, and send reminders or export content to other tools.

## Project Idea

I wanted to automate my Instagram posting schedule. This system uses a Google Sheet to manage upcoming posts, and n8n to trigger reminders or move posts into the proper format when the scheduled time arrives.

## Workflow Plan

- Trigger: Cron job (runs every hour)
- Source: Google Sheet with columns: Date, Caption, Image URL
- Logic: Check if any post is due (based on current date/time)
- Action: Send a Telegram reminder or format post content for upload

## Tools Used

- n8n
- Google Sheets
- Cron node
- Telegram or Email (for notifications)

## Future Ideas

- Automatically post to Instagram via Meta Graph API
- Use Airtable instead of Google Sheets for better content tracking
- Generate captions using AI
