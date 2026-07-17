---
name: log-hunt
description: Hunt through application logs and permitworld to identify a problem and suggest a candidate fix if possible. Use when the user wants you to sift through logs to find an occurance of a bug.
---

Use the `/dash0-cli` skill to sift through logs. 
You can assume the logs are from the last 24 hours unless specified otherwise.
If the user has not provided a breadcrumb of what to look for, ask them for it.

After finding the log, synthesize your findings by looking through the permitworld repository (/Users/frisco/src/work/permitworld
). 

Present your findings and understanding to the user.
