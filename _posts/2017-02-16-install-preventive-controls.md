---
layout:     post
title:      "Install preventive controls to minimize risk"
subtitle:   "Prevention has many forms."
date:       2017-02-16 12:00:00
permalink:  install-preventive-controls
author:     "dario"
header-img: "img/install-preventive-controls.jpg"
header-credit-link: https://pixabay.com/en/computers-information-technology-2652997/
---

## Safeguards to detect, avoid, and mitigate threats

### Firewalls
A firewall is a network security system designed to prevent unauthorized access to or from a private network. Firewalls can be implemented as both hardware and software, or a combination of both. All messages entering or leaving the intranet pass through the firewall, which examines each message and blocks those that do not meet the specified security criteria. Next-generation firewalls (NGFWs) blend the features of a standard firewall with quality of service (QoS) functionalities in order to provide smarter and deeper inspection.

### Intrusion prevention systems (IPS)
An IPS is a network-security/threat-prevention technology that examines network traffic flows to detect and prevent vulnerability exploits.

**Prevention**  
The IPS often sits directly behind the firewall and provides a complementary layer of analysis that negatively selects for dangerous content. Specifically, these actions include:

* Sending an alarm to the administrator (as would be seen in an [**IDS**]({{ site.baseurl }}{% post_url 2017-06-19-audit-trails %}))
* Dropping the malicious packets
* Blocking traffic from the source address
* Resetting the connection

**Detection**  
The IPS has a number of detection methods for finding exploits, but signature-based detection and statistical anomaly-based detection are the two dominant mechanisms.

### Endpoint security
Endpoint security is the process of securing the various endpoints on a network, often defined as end-user devices such as mobile devices, laptops, and desktop PCs.

**Differentiating endpoint security from anti-virus software**  
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
