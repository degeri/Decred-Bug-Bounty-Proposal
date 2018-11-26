# Decred-Bug-Bounty-Proposal

# What:

I suggest we start a bug bounty program to find security vulnerabilities in decred. This would help us improve our overall security posture and get a fresh set of eyes on our code and websites.


# Why:

We do not currently have a formal bug bounty program. A bug bounty program aims to use collective intelligence of many "bug bounty hunters" to find and fix security vulnerabilities. 

Many times I observe people visiting our chatrooms and inquiring about a bug bounty program which shows there is a real interest in people who want to find vulnerabilities in decred and report them for an award.Having a formal program will enable us to funnel all reports through one single process and ensure that valid reports are looked at and fixed  while keeping away bad reports that take up valuable dev time.

# How:

We will have a selfhosted program and use a @decred.org email for getting bug bounty reports.The bug bounty hunters will be sending us PGP encrypted emails of their findings in a predefined format. 



1. We will be using the CVSS v3.0 system for scoring and prioritizing vulnerabilities (https://www.first.org/cvss/calculator/3.0)

2. We will also take into consideration the impact on the decred ecosystem. An RCE in dcrdocs (Low impact) is not the same as an RCE in dcrd or decrediton (Higher impact)

Indicative payout amounts:

Low: 50 - 300 USD 

Medium: 300 - 1500 USD

High: 1500 - 5000 USD

Critical: Above 5000 USD



To achieve all this we need a group of "vulnerability validators" who are verified decred contractors. Their jobs is as follows.

    - Check, validate and respond to all bug reports sent to the system.

    - If its a serious vulnerability escalate the vulnerability to the person in-charge of the project and core staff.

    - If its a non serious open an issue in github and follow through on fixes.

    - Maintain constant contact with the bug reporter and keep them apprised on the status of their report.(Many times I see frustrated bug reporters complain on twitter or publicly release 0-day bugs due to security teams not responding properly to their reports) 

    - Form a core team that decides on any payout above 500$. (Anything below this can be given out at their discretion)
  

* We will need to do some social media posts to get the word out.

* We need to define the bug bounty policy/rules and scope.

* Setup a simple website bounty.decred.org which will contain information about the program,rules and scope.

* Setup a "Thank you" page in the "bounty.decred.org" website to publicly appreciate the people who have found valid vulnerabilities.


**Who:**

* I have been working with the decred project the last few months and would like to believe I have contributed in a useful manner to decred. I also have prior experience as both a bug hunter and a validator and think I would be a good fit for this role.  Hence I nominate myself as a validator for this project.

* Welcome any other decred contractors to join in on this. 

Current Validator List: dnldd, Degeri (me), matheusd

WebSite Development: fernandoabolafio, Degeri (me)

**Costing and Funds:**

* The DCR for this project will stay with the treasury and we send them bi-weekly or monthly requests to release the funds directly to the bug bounty hunters Decred address or towards operation costs if any. 

* The validators who will already be contractors of decred and can bill the decred project directly for hours spent on this work.

* I don't see each validator spending more than 20-30 hours a month. 

**Cost Breakdown**


* An operating fund of 5000 USD for six months.

This will cover the following:
    - Setting up and Maintaining the bounty website.  (2000 USD)
        Breakdown:
        -5 Hours * 7 Days = 35 Hours * 40usd/hour = 1400 USD for Web Development 
            200 USD completion bonus
        - 10 Hours * 40usd/hour= 400 USD for any other minor edits during the 6 months.
  - Defining policies/rules and scope (1000 USD)
  - Anything other non bounty expenditure like setting up email system, book keeping etc . (2000 USD) 


Since we cannot predict the types of vulnerabilities and their severity it is not possible to have a fixed payout limit. But based on past trends and other bug bounty programs I predict that this would not cross **100000 USD for 6 months**.

Note: (Since we suggest the treasury spend the money directly any excess will be available for other proposals and spending) 

**When and Duration:**

 * I suggest we plan to get this up for vote in one week. And launch the bug bounty project by the last week of December or January first week.

 * This project would be approved for 6 months the end of which I will compile a detailed report for the community and if all goes well request for another 6 months extension using a revised proposal. 

**Work Flow**

![alt text](https://raw.githubusercontent.com/degeri/Decred-Bug-Bounty-Proposal/master/workflow.png)


Below is a sample programs rules and scope:

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


**Introduction:**


The decred community welcomes security researchers and bug bounty hunters to find security vulnerabilities in its website and projects. (more text to follow). All bug reports need to have a clear exploit or POC. 

**The following domains and decred projects are in scope:**

*.decred.com

*.dcrdata.org

**Projects in scope : **

All current projects under.

https://github.com/decred/

**Not in scope:**

https://slack.decred.org/ (Slack)

++add more later

**The following vulnerabilities are generally out of scope:**

* Missing security best practices that do not directly lead to a vulnerability

* Insecure settings in non-sensitive cookies

* Vulnerabilities (including XSS) that affect only legacy browser/plugins

* Non-technical attacks such as social engineering, phishing, or physical attacks against our members, users, or infrastructure

* Missing HTTP headers, unless a vulnerability can be demonstrated

* Bugs requiring exceedingly unlikely user interaction

* Clickjacking on pages with no sensitive actions.

**Rules:**

* We prohibit DDOS or network bandwidth load testing.

* No social engineering.

* No spamming.


**Reminders:**

* Almost all of decred's projects can be run locally and reproduction instruction are available on github. We strongly recommend you to do this.

* Only test the code in the "main" merged branch of the projects.

* Use the testnet when possible.

* Decred project is not responsible for any loss of DCR due to bug testing. (ie: don't do dumb stuff and lose your DCR)

* All Current/Past (For up-to 6 months) decred developers are barred from taking part in this bug bounty program. 

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

crypto related programs (What we can expect):

https://hackerone.com/monero/hacktivity?sort_type=latest_disclosable_activity_at&filter=type%3Apublic&page=1

https://hackerone.com/brave/hacktivity?sort_type=latest_disclosable_activity_at&filter=type%3Apublic&page=1

https://hackerone.com/augurproject/hacktivity?sort_type=latest_disclosable_activity_at&filter=type%3Apublic&page=1

https://hackerone.com/myetherwallet/hacktivity?sort_type=latest_disclosable_activity_at&filter=type%3Apublic&page=1

https://hackerone.com/tronfoundation/hacktivity?sort_type=latest_disclosable_activity_at&filter=type%3Aall%20to%3Atronfoundation&page=1 (Nothing has been disclosed yet)

https://hackerone.com/hyperledger/hacktivity (Nothing has been disclosed yet)

https://ww2.bugcrowd.com/rs/453-IJC-858/images/bugcrowd-dash-case-study-2018.pdf

https://bugcrowd.com/binance

https://blog.lisk.io/announcing-lisk-bug-bounty-program-5895bdd46ed4

https://bounty.ethereum.org/

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
