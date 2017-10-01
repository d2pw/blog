---
layout:     post
title:      "Install Preventive Controls"
subtitle:   "Prevention has many forms."
date:       2017-02-16 12:00:00
author:     "dario"
header-img: "img/install-preventive-controls.jpg"
header-credit-link: https://pixabay.com/en/computers-information-technology-2652997/
---

## Install Preventive Controls

### Firewalls
A firewall is a network security system designed to prevent unauthorized access to or from a private network. Firewalls can be implemented as both hardware and software, or a combination of both. All messages entering or leaving the intranet pass through the firewall, which examines each message and blocks those that do not meet the specified security criteria. Next Generation Firewalls (NGFWs) blend the features of a standard firewall with quality of service (QoS) functionalities in order to provide smarter and deeper inspection.

### Intrusion prevention systems IPS
An Intrusion Prevention System (IPS) is a network security/threat prevention technology that examines network traffic flows to detect and prevent vulnerability exploits.

**Prevention**  
The IPS often sits directly behind the firewall and provides a complementary layer of analysis that negatively selects for dangerous content. Specifically, these actions include:

* Sending an alarm to the administrator (as would be seen in an IDS)
* Dropping the malicious packets
* Blocking traffic from the source address
* Resetting the connection

**Detection**  
The IPS has a number of detection methods for finding exploits, but signature-based detection and statistical anomaly-based detection are the two dominant mechanisms.

### Endpoint security
Endpoint security is the process of securing the various endpoints on a network, often defined as end-user devices such as mobile devices, laptops, and desktop PCs

**DIFFERENTIATING ENDPOINT SECURITY FROM ANTI-VIRUS SOFTWARE**  
What differentiates endpoint security from the well-known anti-virus software is that within the endpoint security framework, endpoints bear some or all responsibility for their own security. This is in contrast to network security, in which security measures encompass the network as a whole rather than individual devices and servers.

**Endpoint security products may contain features and functionality such as:**

* Data loss prevention
* Insider threat protection
* Disk, endpoint, and email encryption
* Application whitelisting or control
* Network access control
* Data classification
* Endpoint detection and response
* Privileged user control

Endpoint security isn’t solely conducted from devices, however. Typical endpoint security solutions provide a two-pronged approach, with security software installed on a central server or management console along with software installed on individual devices.

### System-Level Protection
While it is impossible to completely block ransomware at its two most common points of entry (i.e. email and websites), steps can be taken at the system-level that will reduce (but not completely eliminate) ransomware attacks. First and foremost, it is important to note that current anti-malware products should be able to detect and block ransomware at the file and process level before data can be compromised. A well-designed anti-malware product should also be able to scan email attachments and downloads for malicious content. I emphasize should in these statements because ransomware evolves so rapidly that it is not a guarantee that even up-to-date anti-malware products will detect the latest strains.

**At the Network Level**  
At the network level, it has proved more difficult to mitigate and prevent the spread of ransomware. Firewalls that implement whitelisting or robust blacklisting will be a successful deterrent to lessening the likelihood of successful web-based malware downloads and may deter ransomware from connecting to command-and-control servers.
