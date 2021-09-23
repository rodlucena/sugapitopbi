## MSRCAPI Dashboard in PBI

### Reports Software Updates (MSRC x WSUS)

### MSRCAPI Dashboard in PBI

This document will help the Security team to analyze the KBs, delivered monthly by Microsoft.

The "Microsoft Security Updates API | MSRC" <https://api.msrc.microsoft.com/cvrf/v2.0/swagger/index> is a RESTful API that we can use to engage the Microsoft Security Response Center (MSRC) in the following ways:
- Get security update summaries and details using the Common Vulnerability Reporting Framework (CVRF).
- Report suspected cyberattacks or abuse originating from Microsoft Online Services.
- Notify Microsoft of any planned penetration tests against your Azure assets.

The purpose of this documentation is to show you how to get the CVRF summary and combine that information with the WSUS database, providing a PowerBI dashboard with insightful information about KB availability by period, KB replacement, and more. 

The dashboard generate will have the following information:
- Microsoft Common Vulnerabilities and Exposures (CVE).
- Product involved with CVEs.
- KBs associate with CVEs.
- Superseded KBs.
- Supersedes KBs.
- WSUS KBs analyses.
- Combination of data coming from MSRC and WSUS database.

![OverviewImage](/install/images/OverviewImage.png)


Download the [documentation](https://github.com/rodlucena/sugapitopbi/blob/master/install/Security%20-%20Analyze-KBs-Superseded.pdf) and the [PBI template](https://github.com/rodlucena/sugapitopbi/blob/master/install/Security%20-%20Analyze-KBs-Superseded.pbix).

