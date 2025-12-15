---

layout: col-sidebar
title: OWASP Threat and Safeguard Matrix (TaSM)
tags: TaSM
level: 2
type: documentation

---
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

# Introduction
The Threat and Safeguard Matrix (TaSM) is an action-oriented view to safeguard and enable the business created by [CISO Tradecraft](https://www.cisotradecraft.com/).  Simply put if Cyber is in the Business of Revenue Protection, then we need to have a defense in depth plan to combat the biggest threats to our companies.  This matrix allows a company to overlay its major threats with the NIST Cyber Security Framework Functions (Identify, Protect, Detect, Respond, & Recover) to build a robust security plan.  Organizations that perform this activity will gain a better understanding of how to protect their company as they fill in safeguards that mitigate important threats.  Remember the devil is in the details, hence why we chose a TaSManian Devil as the project logo.

![Threat and Safeguard Matrix](assets/images/OWASPTASMBlank.png)

Example: If you were to look across the information security industry, then you would notice that the largest threats to companies often involve things like the following: Web Application Attacks, Phishing, 3rd Party Data Loss, Supply Chain Attacks, or Denial of Service. Please note you can add others to the matrix like Insider Threats, User Errors, Fraud, or anything unique to your environment.

Here's one way you might build a defense in depth plan to mitigate these threats for your company.
![Example TaSM](assets/images/TaSMFilledOnly.png)

# Common Examples of Threats
If you are looking for common examples of threats which can cause material loss consider using any of the following scenarios:
1. **Brand Impersonation Scams** – Imposters launch fake websites to sell counterfeit products under your name.
2. **Business Email Compromise** – Employees fall for a phishing scam, handing over usernames, passwords, and even MFA codes.
3. **Business Logic Bugs** – A bug in your trading algorithm generates losses instead of profits.
4. **BYOD Issues** – Remote employees outsource their work, unknowingly involving unauthorized foreign actors from North Korea.
5. **CEO Impersonation** – A fraudster impersonates your CEO with deep fakes on social media, spreading rumors of layoffs and financial troubles tanking your stock price.  Note your CEO doesn't even have social media
6. **Cloud Disruption** – Your cloud provider or SaaS partner goes down, and so does your business continuity.
7. **Compliance Attestation Complications** – Misinterpreting regulations leads to false attestations—and potential legal action.
8. **Credential Theft Issues** – Your open-source project accidentally exposes secret tokens and private keys to sensitive servers and cloud environments.
9. **Customer Rewards Raid** – Digital thieves snatch customer reward points, leaving your support team flooded with angry calls.
10. **Email Overloaded** – Your leadership drowns in endless spam from throwaway Gmail accounts.
11. **Deepfake Deception** – A hyper-realistic deepfake of your CFO tricks the accounts payable team into wiring unauthorized funds.
12. **DDoS/Botnet Attack** – A swarm of bots takes down your website after a controversial corporate statement.
13. **Forum Defacement** – Script kiddies flood your customer help forums with junk, wrecking your brand’s credibility.
14. **Help Desk Hijack** – Impersonators sweet-talk IT support into resetting employee passwords.
15. **Insider Threat** – Departing researchers take sensitive IP to a rival company.
16. **Infected IoT Devices** – Malware takes over your unpatchable IoT devices, turning them into cyber-zombies.
17. **Open Source Trojan** – That “helpful” library your developers installed? It came preloaded with malware and crypto miners.
18. **Prolonged Power Outages** – Natural disasters knock out power, and your operations grind to a halt.
19. **Hardware Exploits** – Nation-state attackers slip implants into your networking gear.
20. **Payment Fraud** – Scammers trick your customers into redirecting payments to their fraudulent accounts.
21. **Private Data is Publicly Exposed** – Sensitive data leaks from a misconfigured public S3 bucket.  Now your secrets are out.
22. **Rogue Access Points** – Rogue networks near your company cafeteria mimic your corporate Wi-Fi to lure in unsuspecting employees.
23. **Wrong Access Permissions** – Sensitive SharePoint data ends up in the hands of the wrong reseller—for years.
24. **Unpatched Laptops** – An employee connects to airport Wi-Fi and unknowingly invites malware onto an unpatched laptop.
25. **Zero-Day Attack** – Hackers exploit a fresh OpenSSL/Log4J vulnerability on your public website before a patch even exists.

* If you are looking for detailed list of threat events from NIST, then consider using [NIST Special Publications 800-30 Appendix E-1](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf)

# Adding Metrics to the Plan
Now that you have built your TaSM, it's important to look at the safeguards you listed and where you have gaps.  Not every safeguard will be as important.  If everything is important, then nothing is truly important.  Think about the safeguards you want to focus on as an organization.  These may be the ones that are the most effective in stopping the threat.  These safeguards may also be where you have the largest opportunity to improve.  Pick a few safeguards that you can place key metrics on and highlight them by adding a red box.  This will allow you to map progress from your metrics to your TaSM.  Remember, what gets measured gets done and what gets done gets funded.
![Adding Metrics to the Matrix](assets/images/TaSMFilledRedBox.png)

# Creating a Cyber Report Card
After outlining the safeguards your organization wants to make improvements on, you should create metrics that matter and place them on a scorecard.  This example has a few things to notice, but feel free to make modifications. Group things into key categories such as Technology, People, Processes, and the Environment.  Note Environment refers to things outside of your organization's control (i.e. Bad actors or external regulators) 

The scorecard is broken down into metrics that can be monitored, measured, and analyzed.  You can think of them as Key Performance Indicators (KPIs) to measure the success of information security activities being performed within an organization.  Remember a good metric displays 4-5 important things:
1. A clear <b>Definition</b> of what the metric means
2. The <b>Status</b> of where the metric is right now as well as during previous points in time
3. A <b>Trend Line</b> to easily highlight if the current status has improved, stayed consistent, or gotten worse
4. A <b>Goal</b> to show a clear definition of done or desired state for the organization to achieve
5. (Optional) The <b>Due Date</b> on when you expect your goal to be achieved in the future.  Note this is optional since you may have metrics that have already hit the goal and just need to maintain compliance going forward.

Finally, use your scorecard to tell a story that can be shared with executive leadership teams.  Please note this story is fictitious and does not reflect an actual company.

<b>Example:</b> This scorecard identifies the risk profile of XYZ organization.  As you can see, we show that 99% of our servers are patching critical vulnerabilities in 20 days.  While these vulnerability numbers are higher than our desired goal of 15 days, we also install tools such as Web Application Firewalls, Proxy Servers, and Antivirus.  These safeguards provide additional protection during gap windows when we can't patch fast enough.  We feel comfortable in our patching program currently but know that this is one of our most volatile metrics.  One area we would like to highlight is only 60% of our software teams were successful during the annual failover exercise.  This means that 40% of our SOX applications would not be available if our primary data center were to experience a major disaster such as loss of power during a hurricane.  We will be taking XYZ actions to help improve this metric.  As you may recall we are hyper-focused on ransomware defenses.  That's why we are very happy to show that we have now achieved successful restoration testing on 100% of critical applications.  This means that if a ransomware actor were able to encrypt our servers, we feel confident in our ability to recover without having to pay the ransom.  We will now be focusing on XYZ to ...

![Cyber Report Card](assets/images/newcybermetrics.jpg)

# Using the TaSM to enhance Threat Modeling
As we look for additional ways to apply the TaSM in an organization, one way the TaSM might be leveraged is within Application Threat Modeling Discussions.  A Threat Model shown by an application team might look like the following:
![Example Threat Model](assets/images/examplethreat.jpg)

Application Development teams might standardize threat categories by using proven threat models such as STRIDE-LM model to identify common threats to applications.
![STRIDE-LM](assets/images/stride.jpg)

Application teams can also combine a STIDE-LM enhanced TaSM with a [data flow diagram](https://d1.awsstatic.com/whitepapers/compliance/pci-dss-compliance-on-aws.pdf?did=wp_card&trk=wp_card).  Note a data flow diagram is a network diagram that shows key attributes such as (Encryption Layers, Access Control Methods, and Data Types).

By using both a STRIDE-LM enhanced TaSM and a Data Flow Diagram application teams can have a simple and effective way to describe their applications and thier perceived threats during architecture review boards.  This can create insightful discussions.  Additionally, architecture review boards might notice that 20% of all applications possess the same findings.  These findings can be communicated to IT leadership for resolution by an enterprise solution.
![Threat Modeling](assets/images/TMplusSTRIDELM.jpg) 

# Using the TaSM to help improve Risk Committees
Since cyber threats are not the only types of threats, we should also look at how the TaSM could be adopted for larger use in Risk Committees.  All that is needed is an additional column to list the organization within a company.  Imagine if each organization shared its top 3-5 threats.  Your Risk Committee could show how the company is mitigating its biggest threats in a <b>Consistent, Adequate, Reasonable, and Effective (CARE)</b> way.  Additionally, it allows the committee to partner together to solve threats from multiple angles.  Example: How might Cyber leverage HR and Legal processes to help respond to Phishing attacks that cause brand damage?

![TaSM in Risk Committees](assets/images/TaSMRiskCommittee.png)

# Using the TaSM to Safeguard against AI Related Threats
Don't forget to use the TaSM against emerging threats such as Artificial Intelligence (AI).  It's a great way to show what an effective strategy might look like for cutting edge threats.  This is extremely helpful when you might need to forecast the breadth of solutions needed to create an effecitve program to stop emerging threats in AI.  

For example: Let's say there are 7 material threats that your company is worried about regarding the use of Generative AI and Large Language Models (LLMs):
1. **Sensitive Data Leaks**: Employees upload sensitive information or intellectual property to unauthorized external LLMs.
2. **Malicious AI Supply Chains**: A developer integrates an AI/ML model contaminated with malware or hidden cryptocurrency miners.
3. **Hallucinated Promises, Real Legal Risks**: Your chatbot falsely commits to outcomes your company cannot deliver, leading to legal exposure.
4. **Data Overexposure**: Training your LLM on unrestricted company research enables insiders to bypass Role-Based Access Controls and access sensitive data.
5. **AI Misuse for Personal Harm**: An employee exploits your LLM’s capabilities to stalk or harass an ex-spouse.
6. **Unethical AI Recommendations**: Your language model makes morally questionable decisions, like suggesting euthanasia to reduce financial strain.
7. **Bias-Fueled Liability**: Loan-issuing AI trained on data fields like sex, race, and age creates legal and reputational risks.

Consider creating the TaSM to showcase how you'd safeguard your organization from the top 4 out of 7 AI threats most relevant to your business. For instance:

![AI Threats](assets/images/AIThreats.png)

This matrix makes it clear that there is no single solution that your company can buy to solve AI security. Each threat demands a unique set of safeguards, highlighting the necessity of a robust, defense-in-depth strategy to effectively counter a diverse range of AI risks and protect your company from material impacts.

# What do the terms mean?
To ensure proper use of the TaSM, be sure to understand the definitions of the terms used within the matrix

### Cyber Security
Cyber security is the Business of Revenue Protection.  Cyber security is all about understanding, managing, and mitigating the risk of your critical data being disclosed (confidentiality), altered (integrity), or denied (availability).  

### Threats
The Committee on National Security Systems (CNSS) defines a **[Threat](https://csrc.nist.gov/glossary/term/threat)** as any event with the potential to adversely impact organizational operations.

### NIST Functions
The 5 NIST Cyber Security Framework Functions allow you to create a defense in-depth strategy that identifies how you will safeguard the business.  

**1) Identify**
The identify function assists in developing an organizational understanding of managing risk to systems, people, assets, data, and capabilities.  Key Objective: Identify all people, processes, or systems that would be vulnerable to this type of threat.  

**2) Protect**
The protect function supports the ability to limit or contain the impact of the threat. Key Objective: How could you limit the threat of an attack by removing or blocking the vulnerability

**3) Detect**
The detect function defines the activities to identify the occurrence of an event in a timely manner.  Key Objective: If you couldn't stop the threat (i.e. protect phase) how would you know it's even happening, and your company is experiencing harm

**4) Respond**
The respond function includes appropriate activities regarding an incident to minimize impact.  Key Objective: If the threat has been realized how do you prevent additional financial damage, reputation damage, non-compliance, or privacy violations 

**5) Recover**
The recover function includes identifying appropriate activities to maintain plans for resilience and to restore services impaired during cyber security incidents.  Key Objective: How do you get to a state that was equal or better than before the incident

### Safeguards
**Safeguards** are Actions, devices, procedures, techniques, or other measures that reduce the vulnerability of an information system. Synonymous with security controls and Countermeasures.  Feel free to use these lists as a starting point:
#### [153 CIS Controls V8 Implementation Group](https://learn.cisecurity.org/CIS_Controls_v8_Implementation_Groups_Handout)
#### [108 Safeguards outlined by NIST CSF](https://github.com/OWASP/www-project-threat-and-safeguard-matrix/blob/main/Nist_CSF_Safeguards) 
#### [42 Mitre Enterprise Mitigations](https://attack.mitre.org/mitigations/enterprise/)
#### [ISO 27002:2022 Information Security Controls](https://www.iso.org/standard/75652.html)

One common way to organize safeguards is by catergorizing each of them into one of three buckets

**People** - People safeguards can be thought of as education, training, and awareness activities that influence human behaviors

**Process** - Process safeguards can be thought of as Policies, Practices, & Proof or Evidence to operationalize desired outcomes.

**Technology** - Technological safeguards can be thought of as any technical solution that improves the safety and security of a system (WAF, Firewall, Antivirus, etc.)

# Thank You
Thanks to the many folks who helped inspire and Improve the Threat and Safeguard Matrix
#### [Cyber Defense Matrix](https://cyberdefensematrix.com/) by [Sounil Yu](https://www.linkedin.com/in/sounil/)
#### [Eric Bragger](https://www.linkedin.com/in/eric-bragger/)
#### [Andy Ellis](https://www.linkedin.com/in/csoandy/)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OWASP Threat and Safeguard Matrix (TaSM) Builder</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>

    <style>
        :root {
            --primary-blue: #1d4e89;
            --light-header-bg: #ffffff; 
            --header-text-color: #1565c0; 
            --accent-red: #e63946;
            --success-green: #28a745; 
            --success-green-dark: #1e7e34;
            --nist-identify: #4a90e2;
            --nist-protect: #d0021b;
            --nist-detect: #f5a623;
            --nist-respond: #50e3c2;
            --nist-recover: #bd10e0;
            --text-color: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            color: var(--text-color);
            background-color: #fff;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Header Styling */
        header {
            background-color: var(--light-header-bg);
            color: var(--header-text-color);
            padding: 25px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center; 
            border-bottom: 3px solid var(--primary-blue);
        }

        .header-content {
            max-width: 75%; 
        }

        .header-content h1 { 
            margin: 0 0 15px 0; 
            font-size: 2.5rem; 
            font-weight: 800;
            line-height: 1.2;
        }

        .header-content p { 
            margin: 0; 
            opacity: 0.9; 
            font-size: 1rem; 
            line-height: 1.6; 
            color: #333; 
            text-align: justify;
        }
        
        /* Top Right Image Styling */
        .header-img {
            height: 160px; 
            width: auto;
            margin-left: 30px;
            flex-shrink: 0; 
        }

        .container {
            padding: 20px 40px;
            max-width: 1400px;
            margin: 0 auto;
            flex: 1; 
            width: 100%;
            box-sizing: border-box;
        }

        /* Instruction Banner (The "Blue Section") */
        .instruction-banner {
            background-color: #e7f3fe; /* Light Blue */
            border-left: 6px solid #2196F3;
            padding: 15px 20px;
            margin-bottom: 20px;
            font-size: 0.95rem;
            line-height: 1.6;
            display: flex;
            justify-content: space-between;
            align-items: center; /* Centers text vertically against the big button */
            border-radius: 4px;
        }
        
        .instruction-text strong {
            display: block;
            margin-bottom: 5px;
            font-size: 1.1rem;
        }

        /* --- NEW LARGE CAMERA BUTTON STYLING --- */
        .btn-save-img {
            background-color: var(--success-green);
            color: white;
            /* Make it a large square */
            width: 130px;
            height: 130px;
            /* Flex column to stack icon and text */
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 10px; /* Space between icon and text */
            
            padding: 10px;
            border-radius: 16px; /* Rounded square look */
            border: 4px solid var(--success-green-dark); /* Thick border for button look */
            cursor: pointer;
            font-weight: bold;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            transition: all 0.2s ease-in-out;
            margin-left: 20px;
            flex-shrink: 0; /* Prevent squishing */
        }

        /* Styling inner SVG icon */
        .btn-save-img svg {
            width: 50px;
            height: 50px;
            stroke: white;
            stroke-width: 1.5;
        }

        /* Styling inner text span */
        .btn-save-img span {
            font-size: 1rem;
            text-align: center;
            line-height: 1.1;
        }

        /* Hover effects for the large button */
        .btn-save-img:hover {
            background-color: #218838;
            transform: translateY(-3px) scale(1.02); /* Pop up and grow slightly */
            box-shadow: 0 8px 15px rgba(0,0,0,0.3);
        }
        
        .btn-save-img:active {
            transform: translateY(1px); /* Press down effect */
            box-shadow: 0 2px 4px rgba(0,0,0,0.2);
             border-color: #155724;
        }
        /* --------------------------------------- */


        /* Bottom Controls (Add Button) */
        .bottom-controls {
            margin-top: 15px;
            margin-bottom: 40px;
            display: flex;
            justify-content: flex-start;
        }

        /* Buttons */
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.2s;
        }
        .btn-add { background-color: var(--primary-blue); color: white; font-size: 1rem; padding: 12px 24px; }
        .btn-add:hover { background-color: #143b6b; }
        
        /* The Matrix */
        .matrix-container {
            overflow-x: auto;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            background: white; 
            padding: 2px;
            margin-bottom: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            min-width: 1000px;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            vertical-align: top;
        }

        /* NIST Headers */
        thead th {
            color: white;
            text-transform: uppercase;
            font-size: 0.85rem;
            letter-spacing: 0.05em;
            width: 16%;
            line-height: 1.4;
            vertical-align: middle;
        }
        .header-sub {
            display: block;
            font-size: 0.75rem;
            opacity: 0.9;
            text-transform: none;
            margin-top: 4px;
            font-weight: normal;
        }

        .th-threat { background-color: #333; width: 20%; }
        .th-identify { background-color: var(--nist-identify); }
        .th-protect { background-color: var(--nist-protect); }
        .th-detect { background-color: var(--nist-detect); }
        .th-respond { background-color: var(--nist-respond); color: #333 !important; }
        .th-recover { background-color: var(--nist-recover); }

        /* Editable Cells */
        td[contenteditable="true"] {
            background-color: #fff;
            min-height: 80px;
            cursor: text;
        }
        td[contenteditable="true"]:hover {
            background-color: #fcfcfc;
        }
        td[contenteditable="true"]:focus {
            outline: 2px solid var(--primary-blue);
            background-color: #fff;
        }

        /* The Red Focus Box (Metrics) */
        .focus-metric {
            border: 4px solid var(--accent-red) !important;
            position: relative;
        }
        .focus-metric::after {
            content: "METRIC";
            position: absolute;
            bottom: 0;
            right: 0;
            background: var(--accent-red);
            color: white;
            font-size: 0.6rem;
            padding: 2px 4px;
            pointer-events: none;
        }

        /* Threat Input Styling */
        .threat-cell {
            font-weight: bold;
            background-color: #f8f9fa;
        }
        
        .delete-row-btn {
            float: right;
            color: #999;
            cursor: pointer;
            font-size: 1.2rem;
            margin-left: 10px;
        }
        .delete-row-btn:hover { color: red; }

        /* Threat Suggestions Section */
        .suggestions {
            margin-top: 20px;
            padding: 20px;
            background-color: #f4f4f4;
            border-radius: 8px;
        }
        .suggestions h3 { margin-top: 0; }
        .tag-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .tag {
            background: white;
            border: 1px solid #ccc;
            padding: 8px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            cursor: pointer;
            transition: all 0.2s;
            position: relative;
        }
        .tag:hover {
            background: var(--primary-blue);
            color: white;
            border-color: var(--primary-blue);
        }

        /* Footer Styling */
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            border-top: 1px solid #e0e0e0;
            color: #666;
            font-size: 0.9rem;
            background-color: #f9f9f9;
        }

        @media print {
            .bottom-controls, .suggestions, .instruction-banner, .delete-row-btn, .btn-save-img { display: none; }
            body { background: white; }
            header { background-color: white !important; border-bottom: none; color: #333; display: block; }
            .header-content { max-width: 100%; }
            .header-img { float: right; }
            .matrix-container { box-shadow: none; }
            table { page-break-inside: auto; }
            tr { page-break-inside: avoid; page-break-after: auto; }
            td { border: 1px solid #000; }
            .focus-metric { border: 4px solid red !important; -webkit-print-color-adjust: exact; }
            thead th { -webkit-print-color-adjust: exact; color: white !important; }
            .th-identify { background-color: #4a90e2 !important; }
            .th-protect { background-color: #d0021b !important; }
            .th-detect { background-color: #f5a623 !important; }
            .th-respond { background-color: #50e3c2 !important; }
            .th-recover { background-color: #bd10e0 !important; }
            footer { display: block; margin-top: 20px; border-top: none; }
        }
    </style>
</head>
<body>

<header>
    <div class="header-content">
        <h1>OWASP Threat & Safeguard Matrix</h1>
        <p>The Threat and Safeguard Matrix (TaSM) is an action-oriented view to safeguard and enable the business created by CISO Tradecraft. Simply put if Cyber is in the Business of Revenue Protection, then we need to have a defense in depth plan to combat the biggest threats to our companies. This matrix allows a company to overlay its major threats with the NIST Cyber Security Framework Functions (Identify, Protect, Detect, Respond, & Recover) to build a robust security plan. Organizations that perform this activity will gain a better understanding of how to protect their company as they fill in safeguards that mitigate important threats.</p>
    </div>
    
    <img src="https://raw.githubusercontent.com/OWASP/www-project-threat-and-safeguard-matrix/main/assets/images/TasmanianIcon.png" alt="TaSM Logo" class="header-img">
</header>

<div class="container">

    <div class="instruction-banner">
        <div class="instruction-text">
            <strong>How to use:</strong> 
            1. Add a Threat from the list below or create your own.<br>
            2. Fill in the specific safeguards for each NIST function.<br>
            3. Double-click any cell to toggle the <span style="color:red; font-weight:bold;">Red Box</span> (Metrics) to indicate a key performance indicator or focus area.
        </div>
        
        <button class="btn-save-img" onclick="saveAsImage()" title="Click to take a screenshot of the matrix">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round">
                <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/>
                <circle cx="12" cy="13" r="4"/>
            </svg>
            <span>Save a Picture</span>
        </button>

    </div>

    <div class="matrix-container" id="matrixCaptureArea">
        <table id="tasmTable">
            <thead>
                <tr>
                    <th class="th-threat">Threat Scenario</th>
                    <th class="th-identify">Identify<span class="header-sub">Find Vulnerabilities</span></th>
                    <th class="th-protect">Protect<span class="header-sub">Block Attacks</span></th>
                    <th class="th-detect">Detect<span class="header-sub">Monitor Threats</span></th>
                    <th class="th-respond">Respond<span class="header-sub">Contain Damage</span></th>
                    <th class="th-recover">Recover<span class="header-sub">Restore Systems</span></th>
                </tr>
            </thead>
            <tbody id="matrixBody">
                </tbody>
        </table>
    </div>

    <div class="bottom-controls">
        <button class="btn-add" onclick="addEmptyRow()">+ Add New Threat Row</button>
    </div>

    <div class="suggestions">
        <h3>Common Threat Library (Click to Add)</h3>
        <p>Select a threat to add it to your matrix immediately. (Hover over tag to see description)</p>
        <div class="tag-container">
            <div class="tag" onclick="addRow('Brand Impersonation Scams')" title="Imposters launch fake websites to sell counterfeit products under your name.">Brand Impersonation Scams</div>
            <div class="tag" onclick="addRow('Business Email Compromise')" title="Employees fall for a phishing scam, handing over usernames, passwords, and even MFA codes.">Business Email Compromise</div>
            <div class="tag" onclick="addRow('Business Logic Bugs')" title="A bug in your trading algorithm generates losses instead of profits.">Business Logic Bugs</div>
            <div class="tag" onclick="addRow('BYOD Issues')" title="Remote employees outsource their work, unknowingly involving unauthorized foreign actors.">BYOD Issues</div>
            <div class="tag" onclick="addRow('CEO Impersonation')" title="A fraudster impersonates your CEO with deep fakes on social media.">CEO Impersonation</div>
            <div class="tag" onclick="addRow('Cloud Disruption')" title="Your cloud provider or SaaS partner goes down, and so does your business continuity.">Cloud Disruption</div>
            <div class="tag" onclick="addRow('Compliance Attestation Complications')" title="Misinterpreting regulations leads to false attestations—and potential legal action.">Compliance Attestation Complications</div>
            <div class="tag" onclick="addRow('Credential Theft Issues')" title="Your open-source project accidentally exposes secret tokens and private keys.">Credential Theft Issues</div>
            <div class="tag" onclick="addRow('Customer Rewards Raid')" title="Digital thieves snatch customer reward points, leaving your support team flooded with angry calls.">Customer Rewards Raid</div>
            <div class="tag" onclick="addRow('Email Overloaded')" title="Your leadership drowns in endless spam from throwaway Gmail accounts.">Email Overloaded</div>
            <div class="tag" onclick="addRow('Deepfake Deception')" title="A hyper-realistic deepfake of your CFO tricks the accounts payable team into wiring unauthorized funds.">Deepfake Deception</div>
            <div class="tag" onclick="addRow('DDoS/Botnet Attack')" title="A swarm of bots takes down your website after a controversial corporate statement.">DDoS/Botnet Attack</div>
            <div class="tag" onclick="addRow('Forum Defacement')" title="Script kiddies flood your customer help forums with junk, wrecking your brand’s credibility.">Forum Defacement</div>
            <div class="tag" onclick="addRow('Help Desk Hijack')" title="Impersonators sweet-talk IT support into resetting employee passwords.">Help Desk Hijack</div>
            <div class="tag" onclick="addRow('Insider Threat')" title="Departing researchers take sensitive IP to a rival company.">Insider Threat</div>
            <div class="tag" onclick="addRow('Infected IoT Devices')" title="Malware takes over your unpatchable IoT devices, turning them into cyber-zombies.">Infected IoT Devices</div>
            <div class="tag" onclick="addRow('Open Source Trojan')" title="That “helpful” library your developers installed? It came preloaded with malware and crypto miners.">Open Source Trojan</div>
            <div class="tag" onclick="addRow('Prolonged Power Outages')" title="Natural disasters knock out power, and your operations grind to a halt.">Prolonged Power Outages</div>
            <div class="tag" onclick="addRow('Hardware Exploits')" title="Nation-state attackers slip implants into your networking gear.">Hardware Exploits</div>
            <div class="tag" onclick="addRow('Payment Fraud')" title="Scammers trick your customers into redirecting payments to their fraudulent accounts.">Payment Fraud</div>
            <div class="tag" onclick="addRow('Private Data Publicly Exposed')" title="Sensitive data leaks from a misconfigured public S3 bucket.">Private Data Publicly Exposed</div>
            <div class="tag" onclick="addRow('Rogue Access Points')" title="Rogue networks near your company cafeteria mimic your corporate Wi-Fi.">Rogue Access Points</div>
            <div class="tag" onclick="addRow('Wrong Access Permissions')" title="Sensitive SharePoint data ends up in the hands of the wrong reseller.">Wrong Access Permissions</div>
            <div class="tag" onclick="addRow('Unpatched Laptops')" title="An employee connects to airport Wi-Fi and unknowingly invites malware onto an unpatched laptop.">Unpatched Laptops</div>
            <div class="tag" onclick="addRow('Zero-Day Attack')" title="Hackers exploit a fresh vulnerability on your public website before a patch even exists.">Zero-Day Attack</div>
        </div>
    </div>
</div>

<footer>
    &copy; 2025 Erudite Candor Publishing. All Rights Reserved.
</footer>

<script>
    // Initial 5 Material Threats
    window.onload = function() {
        addRow('Ransomware', 
            'Asset Inventory, Data Classification', 
            'MFA, Immutable Backups, Endpoint Protection', 
            'EDR Alerts, Anomaly Detection', 
            'Isolation Playbook, Incident Response', 
            'Restore from Offline Backups'
        );
        addRow('Business Email Compromise', 
            'Identify VIPs, Map Email Flows', 
            'DMARC/SPF/DKIM, MFA, External Email Tags', 
            'Impossible Travel, Forwarding Rule Alerts', 
            'Account Reset, Global Sign-out', 
            'User Retraining, Policy Update'
        );
        addRow('Insider Threat', 
            'Role Access Reviews, Data Identification', 
            'DLP, RBAC, USB Blocking', 
            'User Behavior Analytics (UBA)', 
            'Revoke Access, Legal Hold', 
            'HR Procedures, Forensic Audit'
        );
        addRow('Supply Chain Attack', 
            'Vendor Risk Assessment, BOM Analysis', 
            'Code Signing, Network Segmentation', 
            'Vulnerability Scanning, 3rd Party Monitoring', 
            'Vendor Patching, Virtual Patching', 
            'Switch to Alternative Vendor'
        );
        addRow('DDoS Attack', 
            'Traffic Baseline Analysis', 
            'CDN, WAF, Rate Limiting', 
            'Traffic Spike Alerts, Latency Monitoring', 
            'IP Blocking, Traffic Scrubbing', 
            'Scale Resources, Failover'
        );
    };

    function addRow(threatName = "New Threat", iden="", pro="", det="", res="", rec="") {
        const tbody = document.getElementById('matrixBody');
        const tr = document.createElement('tr');

        tr.innerHTML = `
            <td class="threat-cell">
                <span contenteditable="true">${threatName}</span>
                <span class="delete-row-btn" onclick="deleteRow(this)">&times;</span>
            </td>
            <td contenteditable="true">${iden}</td>
            <td contenteditable="true">${pro}</td>
            <td contenteditable="true">${det}</td>
            <td contenteditable="true">${res}</td>
            <td contenteditable="true">${rec}</td>
        `;

        tbody.appendChild(tr);
    }

    function addEmptyRow() {
        addRow("Edit Threat Name...");
    }

    function deleteRow(btn) {
        if(confirm("Remove this threat row?")) {
            const row = btn.parentNode.parentNode;
            row.parentNode.removeChild(row);
        }
    }

    document.getElementById('tasmTable').addEventListener('dblclick', function(e) {
        const cell = e.target;
        if (cell.tagName === 'TD' && cell.getAttribute('contenteditable') === 'true' && !cell.classList.contains('threat-cell')) {
            cell.classList.toggle('focus-metric');
        }
    });

    // Function to Save Matrix as Image
    function saveAsImage() {
        const captureElement = document.getElementById('matrixCaptureArea');
        
        // Use html2canvas to take a screenshot of the matrix container
        html2canvas(captureElement, {
            backgroundColor: "#ffffff", // Ensure white background
            scale: 2 // Improve resolution
        }).then(canvas => {
            const link = document.createElement('a');
            link.download = 'TaSM_Matrix.png';
            link.href = canvas.toDataURL("image/png");
            link.click();
        }).catch(err => {
            console.error("Image capture failed:", err);
            alert("Error saving image. Please ensure you are using a modern browser.");
        });
    }
</script>

</body>
</html>
