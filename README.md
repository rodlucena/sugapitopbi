## SUGAPI Dashboard in PBI

### Security – Analyze KBs Superseded

### SUGAPI Dashboard in PBI

This solution will help the Security team to analyze the superseded KBs, delivered monthly by Microsoft.

The SUGAPI [aka.ms/sugapi](https://portal.msrc.microsoft.com/en-us/developer) is a RESTful API that we can use to engage the Microsoft Security Response Center (MSRC) in the following ways: 
- Get security update summaries and details using the Common Vulnerability Reporting Framework (CVRF).
- Report suspected cyberattacks or abuse originating from Microsoft Online Services.
- Notify Microsoft of any planned penetration tests against your Azure assets.

The propose of this solution is to show you how to get the CVRF summary and combining this info with WSUS Database will provide you a PowerBI Dashboard that brings insightful information about superseded KBs and more. 

The dashboard generate will have the following information:
- Microsoft Common Vulnerabilities and Exposures (CVE).
- Product involved with CVEs.
- KBs associate with CVEs.
- Superseded KBs.
- Supersedes KBs.

![OverviewImage](/install/images/OverviewImage.png)


Download the [documentation](https://github.com/rodlucena/sugapitopbi/blob/master/install/Security%20-%20Analyze-KBs-Superseded.pdf) and the [PBI template](https://github.com/rodlucena/sugapitopbi/blob/master/install/Security%20-%20Analyze-KBs-Superseded.pbix).

