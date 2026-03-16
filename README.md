VULNERABILITY ASSESSMENT REPORT

# FUTURE_CS_01
Repo for completed cybersecurity tasks at Future Interns.



Overview

Every business today has a website, but not every website is configured securely.

For this task, I performed a passive security assessment of [a public website](http://www.itsecgames.com/) to identify common security weaknesses. The goal was not to exploit the website or perform aggressive 
testing, but rather to approach the site the way a security consultant or auditor would — looking for configuration issues, missing protections, and other risks that could potentially affect the business.

Instead of focusing on “hacking”, the focus of this project was to answer practical questions a business owner might ask:

1.Is my website secure?

2.Are there any obvious risks?

3.What should be fixed first?

The result of this assessment is a structured vulnerability report that explains the findings in clear language and suggests practical remediation steps.

OBJECTIVE

The objective of this exercise was to:

- Analyze a publicly accessible website for common security weaknesses

- Identify configuration issues and exposed services

- Classify risks in a business-friendly way

- Explain findings clearly without excessive technical jargon

- Recommend practical security improvements

- Present the results in a professional vulnerability assessment report

This task is focused on security auditing and risk communication, which are key skills in security consulting.

Scope & Ethics

This assessment followed strict ethical guidelines.

Only non-intrusive analysis was performed.

Allowed Activities

1.Reviewing public-facing web pages

2.Passive vulnerability scanning

3.Inspecting HTTP security headers

4.Configuration analysis

5.Network port exposure checks

Not Performed

-Login bypass attempts

-Exploitation of vulnerabilities

-Brute-force attacks

-Denial-of-Service testing

-Any activity that could harm the target website

The goal was to behave like a security auditor, not an attacker.

Tools Used
1.Network & Security Analysis

2.Nmap – Used to identify open ports and exposed services

3.OWASP ZAP (Passive Scan) – Used to detect potential vulnerabilities without actively attacking the site

4.Browser DevTools – Used to inspect headers, cookies, and client-side behavior

Reporting

-Canva – Used to design the final vulnerability assessment report

What Was Analyzed

The assessment focused on identifying issues such as:

1.Missing or misconfigured security headers

2.Potential clickjacking protections

3.MIME-type handling issues

4.Exposed ports

General configuration weaknesses

Each issue was documented with:

-A clear explanation

-A risk classification

-Recommended remediation steps

-Risk Classification

Findings were categorized using a simple business-focused scale:

Low – Minor issue with limited risk

Medium – Security weakness that could be exploited in certain situations

High – Significant issue that should be addressed quickly

This approach helps businesses prioritize what to fix first.
