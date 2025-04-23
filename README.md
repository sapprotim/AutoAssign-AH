AH NudgePilot

Excel-driven Selenium automation for the AH CMS: logs in, handles OTP, and assigns 40+ custom alerts & nudges across 3 study arms. Processes up to 1,000 assignments daily, hands-free.

🚀 Features

Auto Login & OTP

Navigate Programme Management → Alerts/Nudges

Read user_list.xlsx & Alerts_Nudge_list.xlsx

Batch Assign alerts & nudges

Console Logs for real-time tracking

Safe Teardown: quits browser on completion

⚙️ Setup

Add Credentials

Create credentials.json in the root:

{"username":"YOUR_USER","password":"YOUR_PASS","otp":222222}

Prepare Excel Files

user_list.xlsx: columns for each study arm

Alerts_Nudge_list.xlsx: matching alert/nudge titles

▶️ Usage

python autofetch_ah.py

Internal use only – keep credentials private.
