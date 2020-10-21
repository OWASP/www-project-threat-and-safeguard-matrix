---

layout: col-sidebar
title: OWASP Threat and Safeguard Matrix (TaSM)
tags: example-tag
level: 1
type: 
pitch: A very brief, one-line description of your project

---
# Introduction
The Threat and Safeguard Matrix or (TaSM) is an action oriented view to safeguard and enable the business created by Ross Young.  It started with a thought that we often list our greatest threats to our company in a risk register, but fail to actually provide a defense in depth plan to address them.  Simply put if Cyber is in the business of Revenue Protection, then we need to have a well though out plan against the biggest threats to our company.  This is where the functions (Identify, Protect, Detect, Respond, & Recover) of the NIST Cyber Security Framework come into play

Example if you were to look across the information security industry you would notice that the largest data breaches against companies often involve Phishing, Ransomware, Web Application Attacks, and Vendor/Partner Data Loss.

![TaSM](https://github.com/OWASP/www-project-threat-and-safeguard-matrix/blob/main/assets/images/TaSM%20Matrix.png)

# How does it work?

## Threats
CNSS defines a **Threat** as any event with the potential to adversely impact organizational operations.
Common Examples of Threat types can be found in the STRIDE-LM matrix
![STRIDE-LM](https://github.com/OWASP/www-project-threat-and-safeguard-matrix/blob/main/assets/images/StrideLM.png)

## Functions & Safeguards

The 5 NIST Cyber Security Framework Functions
#### Identify 
The identify function assists in developing an organizational understanding of managing risk to systems, people, assets, data, and capabilities.  
**Key Objective**: Identify all people, proccesses, or systems that would be vulnerable to this type of threat.  
#### Protect
The protect function supports the ability to limit or contain the impact of the threat. 
**Key Objective**: How could you limit the threat of a an attack by removing or blocking the vulnerability
#### Detect
The detect function defines the activities to identify the occurence of an event in a timely mannner.  
**Key Objective**: If you couldn't stop the threat (ie protect phase) how would you know it's even happening and your company is experiencing harm
#### Respond
The respond function includes appropriate activities regarding an incident to minimize impact.  
**Key Objective**: If the threat has been realized how do you prevent additional financial damage, reputation damage, non compliance, or privacy violations 
#### Recover
The recover function includes identifying appropriate activities to maintain plans for resilience and to restore services impaired during cybersuecrity incidents.  
**Key Objective**: How do you get to a state that was equal or better than before the incident

## Safeguards
**Safeguards** are Actions, devices, procedures, techniques, or other measures that reduce the vulnerability of an information system. Synonymous with security controls and Countermeasures.  Please note you can see the [108 different safeguards outlined by NIST CSF](https://github.com/OWASP/www-project-threat-and-safeguard-matrix/blob/main/Nist_CSF_Safeguards).

# Example TaSM
![Example TaSM](https://github.com/OWASP/www-project-threat-and-safeguard-matrix/blob/main/assets/images/CompletedTaSM.png)


layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar

title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore

tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 

level: For projects, this is your project level (2 - Incubator, 3 - Lab, 4 - Flagship)

type: code, tool, documentation, or other
