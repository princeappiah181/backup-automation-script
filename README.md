# 🔐 Automated Daily Backup Script with Bash and Cron

This project was developed as the final assignment for the IBM course: Linux Commands & Shell Scripting Essentials on Coursera. It automates the process of backing up 
encrypted password files that were modified in the last 24 hours.


## 🧾 Scenario

You are the lead Linux developer at ABC International Inc. The company is facing a serious bottleneck: interns must manually access encrypted password files
on core servers and back up any that have been modified in the last 24 hours. This process is error-prone, time-consuming, and insecure.
As one of ABC Inc.'s most trusted Linux engineers, your task is to write a Bash script, `backup.sh`, that automates this process securely and reliably.



## 💡 What the Script Does

- Identifies all regular files in a specified directory that were modified in the last 24 hours
- Archives and compresses those files into a timestamped `.tar.gz` file
- Moves the archive to a designated backup destination
- Can be run manually or automatically via a scheduled cron job



## 📂 Files Included

- `backup.sh` – The main backup script
- `Testing the backup_sh.rtf` – Instructions used for testing and validating the script (as part of the IBM course)

