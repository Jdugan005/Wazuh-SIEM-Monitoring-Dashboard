# Wazuh SIEM Deployment and Windows Agent Monitoring

This project demonstrates a functional Wazuh SIEM deployment using:
- **Wazuh Manager** running on Ubuntu
- **Wazuh Dashboard** for visualization
- **Windows 11 endpoint** connected as an agent

The goal of this project was to install, configure, and validate a working SIEM environment capable of collecting logs, monitoring system activity, and displaying security events.

Screenshots

### 🔹 1. Active Agent (Agents Page)
Shows that the Windows agent successfully connected and is reporting to the manager.
<img width="1654" height="1645" alt="Agents" src="https://github.com/user-attachments/assets/b669d7f9-d332-4acf-ad69-61cd2659cd62" />

### 🔹 2. WIN-HOST Agent Details
Displays OS information, version, keepalive status, and registration details.
<img width="1647" height="1962" alt="WIN-HOST" src="https://github.com/user-attachments/assets/d56e0139-a0c3-4240-9201-5d90037957ad" />

### 🔹 3. Security Events Dashboard
Shows alerts and event data collected from the agent.
<img width="1656" height="1995" alt="security-events" src="https://github.com/user-attachments/assets/7f3e99fe-5b0f-479c-8357-5c548ab6738d" />

### 🔹 4. Inventory Data (Syscollector)
Displays collected system information such as installed software, processes, and network interfaces.
<img width="1655" height="1991" alt="Inventory Data" src="https://github.com/user-attachments/assets/4ae72bb0-4e78-4a24-87b8-291dd50fcf80" />

##  What This Demonstrates
Through this project, I learned how to:
- Deploy a SIEM platform  
- Configure and register endpoint agents  
- Collect and view security logs  
- Use Wazuh modules like:
  - Security events  
  - Inventory (Syscollector)  
  - Agent health monitoring
