# 0x19. Postmortem
:open_file_folder: Foundations - System engineering & DevOps  On call  
:bust_in_silhouette: by Sylvain Kalache  
:copyright: **[Holberton School](https://www.holbertonschool.com/)**

## Background Context
Any software system will eventually fail, and that failure can come stem from a wide range of possible factors: bugs, traffic spikes, security issues, hardware failures, natural disasters, human error Failing is normal and failing is actually a great opportunity to learn and improve. Any great Software Engineer must learn from his/her mistakes to make sure that they wont happen again. Failing is fine, but failing twice because of the same issue is not.

A postmortem is a tool widely used in the tech industry. After any outage, the team(s) in charge of the system will write a summary that has 2 main goals:
  - To provide the rest of the companys employees easy access to information detailing the cause of the outage. Often outages can have a huge impact on a company, so managers and executives have to understand what happened and how it will impact their work.
  - And to ensure that the root cause(s) of the outage has been discovered and that measures are taken to make sure it will be fixed.

## Resources
* [Postmortem](https://www.youtube.com/watch?v=rp5cVMNmbro&feature=youtu.be)
* [Incident Report, also referred to as a Postmortem](https://sysadmincasts.com/episodes/20-how-to-write-an-incident-report-postmortem)
* [How to run a Postmortem](https://blog.serverdensity.com/how-to-write-a-postmortem/)

## Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/2012/04/feynman-technique/), without the help of Google:
###### General
* Postmortem

## Requirements
###### General
* Issue Summary (that is often what executives will read) must contain:
  - duration of the outage with start and end times (including timezone)
  - what was the impact (what service was down/slow? What were user experiencing? How many % of the users were affected?)
  - what was the root cause
* Timeline (format bullet point, format: time - keep it short, 1 or 2 sentences) must contain:
  - when was the issue detected
  - how was the issue detected (monitoring alert, an engineer noticed something, a customer complained)
  - actions taken (what parts of the system were investigated, what were the assumption on the root cause of the issue)
  - misleading investigation/debugging paths that were taken
  - which team/individuals was the incident escalated to
  - how the incident was resolved
* Root cause and resolution must contain:
  - explain in detail what was causing the issue
  - explain in detail how the issue was fixed
* Corrective and preventative measures must contain:
  - what are the things that can be improved/fixed (broadly speaking)
  - a list of tasks to address the issue (be very specific, like a TODO, example: patch Nginx server, add monitoring on server memory)

Be brief and straight to the point, between 400 to 600 words

## Tasks
* [x] 0. My first postmortem
* [x] 1. Make people want to read your postmortem

## Software Developer
Built by [Javi](https://github.com/javi0b01) :copyright: 2019 - 2020  
Found a bug or have an idea? [Contact me](https://www.linkedin.com/in/javi0b01/).
