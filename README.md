# Phishing-Email-Analysis

Here’s an example of a sample phishing email, crafted for educational and awareness purposes only.

Subject: Urgent: Suspicious Activity Detected on Your Account

From: security@paypalsecure.com

To: [Your Email Address]

Date: Mon, 27 May 2025 10:42 AM

Dear Customer,

We have detected unusual login activity on your PayPal account from an unrecognized device. For your protection, your account has been temporarily suspended.

To restore access and verify your identity, please click the link below:

👉 Verify Your Account Now

Failure to verify your information within 24 hours will result in permanent suspension of your account.

Thank you for your prompt attention to this matter.

Sincerely,

PayPal Security Team

© 2025 PayPal, Inc. All rights reserved.

To examine the sender email address for spoofing

These are the things you should check mainly

1.Fake sender email: Not from the official paypal.com domain.

2.Urgency and threat: Pressure to act quickly to avoid account suspension.

3.Phishing link: Suspicious URL that looks like PayPal but is not.

4.Generic greeting: “Dear Customer” instead of using your name.

🔍 1. Check the Full Email Address, Not Just the Display Name
Phishers often spoof the display name to look like someone you trust (e.g., “PayPal Support”), but the actual address may reveal something suspicious.

How to check:

Hover over or click on the sender's name to see the full email address.

Example:

Display Name: PayPal Support

Actual Email: security@paypalsecure.com (not from paypal.com)

🔒 2. Verify the Domain Name
Legitimate companies use their official domains. Spoofers use lookalikes:

paypalsecure.com, pay-pal.com, or paypal.co instead of paypal.com.

Ask:

Is the domain correct and spelled perfectly?

Does the domain match the official website?

📬 3. View the Email Header for Technical Clues
Email headers contain detailed routing information and authentication results.

How to view email headers:

Gmail: Click the 3-dot menu > "Show original"

Outlook: Right-click email > "View message source"

Apple Mail: View > Message > All Headers

Look for:

SPF, DKIM, and DMARC results:
These are anti-spoofing checks.

SPF: PASS, DKIM: PASS, DMARC: PASS are good signs.

If you see FAIL or None, the email might be spoofed.

⚠️ 4. Compare the “From,” “Return-Path,” and “Reply-To” Addresses

They should all match or be logically related.

Example of a spoof:

From: support@paypal.com

Return-Path: scammer@evilsite.ru

Reply-To: scamhelpdesk@gmail.com

If any of these are off, it’s likely spoofed.

🛡️ 5. Use an Email Lookup Tool

Tools like MXToolbox, Mailheader Analyzer, or Whois lookup can help you analyze headers and domain reputation.

Summarize phishing traits found in the Email.

✅ Phishing Traits in the Sample Email:
Trait	Description

Urgency and Fear Tactics:          Claims “suspicious activity” and threatens account suspension if action isn’t taken immediately.

Suspicious Link:                  The link looks like a legitimate login but points to a fake domain (e.g., paypal-verification-secure-login.com).

Generic Greeting:                	Uses “Dear Customer” instead of your actual name — a sign it’s sent to many people.

Spoofed Sender Name:            	The display name is “PayPal Security,” but the email address is from a lookalike domain (e.g., @paypalsecure.com).

Impersonation of a Trusted Brand:        	Uses PayPal’s name and logo to build trust and credibility.

Grammar and Tone:                	While subtle, phishing emails may contain awkward phrasing or unnatural urgency.

Threat of Consequences:         	Says failure to act will result in “permanent suspension,” pressuring the user.

These are all red flags that should make recipients stop and investigate before clicking anything. 

