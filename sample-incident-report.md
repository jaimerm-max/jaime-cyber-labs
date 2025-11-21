# Sample Incident Report – Simulated Ransomware

**Analyst:** Jaime R. Martinez  
**Date:** 2025-11-21  
**Tools:** Splunk + Microsoft Sentinel + Velociraptor  

### Detection
- High-volume file encryption alerts in Splunk  
- Cobalt Strike beaconing detected via living-off-the-land techniques  

### Containment
- Isolated affected endpoint with Velociraptor  
- Blocked C2 communication at firewall  

### Key Findings (Nessus scan post-incident)
- CVE-2024-XXXX – Unpatched Windows host (Critical)  
- CVE-2023-YYYY – Missing EDR agent  

### Recommendations
- Immediate patching + EDR deployment  
- Add Sigma rule for ransomware file-write patterns  

**Status:** Resolved – No data exfiltration
