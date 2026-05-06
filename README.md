# SOC-Analysis-Phishing-Alert
This is repo contains a TryHackMe investigation that has been conducted to verify a true positive threat and suggest further action. 

# Report 
## Time of activity: 18:45

## List of Affected Entities: c.allen@thetrydaily.thm

## Reason for Classifying as True Positive: 
This activity has been classified as a true positive because the following red flags were detected immediately after viewing the email: The sender Typosquatted an existing company name (Microsoft), manipulated a domain by adding .co instead of .com, and they made use of a suspicious email domain. Further actions were taken where I verified whether the user interacted with the link or not, and I made use of a threat intelligence tool to verify that this link was indeed a malicious email. After carefully taking these steps I have concluded that this user did not interact with the link , and the link is indeed a malicious link.

## Reason for Escalating the Alert: 
The link that has been sent is malicious which therefor makes it a potential threat to the company. 

## Recommended Remediation Actions: 
The link should be blocked to prevent any future access from potential victims. 

## List of Attack Indicators: 
- Typosquatted an existing company to imitate them as a way of malware attack
- Suspicious domain name
- Malicious link 
