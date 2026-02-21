# 🐧 Linux CTF Challenge

I completed the **Linux CTFs** challenge from the LearnToCloud community to strengthen my hands-on Linux administration, cloud troubleshooting, and security investigation skills.

This repository highlights the **technical competencies demonstrated** throughout the challenges — without revealing flags or solutions.

The focus of this write-up is to showcase practical Linux problem-solving, service analysis, and networking techniques applicable to real-world environments.

---
## 📎 Challenge Source

Linux CTFs by LearnToCloud  
https://github.com/learntocloud/linux-ctfs

---

## Challenges

| # | Challenge | Description | Difficulty | Skills |
|---|-----------|-------------|------------|--------|
| 1 | The Hidden File | Find and read a hidden file in `ctf_challenges` | ⭐ | Hidden files, `ls` |
| 2 | The Secret File | Locate a file containing "secret" in its name under your home directory | ⭐ | File searching, `find` |
| 3 | The Largest Log | Find and read an unusually large file in `/var/log` | ⭐⭐ | File sizes, log navigation |
| 4 | The User Detective | A user with UID 1002 has a flag in their login configuration | ⭐⭐ | User management, UIDs |
| 5 | The Permissive File | Find a suspicious file with wide-open permissions under `/opt` | ⭐⭐ | Permissions |
| 6 | The Hidden Service | Something is listening on port 8080. Connect to it | ⭐⭐ | Networking, ports |
| 7 | The Encoded Secret | Find and decode an encoded flag in `ctf_challenges` | ⭐⭐ | Base64, encoding |
| 8 | SSH Key Authentication | Configure SSH key authentication and find a hidden flag | ⭐⭐ | SSH configuration |
| 9 | DNS Troubleshooting | Someone modified a critical DNS config file. Fix it | ⭐⭐ | DNS, `/etc/resolv.conf` |
| 10 | Remote Upload | Transfer any file to `ctf_challenges` to trigger the flag | ⭐⭐ | File transfer, SCP |
| 11 | Web Configuration | The web server is running on a non-standard port. Find and fix it | ⭐⭐ | Nginx, services |
| 12 | Network Traffic Analysis | Someone is sending secret messages via ping packets | ⭐⭐⭐ | Packet inspection, tcpdump |
| 13 | Cron Job Hunter | A scheduled task contains a hidden flag. Find and read it | ⭐⭐ | Cron, scheduling |
| 14 | Process Environment | A running process has a secret in its environment. Extract it | ⭐⭐⭐ | `/proc`, environment vars |
| 15 | Archive Archaeologist | A flag is buried inside nested archives. Dig it out | ⭐⭐ | tar, gzip, archives |
| 16 | Symbolic Sleuth | Follow the trail of symbolic links to find the flag | ⭐⭐ | Symlinks, `readlink` |
| 17 | History Mystery | Someone typed a flag in their command history. Find it | ⭐⭐ | Bash history |
| 18 | Disk Detective | A flag is hidden in filesystem metadata. Investigate mounted filesystems | ⭐⭐⭐ | Disk images, mounting |

**Difficulty:** ⭐ Beginner | ⭐⭐ Intermediate | ⭐⭐⭐ Advanced

---

## 🔧 Core Linux Commands Used

| Command    | Purpose                                                                    |
| ---------- | -------------------------------------------------------------------------- |
| `cd`       | Navigate between directories within the filesystem.                        |
| `ls`       | List files and directories in the current location.                        |
| `ls -la`   | Display detailed file information, including hidden files and permissions. |
| `cat`      | Output file contents directly to the terminal.                             |
| `tar`      | Create or extract compressed archive files.                                |
| `find`     | Search for files and directories based on specific criteria.               |
| `ps aux`   | Display detailed information about active processes.                       |
| `curl`     | Interact with web services and test HTTP endpoints.                        |
| `ss`       | Inspect active network sockets and listening ports.                        |
| `kill`     | Terminate running processes using their PID.                               |
| `iptables` | Manage firewall and packet filtering rules.                                |
| `tcpdump`  | Capture and analyze live network traffic.                                  |

---
# 🧩 Challenging Exercises & Key Takeaways

The following challenges required deeper investigation, structured troubleshooting, and persistence. Each pushed me to refine my methodology and strengthen specific areas of Linux proficiency.

| Challenge | Why It Was Difficult | Key Growth Area |
|------------|---------------------|-----------------|
| **Web Configuration** | Service was running on a non-standard port, requiring careful configuration review and port verification. | Improved understanding of how services bind to ports and how configuration impacts accessibility. |
| **Network Traffic Analysis** | Required isolating meaningful data from live packet captures without being overwhelmed by background traffic. | Strengthened packet filtering techniques and protocol interpretation skills. |
| **Process Environment** | Sensitive data was embedded within a running process, requiring inspection of runtime system data. | Deepened understanding of the `/proc` filesystem and how processes store environment variables. |
| **Hidden Service** | A service was listening silently on an unexpected port, requiring systematic enumeration. | Reinforced disciplined port scanning and evidence-based troubleshooting. |

---

## 🔍 What These Challenges Reinforced

- Effective troubleshooting begins with structured observation and disciplined enumeration.  
- Assumptions should always be validated through direct system and runtime inspection.  
- Processes, services, and network behavior must be analyzed in context to understand root causes.  
- Careful examination of runtime data (process environments, active connections, traffic flows) can surface critical insights.  
- Persistence and methodical thinking are often more valuable than speed when resolving complex issues.  

These challenges strengthened both my technical diagnostic skills and my ability to approach unfamiliar systems with confidence, precision, and a structured problem-solving mindset.
