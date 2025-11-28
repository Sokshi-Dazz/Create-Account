📌 HP Smart Account Automation
This repository contains an end-to-end automation for HP Smart Desktop App account sign-up, using a hybrid of desktop and web automation:

PyWinAuto → Automates the HP Smart Windows desktop application
Selenium WebDriver → Opens Mailsac, checks inbox and reads OTP emails
Dynamic test data → Random first name, last name and email for each run
HTML reports → Detailed step-by-step execution logs


🎯 Automation Flow

Launch the HP Smart Desktop App.
Navigate to the Create Account page.
Fill the sign-up form with:
Random first name
Random last name
Unique Mailsac email address
Open the corresponding Mailsac inbox in Chrome.
Poll the inbox and extract the 6-digit OTP from the latest email.
Switch back to HP Smart and enter the OTP in the verification screen.
Complete account creation and generate an HTML execution report.
