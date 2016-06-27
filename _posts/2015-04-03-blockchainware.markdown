---
layout: post
title:  "Blockchain-ware: Next stage of malware evolution."
date:   2015-04-03 17:28:17 +0530
categories: blockchain economics malware  
---
Blockchain is amazing piece of technology from payment perspective where by offering users a decentralized system of payments across the globe, with adequate amount of privacy and security. However the certain functionality of Blockchain can be used for nefarious purposes especially by malcoders. Some of them being encoding components of malware within Blockchain transactions or by using it for purpose of command and control mechanism (i.e. Similar to Zeus controler used in Zeus botnet ).

### Use of Blockchain as a storage for malware components.
Any executable (PE File )can be broken down into sections of code. (i.e. - .data, .text .bss etc ) Most of the malwares now a days are packed malwares by using method of execution compression. There by limiting the sections to two sections only. But if smartly done multiple sections can be hand crafted or custom made such that each section serves as a library for specific calls.

The Blockchain transaction have functionality of inserting comments in to transactions which is in turn kept into the Blockchain till eternity. Since the Blockchain is decentralised all the malcoders needs to do is insert various sections of the malware in the comments section of the transactions (execpt the header ) or store various section using decentralized stroage platform using Blockchains, and develop a header (Actual exe which runs on infected system) which would query the Blockchain and perform designated malicious activities.

### Use of Blockchain as a Command and control center.
Bot-nets operate in command and control model. The attacker can use the comment section of transaction from a specific address to broadcast messages to bots / infected system for their future course of actions. (i.e. Attack a specific system / target or DDoS a Server etc ) However this method can be prety devastating if the data in comments is encrypted. The current advancement in Blockchain technology (i.e :- Making the Blockchain Turing complete and having functional programmable language inside the Blockchain) may assist this cause.

However adverse the situation may be there is always a way out and it could this either mean a new set of Blockchain based Security Products for Antivirus Companies (specific for bitcoin users / providers ) or additional security consideration to core developers of respective decentralized platforms?
