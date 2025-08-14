<h1 align="center">🛡️ Task 7 – Identify and Remove Suspicious Browser Extensions</h1>

**Date:** 14 August 2025  
**Submitted by:** Pradeep S

---

## 🎯 Objective

Review all installed browser extensions, identify any that may pose security or privacy risks based on their permissions and trustworthiness, and take appropriate action (removal or retention) to maintain a secure browsing environment.

## 📌 Summary Objective

Identify, evaluate, and remove potentially harmful browser extensions to improve browser security.

## 🛠 Tools Used

- Google Chrome
- Extensions Manager

## 🔍 Steps Taken

1. Opened Firefox Extensions Manager.  
2. Reviewed all installed extensions and their permissions.  
3. Checked each extension's developer credibility and online reviews.  
4. Identified extensions that may pose security/privacy risks.  
5. Removed or disabled the suspicious extension.  
6. Restarted the browser and verified extension list.

## 🚨 Extension Review

| Extension Name            | Purpose                         | Risk Assessment                                               | Action Taken |
|--------------------------|----------------------------------|---------------------------------------------------------------|--------------|
| Dark Reader              | Enables dark mode on websites    | Trusted and widely used                                       | Kept         |
| Download Manager (S3)    | Manage and download files        | Requests broad permissions; similar tools have ads/tracking   | Removed      |
| Foxy Proxy               | Proxy configuration tool         | Safe if configured properly; requires network access          | Kept         |
| SponsorBlock for YouTube | Skip sponsored segments on YouTube | Open-source and considered safe                               | Kept         |

---

## 🚨 Suspicious Extension Analysis – Download Manager (S3)

**Purpose:** Manage and organize downloads in the browser.  
**Reason for Suspicion:** Requests overly broad permissions that could be exploited for malicious purposes.

**Permissions Granted & Risks:**

1. Access data for all websites – Could read/alter sensitive info like passwords or bank data.  
2. Download files & modify history – Can track or manipulate downloads.  
3. Open downloaded files – Risk of executing malicious content.  
4. Access browsing history – Enables complete activity tracking.  
5. Display notifications – Could send phishing-like popups.  
6. Access browser tabs – Allows monitoring of all tabs and content.

**Action Taken:** Removed from browser to prevent potential misuse.  
**Risk Level:** High

---

## ✅ Trusted Extension Analysis – Dark Reader

**Purpose:** Enables dark mode on all websites to reduce eye strain and improve readability at night.  
**Reason for Permissions:** Required to modify website styles in real-time and to know which tabs to apply changes to.

**Permissions Granted & Risks:**

1. Access data for all websites – Needed to change site colors; in malicious extensions, could alter or steal information.  
2. Access browser tabs – Identifies which sites are open to apply styling; in malicious cases, could track browsing activity.

**Action Taken:** Kept installed – verified open-source and reputable.  
**Risk Level:** Low (trusted source)

---

## ✅ Trusted Extension Analysis – SponsorBlock for YouTube

**Purpose:** Automatically skips sponsorships, self-promotions, and other non-content segments in YouTube videos.

**Reason for Permissions:**

1. Access data for youtube.com – Needed to read video timelines and skip sponsors.  
2. Access data for SponsorBlock server – Stores and retrieves sponsor timestamps.  
3. Access data for youtube-nocookie.com – Ensures sponsor skipping works in embedded YouTube videos using privacy mode.

**Action Taken:** Kept installed – open-source, reputable, and permissions are limited to specific domains.  
**Risk Level:** Low (trusted source)

---

## ⚠️ Caution Extension Analysis – Foxy Proxy

**Purpose:** Advanced proxy management tool for switching between multiple proxies easily.

**Reason for Permissions:**

1. Download files & modify download history – Could track or alter downloads; likely minimal risk for a proxy tool.  
2. Display notifications – Alerts user of proxy changes or errors.  
3. Control browser proxy settings – Needed for proxy management; high-risk if extension or configured proxy is malicious.  
4. Access browser tabs – Allows knowing which sites are open; could be abused for tracking.

**Action Taken:** Kept installed – verified source, but configured proxies only from trusted providers.  
**Risk Level:** Medium (permissions powerful but justified)

---

## ⚠️ Mitigate Risky Browser Extensions

1. Remove suspicious extensions that ask for too many permissions.  
2. Install only from trusted sources and check reviews.  
3. Review and update extensions regularly.  
4. Limit permissions to what’s necessary.  
5. Use separate browsers for sensitive work.  
6. Watch for unusual activity and run antivirus scans.

---

## 📚 Key Learnings

1. Always verify the source before installing extensions.  
2. Avoid granting unnecessary permissions.  
3. Regularly review and remove unused extensions.