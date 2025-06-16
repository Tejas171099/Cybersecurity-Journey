
# Port Analysis Report

## Target: 10.0.2.2

### Open Ports and Services
- **135/tcp** – Microsoft Windows RPC
- **445/tcp** – Microsoft-DS (SMB File Sharing)
- **843/tcp** – Unknown
- **2869/tcp** – Microsoft HTTPAPI HTTPD 2.0 (SSDP/UPnP)
- **6881/tcp** – Possibly BitTorrent Tracker
- **7070/tcp** – SSL/RealServer?

### Observations
- Host is likely running a Windows OS.
- Some ports are related to file sharing and remote procedure calls.
- Potential presence of peer-to-peer (BitTorrent) activity.

### Next Steps
- Investigate 6881 and 7070 for potential vulnerabilities.
- Explore SMB version on port 445 for exploitation possibilities in future modules.
