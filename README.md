# Nmap Network Scan - 10.0.2.2

**Date:** July 5, 2025  
**Tool Used:** Nmap  
**Command:** `nmap -sV -T4 10.0.2.2`  
**Purpose:** To identify active services or open ports on a discovered live host during local network reconnaissance

---

## 🔍 Scan Results:
- **Host Status:** UP  
- **Open Ports:** None detected  
- **MAC Address:** 52:55:0A:00:02:02  
- **Service Info:** All 1000 ports were filtered (net-unreachable)

---

## 🧠 Notes:
- The host is live but heavily firewalled or protected
- All ports are filtered, indicating the host may be blocking probes
- No banners or fingerprints were returned from open services
- System appears to be hardened against basic scanning attempts

---

## 🧪 What I Learned:
- How to use Nmap with flags like `-sV` (service version detection) and `-T4` (faster scan)
- The difference between "closed", "open", and "filtered" ports
- How to recognize when a system is silently ignoring scan requests
- How to log and push scan results to GitHub using Git
