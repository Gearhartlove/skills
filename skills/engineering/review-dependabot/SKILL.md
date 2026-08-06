---
name: dependabot-review
description: Review a dependabot pr. Invoke when a user what's to review a dependabot PR.
---

It's common for me to want to review a dependabot PR which upgrades dependencies in my repository. What I'm interested in at a high level is whether the change is an "easy upgrade" or if it requires more testing and care. Apart of these PR's we already have the ability to test the application through CI checks, but it's important to note that this does not cover every use case.

Your task is to review the dependabot PR. Understand what is changing, in the context of the application, and help the reviewer understand the blast radius.

The analysis should include: 
- verdict (yes/no easy merge)
- details

