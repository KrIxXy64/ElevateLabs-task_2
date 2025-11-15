# Phishing Email Analysis Report

## 1. Overview

This report analyzes a sample phishing email pretending to be from
PayPal.\
The goal is to identify red flags, phishing indicators, spoofing
attempts,\
and social engineering techniques.

------------------------------------------------------------------------

## 2. Phishing Indicators Identified

### **2.1 Fake or Spoofed Sender Email**

-   Sender: security-alert@pypall-secure.com\
-   The domain **pypall-secure.com** is NOT PayPal.\
-   Attackers often use similar-looking domains to trick victims.

------------------------------------------------------------------------

### **2.2 Urgent / Fear-Based Language**

The email uses threatening statements to create panic, such as: - "Your
account has been suspended" - "Verify your identity" - "Within 24 hours"

This is a classic social engineering tactic.

------------------------------------------------------------------------

### **2.3 Malicious / Fake URL**

The link provided is: https://paypal.verify-account-secure-login.com

This is NOT an official PayPal domain.\
Real PayPal domain = **paypal.com**

The attacker uses a long subdomain to confuse users.

------------------------------------------------------------------------

### **2.4 Generic Greeting**

The email uses **"Dear Customer"** instead of your real name.\
Legitimate companies usually address you personally.

------------------------------------------------------------------------

### **2.5 Suspicious Attachment Mention**

The email mentions a security report attachment.\
Phishing emails often attach: - malware\
- trojans\
- fake PDF forms

This is a red flag.

------------------------------------------------------------------------

### **2.6 Grammar and Formatting Errors**

Small mistakes and unnatural sentence structure indicate the email is
not official.

------------------------------------------------------------------------

### **2.7 Header Analysis (Example Results)**

Using MXToolbox or any header analyzer: - SPF: fail - DKIM: fail -
DMARC: fail

This means: - The message was NOT sent through official PayPal servers.

------------------------------------------------------------------------

## 3. Conclusion

Multiple indicators confirm this email is a **phishing attack**.
