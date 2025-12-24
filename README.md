Google Drive → Airtable Automation (n8n)

This project contains an n8n workflow that automates actions between Google Drive and Airtable.

🚀 What the Workflow Does

- Monitors a specific Google Drive folder

- Uses a Google Drive Trigger node

- Checks every minute for newly created files

- Automatically shares the new file

- Shares the file with a predefined email address

- Grants writer permission

- Logs file details into Airtable

- Creates a new record in an Airtable table

Stores:

- File ID

- File creation time

- Recipient email address

🛠 Tools & Technologies

- n8n – workflow automation

- Google Drive API – file monitoring and sharing

- Airtable API – data storage and tracking

📂 Use Case Examples

- Track newly uploaded files in shared folders

- Automatically give access to team members

- Maintain an audit log of shared files

- Integrate Google Drive events with no-code databases

🔧 Workflow Overview
Google Drive Trigger
        ↓
Share File (Google Drive)
        ↓
Create Record (Airtable)

⚙️ Setup Requirements

- n8n instance (local or cloud)

- Google Drive OAuth credentials

- Airtable Personal Access Token

- Access to the target Google Drive folder and Airtable base

📌 Notes

- The workflow is currently inactive by default

- Polling interval is set to every minute

- Folder and email can be customized easily
