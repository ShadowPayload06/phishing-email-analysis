📧 Phishing Email Analysis Report

🔍 Overview

This report documents a structured investigation into a phishing email sample sourced from CanIPhish, designed to impersonate Payoneer. The analysis covers sender authenticity, header validation, link behavior, language manipulation, and overall threat indicators. The goal is to identify phishing traits and provide actionable recommendations for mitigation and user awareness.

🧪 Methodology

The email was examined using a combination of manual inspection and automated tools. Key areas of focus included:

- Sender domain legitimacy  
- Email header authentication (SPF, DKIM, DMARC)  
- Link behavior and redirection analysis  
- Language cues such as urgency or robotic phrasing  
- URL mismatches and deceptive formatting  
- Use of external tools like VirusTotal, CheckPhish.ai, and Google Admin Toolbox

📌 Key Findings
 
- Spoofed Sender Domain:  
  The email claimed to be from Payoneer but used `payoneer[_]gps@alerting-services[.]com`, a domain not affiliated with the brand.

- Failed Authentication:  
  SPF failed, DKIM was missing, and DMARC was not configured — confirming the sender was unauthorized.

- Deceptive Link Behavior:  
  The “View Payment” and “Verify” buttons redirected to suspicious domains such as `http://businesses.loan/paynow` and `http://payouts.payoneer.com/VerifyGateway.aspx?...`, which may be crafted to appear legitimate.

- Urgent and Manipulative Language:  
  Phrases like “You have received a new payment” and “Payment will expire in 24 hours” were used to pressure the recipient into acting quickly.

- No Spelling Errors, But Robotic Grammar:  
  The email was grammatically correct but contained unnatural phrasing, suggesting automated or non-native composition.

- Phishing Traits Summary:
  - Spoofed sender identity  
  - Failed authentication protocols  
  - Mismatched and deceptive URLs  
  - Artificial urgency  
  - Subtle language manipulation

🛠️ Tools Used

| Tool                 | Purpose                              |
|----------------------|--------------------------------------|
| Google Admin Toolbox | Header authentication analysis       |
| VirusTotal           | Link and file scanning               |
| CheckPhish.ai        | Phishing URL detection               |
| CanIPhish            | Phishing simulation platform         |

✅ Recommendations

1. Do not click on links from unknown or mismatched domains.  
2. Verify sender authenticity** using header analysis tools.  
3. Use scanning platforms** like VirusTotal to validate suspicious links or attachments.  
4. Report phishing** via email client options or internal security channels.  
5. Educate users** on recognizing urgency, mismatched URLs, and spoofed branding.

🧾 Notes

- All findings are documented in `.txt` files for clarity and traceability.
- Screenshots were reviewed but not included in public documentation to maintain privacy.  
- Sensitive data such as email addresses and timestamps were redacted or anonymized.  
- This report supports responsible disclosure and user training initiatives.
