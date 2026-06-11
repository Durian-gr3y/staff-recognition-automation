## Staff Recognition Automation
**Tool:** Microsoft Power Automate
**Organisation type:** NGO / People-centred organisation

### The Problem
There was no system in place — manual or automated — for recognising staff birthdays 
or work anniversaries. No emails were being sent, and no one was tracking which staff 
member's special day fell on a given date.

### What I Built
The workflow runs on a daily schedule and pulls every row from the staff directory 
Excel table. It loops through each staff member, checking whether today's date matches 
their birthday or their work anniversary. When a match is found, it sends a personalised 
email celebrating the occasion, logs the event, and updates a running count and name 
list for that category. After processing every staff member, it sends a single summary 
email reporting how many birthday and anniversary emails were sent that day, and to whom.

### Impact
Staff are now automatically and consistently recognised on their birthdays and work 
anniversaries — something that previously never happened at all. There's no manual 
checking, no risk of someone being missed, and the daily summary plus logging gives 
full visibility into who was emailed and when.

### Files in This Repo
- /screenshots — workflow screenshots
- staff_template.xlsx — anonymised data structure
- workflow_package.zip — exportable Power Automate package





