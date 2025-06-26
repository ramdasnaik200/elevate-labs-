## TASK 1


# 🔍 Network Scanning with Nmap

This project documents a basic **network reconnaissance task using Nmap** to discover active devices, open ports, and services running on a local network. Optional analysis was done using Wireshark, and potential security implications were identified.

---

## 🛠️ Tools Used

- [Nmap](https://nmap.org/) – Network scanning tool
- [Wireshark](https://www.wireshark.org/) – Packet analysis tool (optional)
- Operating System: [Your OS – e.g., Kali Linux, Ubuntu, Windows]

---

## 📋 Task Steps

1. Installed **Nmap** from the official website.
2. Identified local IP range (e.g., `192.168.1.0/24`) using:
   ```bash
   ip a        # on Linux
##  Performed a TCP SYN scan:

sudo nmap -sS 192.168.1.0/24


## TASK 2

# 📧 Phishing Email Analysis Project

This project documents a detailed analysis of a **sample phishing email**. The goal was to identify spoofing techniques, suspicious elements, and social engineering tactics commonly used by attackers to trick users into revealing sensitive information or clicking malicious links.

---

## 🛠️ Tools Used

- 📬 Sample Phishing Email (sourced from public repositories or inbox spam folder)
- 🔍 [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- 🧠 [Google Admin Toolbox Messageheader](https://toolbox.googleapps.com/apps/messageheader/)
- 🖱️ Browser-based link inspection (hover analysis)

---

## 📋 Task Steps

1. **Obtained a sample phishing email** from a publicly available source.
2. **Analyzed the sender’s email address** to detect spoofing or lookalike domains.
3. **Checked email headers** using:
   - **MXToolbox**: to trace the real source IP and check SPF/DKIM/DMARC results.
   - **Google Header Analyzer**: to evaluate delays, hops, and authenticity.
4. **Identified suspicious links or attachments** embedded in the email.
5. **Noted use of urgent or manipulative language**, like:
   - "Your account will be deactivated"
   - "Immediate action required"
6. **Checked for mismatched URLs** by hovering over links (real vs displayed URL).
7. **Spotted spelling/grammar errors**, a common sign of phishing.
8. **Summarized the phishing traits** found in the email (see below).

---

## 🧪 Phishing Traits Identified

| Trait                             | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| 🔀 Spoofed Email Address         | Sender domain looked similar to a legitimate company                        |
| 📛 Failing SPF/DKIM/DMARC        | Email failed authentication checks                                          |
| 🔗 Mismatched URLs               | Visible links were different from actual target URLs                        |
| ⚠️ Urgent Language               | Created fear to trigger immediate response                                  |
| 📄 Suspicious Attachments        | HTML file that redirected to a credential-harvesting page                   |
| ✍️ Spelling/Grammar Issues       | Unprofessional formatting and language                                      |

---

## 📎 Screenshot Evidence

Screenshots of:
- Header analysis reports
- The phishing email body
- Hovered links and attachments

are included in the `/screenshots/` folder.

---

## 📚 References

- [Google Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)
- [MXToolbox Email Tools](https://mxtoolbox.com)
- [Phishing Email Examples (PhishTank)](https://www.phishtank.com/)
- [How to Read Email Headers](https://www.cisa.gov/news-events/news/insight-how-read-email-header)

---

## ✅ Outcome

- Learned how to analyze email headers for spoofing
- Detected multiple red flags in a phishing email
- Developed awareness of phishing tactics and social engineering
- Gained hands-on experience with email security tools

---

## 📌 Note

This project was completed as a part of practical cybersecurity training focused on **email security awareness** and **phishing analysis**.
