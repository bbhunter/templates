# Overview
<!--
**Please replace text in each section below**

No Rate Limiting on form SMS Triggering - Vulnerability Report

Resources:

- <https://www.owasp.org/index.php?title=OWASP_Periodic_Table_of_Vulnerabilities_-_Brute_Force_(Generic)_/_Insufficient_Anti-automation&setlang=en>
- <http://projects.webappsec.org/w/page/13246938/Insufficient%20Anti-automation>
-->

## Walkthrough & PoC
<!--
Provide a step-by-step walkthrough on how to access the vulnerable injection point, and how to exploit the vulnerability.
Adding a dot-pointed walkthrough with relevant screenshots will speed triage time and result in faster rewards!

Example:

1. Browse to the website <www.inscope.com/form>
1. Fill out the application installation form and add in our target SMS Number
1. Turn on our intercept proxy for the browser and submit the form
1. Send the request to intruder from the intercept proxy
1. Submit the request 100 times and wait 5 minutes
1. Check our target mobile, you will see our 100 SMS Messages being recieved to our target mobile number
-->

## Vulnerability Evidence
<!--
Your submission MUST include evidence of the vulnerability and not be theoretical in nature.

You must attach the request you are sending to trigger these SMS Messages, and the SMS you recieve to the target mobile number
-->

## Demonstrated Impact
<!--
This can enable an attacker to use this form to send spam to a target mobile number, cause service interuptions for the service provider, and could put the SMS Number on a spam list.
--> 