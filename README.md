Final Project for CIS 1051 Fall 2025:
Email  Analyzer

A AI powered tool that connects to your email to detect/analyze possible phishing threats. The application provides three modes for email security analysis.

Features:

  Check Specific Email: Analyze individual emails in detail

  Builk Analysis: Scan recent emails (last 7 days) for potential phishing emails
  
  Auto Scan: Will continously scan for threats and delete them
  



The tool uses AI to feed the email data such as text, sender, and emails to Deepseek LLM for analyzes adn then outputs it to the user for the option to the email(s) or not.


Requirements
Gmail account only (currently)
Google OAuth2 credentials (client_secret.json)
DeepSeek API key
Python dependencies: google-auth-oauthlib, imap-tools, rich, requests

Challenges I Had:
1. Oauth Oauth Oauth, I spent so long trying to get Oauth2.0 to work. At one point I wanted to scrap the idea because I thought it was no point in getting everything working but having to use a no noname email proivder. in genreal i would figure one thing out and then another issue would arise and it felt like that for a while but a lot of the challenges I had with Oauth were regarding the refresh token and getting everything configured properly in Google Dev Panel.
2. I used PyInstaller for the .exe file adn I ran into a issue where the icon would apepar very tiny. I could not resolve the issue and eventually found a workarond utilizing Rehacker to change the Icon


Final Thoughts:
I really had fun building this project was actually really fun. I really liked utilizing imap-tools it made the whole email process so easy and I if I ever do any other email absed projects I would absolutely use it. My favortie new thing I learnt was the RICH Library, I liked being able to make my output look different and unique and I feel like it gave me many options. One key takeaway i learnt from this project is the need to organize your code and add comments. There were many occasions where I would code something and then come back and forget what exactly my code is doing, or how specfic libraries works. As for PhishPy i think I will continue to improve it and make it better and to be completely honest I plan to use it.
