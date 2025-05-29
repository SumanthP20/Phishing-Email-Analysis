This project showcases how to analyze phishing emails using email headers, body content, attachments and links.

Tools used for Phishing Analysis

Header Analysis ( MX Tool box for email header analysis )

Suspicious Link Inspection ( Virus Total, URLscan.io )

Attachment Scanning ( Virus Total )

Summarize your Analysis

Step-1  Analyzing the email header using the Mx toolbox and then copy the sender domain address and paste it in virus total.

Step-2 After analyzing the email headers and check the DKIM, SPF, DMARC results.

Step-3 Copying the URL and paste it in the Virus Total. It will scan the URL in different security vendors and the shows the results like malicious, phishing or clean.

Step-4 Scan the attachments. Firstly download or save the attachment in a secure environment like VM or Sandbox. Then paste the attachment or upload the file in the Virus Total. Review the results or detctions.

Step-5 Scan the sender Domain or IP. It will show the results if that domain is associated with Malware / Phishing related things.

Step-6 Document the findings  such as ip address and attachments or links used for the attack and block the sender ip address or domain.

Tips 

Never open links/attachments on your real machine

Always use sandbox or vm

