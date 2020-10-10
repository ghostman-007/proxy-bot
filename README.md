# Proxy Bot
This is an automated script developed with the intension of utilizing precious time in doing high priority tasks without losing attendance.

## Table of contents
* [Features](#features)
* [Requirements](#requirements)
* [Installation](#installation)
* [Errors you may come across](#errors-you-may-come-across)
* [Motivation](#motivation)

## Features
* Disable Camera
* Disable Mic
* Join lecture at the scheduled time
* Mark attendance in the chat
* Save all chats
* Leave class when people are less than 5
* can pursue other tasks while the script is running
* anytime take over from the bot

## Requirements
* Google Chrome
* Chormedriver
* Python 3.0+
  * Python Libraries
    * selenium
    * jupyter notebook
    
## Installation
1. Clone the repo to your local pc
2. Open PROXY_BOT.ipynb and make changes written in it
3. Run PROXY_BOT.ipynb
4. In the opened chrome tab add a user using which you want to join lectures
5. Stop PROXY_BOT.ipynb and close google chrome
6. Now whenever you want to attend the lecture just change the time in PROXY_BOT.ipynb and run it.

## Errors you may come across
* Couldn't sign you in
  * If you are signing in through Gmail account then you have to Turn OFF "2-Step Verification" and Turn ON "Less secure app access" in Security Option in Google Account Settings.

* You can't join the video call
  * You may have not signed in your google account.
  
 ## Motivation
1. Bunking lectures when already have the knowledge of the topics to be taught.
2. To join lectures on time having strict time constraints.
