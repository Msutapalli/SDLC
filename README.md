

# Laurel Bot - The HR Bot
[![GitHub version](https://badge.fury.io/gh/boennemann%2Fbadges.svg)](http://badge.fury.io/gh/boennemann%2Fbadges)

![mil-dark-caption-logo](https://user-images.githubusercontent.com/25320466/42839454-c7b069ce-89d1-11e8-9103-3765bcd251ed.png)

---
**Author** : Manasa Sutapalli\
**Project Manager** : Akash Pavate\
**Created On** : 07/16/2018\
**Last Revision** : 07/17/2018\
**Reviewed By** : Chanakya Lokam

---
## Quick Start

#### Technology Stack

The following are the technologies should be used for developing this use case. 

**Code Editor** : Visual Studio
**Version** : 2015 
**Hosting Server** : Microsoft Azure
**Bot Framework** : Microsoft Bot Framework, LUIS

#### Setup Instructions
Install Visual Studio 2015 - [https://msdn.microsoft.com/en-us/library/e2h7fzkw.aspx](https://msdn.microsoft.com/en-us/library/e2h7fzkw.aspx)

Access to Microsoft Azure - [https://portal.azure.com/](https://portal.azure.com/)

Access to MS Bot Framework - [https://dev.botframework.com/bots/new](https://dev.botframework.com/bots/new)

---
## Detailed Documentation

#### Introduction
*Should keep overview of our application/use case*
HR Bot is a virtual HR which can help us with multiple services like booking a conference room, paycheck details, holiday details, transportation details and for applying for leave. It has the capability of sending proactive messages to all the users after getting the payslip every month. 

#### Functions And Features
*Application architecture can be found in /docs*

- Dialog flow for the bot using MS Bot Framework
- Multi-channel integration for MS Teams, Skype, Slack, SFB
- Able to change from one dialog to another in the middle of active dialog
- Spell Check and Sentiment Analysis
- Conversations should be based on intent matching

#### Basic Terminology
##### Natural Language Processing
NLP consists of systematic processes for analyzing, understanding, and deriving information from the text data in a smart and efficient manner. By utilizing NLP and its components, we can organize the massive chunks of text data, perform numerous automated tasks and solve a wide range of problems.
 
##### Dialog Flow
**User** : Hello\
**Bot** : Hello!!! I'm Laurel Bot, how can I help you?\
**User** : What can you do?\
**Bot** : I can help you with booking a conference room, paycheck details, apply for leave.\
**User** : Book a conference room\
**Bot** : Sure, I can help you with that. May I know the date for which you need a room? (Ex. 25 July 2018 or 07/25/2018)\
**User** :  24 July 2018\
**Bot** : At what time will you be checking in ? (Ex. 1:30 pm)\
**User** : 12.30PM\
**Bot** : For how long (in minutes) would you use the room ?\
**User** : 60mins\
**Bot** : How many people would be joining in ?\
**User** : 10\
**Bot** : So, you want to reserve a conference room on Friday, September 22, 2017 from 11:00 AM to 12:00 PM with a capacity of 8 people.\
**User** : Thank you

*Should continue the same flow for other use cases as well*

##### Flow Diagram

*Add flow of the use-case*

#### Scope
HR Bot is like a virtual HR which can help us with multiple services like booking a conference room, paycheck details, Holiday details, Transportation details and applying for leave. It has the capability of sending proactive messages after getting the payslip every month. 

*Write more details about the use case*

#### Configuration Management

*Need to keep information about GIT and VSTS*
