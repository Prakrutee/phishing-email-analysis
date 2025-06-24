# Phishing Email Analysis Report

## Phishing Link
**URL:** https://re-amendes-gouv.com/as.php  
**Target:** French Citizens (Fake Government Fine Portal)  
**Found on:** PhishTank (ID 9136148)

---

## Phishing Indicators

| Indicator Type      | Evidence |
|---------------------|----------|
| Spoofed Sender      | `amendes@gouv-france-secure.com` (Not a legit French domain) |
| Suspicious Link     | Link text says "Click here", but leads to a scam URL |
| Domain Mismatch     | `.gouv.fr` is legit; this is `.com` |
| Urgent Language     | "Final Notice", "Legal consequences", "Failure to complete..." |
| Email Header Issue  | Simulated SPF failure |
| Threat Tactic       | Fines, legal action threat |
| Grammar/Language    | Reasonably correct (targeted attack) |

---

## Tools Used
- [VirusTotal](https://www.virustotal.com/)
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [Unshorten.it](https://unshorten.it/)
- Hover-over technique for URL checking

---

## Summary
This phishing email impersonates a government agency to scare the target into clicking a malicious payment link. It uses a spoofed sender domain, threatening language, and a fraudulent URL to appear legitimate.
