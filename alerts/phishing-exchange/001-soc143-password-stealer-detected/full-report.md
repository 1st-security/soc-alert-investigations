# Alert Name
SOC143 - Password Stealer Detected

## Alert Severity
Medium

## Alert Time
Apr 26, 2021, 11:03 PM

## Alert Description
A phishing-related alert was triggered after a suspicious email containing a malicious attachment was delivered to the recipient inbox. The email had no message body and was associated with malicious activity based on threat intelligence.

## Context
- User: ellie@letsdefend.io
- Sender: bill@microsoft.com
- Host: N/A (email-based alert)
- Category: Phishing-Exchange

## Evidence
1. Email was delivered to ellie@letsdefend.io from bill@microsoft.com.
2. The email contained no message body.
3. The email included a malicious attachment.
4. Threat intelligence flagged the attachment as malicious and associated with phishing activity.
5. Recommended action was to remove the email from the user’s inbox.

## Analyst Comment
At Apr 26, 2021, 11:03 PM, user ellie@letsdefend.io was observed receiving a suspicious email from bill@microsoft.com. This activity involved delivery of an email containing no message body and a malicious attachment and led to a phishing alert requiring removal of the message from the user’s inbox. This behavior is suspicious because threat intelligence flagged the attachment as malicious and associated with phishing activity. This alert is assessed as a True Positive.
