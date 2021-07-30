# Reflected XSS (Non-self)

## Overview

<!--
Provide a 1-2 sentence description - see http://cveproject.github.io/docs/content/key-details-phrasing.pdf for tips

This format is a good guide:
[VULNTYPE] in [COMPONENT] in [APPLICATION] allows [ATTACKER] to [IMPACT] via [VECTOR] 
-->
Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into trusted websites. XSS vulnerabilities allow a malicious attacker to pretend to be the user, and to carry out any actions that the user is able to perform, to access any of the user's data. The malicious attacker might be able to gain full control over all of the application's functionality and data depending on the users level of permissions.

Non-self reflected XSS in {{application}} of {{target}} allows malicious attacker to to execute arbitrary JavaScript and perform actions such as: view any information that the user is able to view, and modify any information that the user is able to modify.

## Walkthrough & PoC

<!--
Provide a step-by-step walkthrough on how to access the vulnerable injection point, and how to exploit the vulnerability.
Adding a dot-pointed walkthrough with relevant screenshots will speed triage time and result in faster rewards!
-->

1. Enable a HTTP interception proxy
1. Navigate to {{url}}
1. Modify the request to contain the JavaScript payload {{parameter}}
1. Forward the request and observe the JavaScript payload being executed

## Vulnerability Evidence

<!--
Your submission MUST include evidence of the vulnerability and not be theoretical in nature.

For a reflected XSS vulnerability, please include a simple URL or HTML payload that can be executed to easily demonstrate and reproduce the issue. 
-->

Below is a screenshot demonstrating the injected JavaScript executing at {{url}}.

{{screenshot}}

## Demonstrated Impact

<!--
Attempt to escalate the XSS to perform additional actions (such as an account takeover or CSRF bypass to perform a sensitive action). If this is possible, provide a full proof-of-concept here.
--> 

A malicious attacker could abuse this XSS further to {{action}} by using the following JavaScript payload.

```
{{payload}}
```

Here is a screenshot of the full exploit taking place:

{{screenshot}}