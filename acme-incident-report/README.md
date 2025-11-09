# Acme Financial Services – Security Incident Analysis  
**Analyst:** Hatice Nalçacı  
**Date:** November 2025  

## Deliverables
- `Hatice_Nalçacı_Report.pdf` – 4-page forensic report (CSV references included)  
- `improved_architecture.png` – Proposed secure architecture  
- **Video Presentation (10 min)**: [YouTube – Unlisted](https://www.youtube.com/watch?v=DlWB7EulSGw)  

## Key Findings
- **Phishing → Credential Theft → IDOR → SQLi Bypass → Full Data Exfiltration**  
- **900 KB user data stolen** in under **25 minutes**  
- **Root Causes**: No object-level auth, WAF gap, no rate limit  

## Log Files (Already in Repository)
- `email_logs.csv` → Phishing evidence  
- `api_logs.csv` → Token theft + IDOR  
- `web_logs.csv` → SQLi + WAF bypass  
- `export_logs.csv` → Data exfiltration  

## Tools Used
- Google Docs, Excel, draw.io, Loom, YouTube  

**Ready for technical review.**