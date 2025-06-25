# Elevatelab-Task2 

## 🔍 Phishing Indicators Identified

1. **Fake Email Address**  
   - `support@paypa1-alerts.com` mimics PayPal but uses a "1" instead of "l" to trick users.

2. **Suspicious Link**  
   - The displayed text is "Verify Account" but links to `http://paypal.verify-userinfo.com`, a fake domain.

3. **Urgent Language**  
   - Creates panic with phrases like "unusual login", "suspended", and "act within 24 hours".

4. **Generic Greeting**  
   - Uses "Dear Customer" instead of addressing the user by name — a common sign of phishing.

5. **Grammatical Inconsistencies**  
   - Slight awkwardness in phrasing typical of phishing messages.

6. **Link Domain Mismatch**  
   - Hovering over the link reveals it’s not actually hosted on the official `paypal.com` domain.


## 🛠 Tools Used

- [Google Admin Toolbox – Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)
- [VirusTotal – URL Scanner](https://www.virustotal.com/)
- Hover-to-reveal method to inspect embedded links
- Sample sourced from: [https://www.phishing.org/phishing-examples](https://www.phishing.org/phishing-examples)


## 🧠 Learnings

- Always verify the domain of email addresses and links.
- Hover over links to inspect the true destination before clicking.
- Phishing emails commonly use fear and urgency to manipulate the user.
- Tools like VirusTotal and email header analyzers can confirm suspicious activity.
- Never download attachments or click links from unknown or suspicious emails.

---

## 📁 Repository Contents

| File Name | Description |
|-----------|-------------|
| `README.md` | This report summarizing the phishing analysis |
| `phishing_email_sample.txt` | Text file of the email sample (redacted) |

## ✅ Conclusion

This analysis helped identify the common signs of phishing and taught how to validate suspicious emails using free tools. Recognizing such red flags is crucial in protecting personal and organizational data from cyber threats.

