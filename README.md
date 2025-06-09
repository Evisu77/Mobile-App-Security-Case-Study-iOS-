# Mobile App Security Case Study (iOS) – Responsible Disclosure Practice

This case study documents a limited, passive security review of a publicly available iOS application. The assessment was conducted independently for learning purposes, with a strict focus on ethical boundaries and responsible disclosure.

## Summary

The goal of this review was to analyze how mobile apps handle user data, authentication, and third-party integrations. Testing stopped before any unauthorized access or active exploitation. A responsible disclosure report was submitted to the app vendor.

> ⚠️ No vulnerabilities were exploited. No private data was accessed. All research was passive and legal.

## Key Findings

- **No user authentication required**, even for sensitive actions.
- **Permissive network configuration**, disabling iOS HTTPS protections.
- **Third-party SDKs transmitting behavioral data** without visible user consent.
- **Unnecessary microphone access** requested by the app.
- **Indexed usage data by Siri & Search**, without transparency to users.

## 🛠Techniques Used

- IPA unpacking and static analysis (`Info.plist`)
- Passive traffic inspection via Burp Suite and Wireshark
- iOS privacy behavior observation
- No reverse engineering or active probing

## What I Learned

- Mobile app security principles (authentication, ATS, permission handling)
- Data privacy best practices and SDK behavior
- How to write a responsible disclosure report professionally
- Real-world reporting ethics — and when to stop testing

## 📁 [Download Public Report (Redacted PDF)](https://github.com/Evisu77/Mobile-App-Security-Case-Study-iOS-/releases/download/v1.0/Mobile_App_Security_Case_Study_Redacted.pdf.pdf)

## 🤝 Disclaimer

This is a non-commercial, ethical learning project. The app name has been omitted out of respect for the developers. This project is shared to demonstrate professional intent, practical ability, and growth in the field of cybersecurity.

---
