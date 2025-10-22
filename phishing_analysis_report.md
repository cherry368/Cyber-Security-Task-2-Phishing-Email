# Phishing Email Analysis Report

## 1. Objective
To analyze a suspicious email and identify potential phishing characteristics.

## 2. Email Overview
**Subject:** Urgent: Verify your PayPal Account Now  
**Sender:** support@paypaI-secure.com  
**Body:** Contains a fake verification link urging immediate action.

## 3. Findings
| Indicator | Description | Evidence |
|------------|--------------|-----------|
| Spoofed sender | Domain slightly altered | @paypaI-secure.com |
| Suspicious link | Fake URL pretending as PayPal | http://paypal-secure.com/verify |
| Urgent language | Threat of suspension | "Failure to do so…" |
| Grammar errors | Unprofessional wording | "avoid suspension" |
| Header mismatch | SPF/DKIM failure | Header analyzer result |

## 4. Tools Used
- MXToolbox Header Analyzer
- Email client's "View Original Message" feature

## 5. Conclusion
The analyzed email is a phishing attempt. Indicators include domain spoofing, mismatched URLs, and urgent/psychological manipulation tactics.

**Recommendation:**  
Never click unknown links or share credentials. Verify via the official website or customer support channels.

---

## 📸 Visual Evidence
Screenshots and additional analysis evidence can be found in the `screenshots/` folder.

## ⚠️ Educational Purpose
This analysis is part of a cybersecurity training program. The email sample is fictional and used solely for learning purposes.
