
---

### 🚀 Deployment & Automation (1–15)
1. Write a script to deploy a Node.js app with PM2.
2. Automate pulling the latest Git branch and restarting a service.
3. Create a script that packages a directory into a `.tar.gz` and uploads it to S3.
4. Write a script that checks if Jenkins is running and restarts it if not.
5. Script a Docker image build and push to a private registry.
6. Automate creation of a versioned release folder with a timestamp.
7. Script to SSH into multiple servers and run a deploy command.
8. Write a script that watches a Git repo and deploys on new commit.
9. Deploy a WAR file to a remote Tomcat server using SCP + SSH.
10. Rollback the deployment if the service health check fails.
11. Clone a repo, build with Maven, and deploy to `/opt/app`.
12. Write a script to run database migrations after deployment.
13. Script to rotate deployment logs weekly.
14. Automate the download and install of the latest AWS CLI on Linux.
15. Write a script that reads service names from a file and restarts them all.

---

### 🖥️ Server Management (16–30)
16. Script to check CPU usage and log a warning if above 90%.
17. Find and kill processes using more than 2GB memory.
18. Clean `/tmp` and `/var/tmp` folders safely.
19. Restart a service if it stops responding to curl.
20. Script to get IP address of all network interfaces.
21. Disable a user account automatically at midnight.
22. Rotate logs in `/var/log/custom/` daily.
23. Update and upgrade packages using a script.
24. Monitor uptime and notify if rebooted.
25. Check if critical services (`nginx`, `docker`, `mysql`) are running.
26. Auto-restart crashed systemd services.
27. Compare kernel version across multiple servers.
28. Backup `/etc` folder weekly with compression and checksum.
29. Report all open TCP/UDP ports to a log file.
30. Schedule a reboot every Sunday at 3 AM via script and cron.

---

### 📝 File Editing & Parsing (31–45)
31. Replace all IPs in a file with a placeholder using `sed`.
32. Extract email addresses from a log file using `grep` or `awk`.
33. Delete lines containing a keyword from a config file.
34. Append a line only if it does not already exist.
35. Format a log file to CSV using `awk`.
36. Rename all `.log` files with today's date appended.
37. Add a block of configuration to `nginx.conf` using a script.
38. Extract the 3rd column from a space-delimited file.
39. Count how many times each word appears in a file.
40. Merge two files line by line.
41. Script to find files larger than 500MB and list their paths.
42. Convert all `.txt` files in a folder to `.md`.
43. Generate an inventory file from a list of servers.
44. Create a list of all executable files in `/usr/bin/`.
45. Archive and compress files modified in the last 24 hours.

---

### 🔪 Process & Service Management (46–60)
46. Script to kill all processes by a given name.
47. Alert if a process stops running.
48. List all running services with their PIDs.
49. Restart a systemd service using shell script.
50. Identify top 5 CPU-consuming processes and log them.
51. Monitor a specific PID and alert if it exits.
52. Check if a given port is in use and by which PID.
53. Auto-start services on boot using script + `systemctl`.
54. Monitor zombie processes and clean them up.
55. Start multiple background jobs from a list.
56. Monitor resource usage of a process over time.
57. Kill all user sessions except the current one.
58. Write a script to create a systemd service from scratch.
59. Kill all child processes of a specific parent process.
60. Monitor and log high memory processes every 5 min.

---

### 📈 Monitoring & Logging (61–75)
61. Script to log CPU and RAM usage every minute.
62. Monitor disk space and alert if usage exceeds 85%.
63. Ping multiple hosts and log downtime with timestamps.
64. Monitor `/var/log/auth.log` for failed SSH attempts.
65. Log open network connections every 10 seconds.
66. Generate a daily report of service uptime.
67. Monitor load average and send an alert if > 5.
68. Use `top` or `ps` in a script to create a daily resource usage report.
69. Parse `/var/log/syslog` and extract ERROR entries.
70. Log all files accessed in `/etc/` using `auditd` and a script.
71. Create a rotating log system for a custom app.
72. Alert if new users are created in `/etc/passwd`.
73. Send system metrics via email using a shell script.
74. Script to upload logs to S3 weekly.
75. Track file changes using `inotify` in a script.

---

### 🔐 Security & User Management (76–85)
76. Script to create users in bulk with passwords.
77. Lock inactive users for 30+ days.
78. Monitor `/etc/passwd` and log changes.
79. Check password expiration for all users.
80. Find users with UID 0 other than root.
81. Block SSH access to a user from a script.
82. List users currently logged in and how long.
83. Create a script to change all users' shell to `/bin/bash`.
84. Disable root login in sshd_config using a script.
85. Audit all sudoers entries and back them up.

---

### 💡 Scripting & Logic (86–95)
86. Accept two arguments and perform arithmetic.
87. Script to calculate factorial using recursion.
88. Parse input CSV and generate JSON from it.
89. Accept a filename and print number of lines, words, characters.
90. Find and print palindrome strings from a file.
91. Check if a given year is leap year using shell.
92. Build a menu-based script with user options.
93. Script to read a list of IPs and ping them concurrently.
94. Use `case` to create a file operation menu.
95. Accept multiple input arguments and loop through them.

---

### 🧪 Testing, Debugging & Utilities (96–100)
96. Add logging and error handling to any script using `trap` and `set -e`.
97. Create a dry-run flag for a deployment script.
98. Log script execution start and end times with duration.
99. Detect the OS and execute OS-specific commands.
100. Debug a shell script that fails silently (use `set -x`).


