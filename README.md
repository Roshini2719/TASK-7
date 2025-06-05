# 🔐 Cyber Security Internship - Task 7 (Browser Extension Review)

## 📌 Focused Extension Analysis: Edge Browser

This document presents a detailed security review of the following Microsoft Edge extensions:

---

### 🧠 1. Sider: Chat with all AI models

**Description:**  
AI assistant sidebar that connects with models like DeepSeek, Gemini, Claude, etc., for advanced chat, read, and write capabilities.

**Permissions Requested:**
- Read your browsing history  
- Block content on any page  
- Read and change all your data on websites  
- Access file URLs  
- Allowed in InPrivate mode  

**Findings:**  
- ⚠️ **Highly invasive permissions** — full access to user browsing activity and page content.
- May raise **privacy concerns**, especially with persistent background access even in **InPrivate mode**.
- Large size: **62.7 MB**.
- Not open-source.  

**Action Taken:** ⚠️ *Flagged for Review*  
**Reason:** Extension is potentially useful, but intrusive permissions could pose a risk if abused. Further monitoring required or consider removal if not essential.

---

### 📋 2. Clipboard

**Description:**  
Enhances productivity by enabling multi-copy and quick paste functionality.

**Permissions Requested:**
- Modify clipboard data  
- Read and change all data on websites  
- Allowed in InPrivate mode  

**Findings:**  
- 📌 **Moderate permissions** but justified for clipboard functionality.
- Small size: **<1 MB**
- No suspicious activity or hidden data collection identified.

**Action Taken:** ✅ *Kept*  
**Reason:** Useful, lightweight, and does not request excessive access.

---

### 📄 3. Google Docs Offline

**Description:**  
Allows editing of Google Docs, Sheets, and Slides offline.

**Permissions Requested:**
- No special permissions
- Access limited to `docs.google.com` and `drive.google.com`
- Allowed in InPrivate mode  

**Findings:**  
- 🟢 **Low-risk** — limited, specific site access.
- Official extension developed by Google.
- Frequently used and trusted by users globally.

**Action Taken:** ✅ *Kept*  
**Reason:** Safe, essential, and minimal permissions.

---

## 📌 Summary Table

| Extension Name       | Action       | Reason                                          |
|----------------------|--------------|-------------------------------------------------|
| Sider                | ⚠️ Flagged   | High permissions; under observation             |
| Clipboard            | ✅ Kept      | Functional, low-risk                            |
| Google Docs Offline  | ✅ Kept      | Trusted source, minimal access, widely used     |

---

## ✅ Conclusion

- All extensions were manually reviewed for permissions, functionality, and potential risk.
- One extension (**Sider**) flagged for its broad access and should be re-evaluated periodically.
- Others pose no significant threat and are retained.

---
