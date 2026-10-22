# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The problem within this project was based on a fictional company named Northstar Medical Group. They are a fast growing company who delegated their Identity Lifecycle workflow to a third party MSP. In the beginning, this was fine however as this company grew the issues began to show. They had no RBAC policy. Users were assigned access AD-HOC. There were no audit trails and many HIPPA risks.

## Solution Overview
The solution was to build a basic employee onboarding pipeline in active directory. I then set up the RBAC matrix and ensured users were granted access ONLY according their roles. I also simulated a mock ticket where a user was granted the incorrect level of access.


## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Set up two separate Domain Servers from Scratch (Woods.com and NMG Server)
* Created users and placed them in the correct OU and Security Groups
