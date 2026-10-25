# On-Call Quest 🚨

A browser game for learning DevOps and AWS and getting ready for interviews. "Your pager is on": you work through 13 zones, earning XP and badges, and finish with a mock interview.

Explanations are in English, with Tanglish (Tamil + English) tips and analogies so the concepts stick.

## Zones

1. Linux Ground Floor
2. Networking Wires
3. Git Vault
4. Container Dock
5. Kubernetes Harbor
6. Pipeline Works
7. IaC Foundry
8. AWS Gate: IAM & EC2
9. AWS Network City: VPC
10. AWS Storage & DB Vault
11. AWS Scale & Serverless Lab
12. SRE Watchtower
13. Final Boss: The Interview

## Features

- **Lessons and quizzes**: concept cards and MCQs for each zone
- **Hands-on labs**: step-by-step commands, a verify checklist, cleanup steps and a resume line
- **Interview Simulator**: practice spoken-style answers to common DevOps/AWS questions
- **XP, ranks, streaks and badges**: your progress is saved in the browser (localStorage)
- **Revision list**: a list of questions to go back and review

## Run it

There's nothing to install. It's one self-contained `index.html` file.

- Open `index.html` in any browser, **or**
- Serve it locally: `python -m http.server` and go to http://localhost:8000

## Tech

Plain HTML, CSS and JavaScript in a single file. There's no build step and no dependencies.
