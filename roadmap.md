Week 1 (Oct 1–7): Foundations
Day	Learn + Lab	GitHub
1 Oct 1	Set up Kali VM, TryHackMe, GitHub profile README, LinkedIn headline ("Aspiring Security Analyst | Learning in public")	Create repo + README roadmap
2	CIA triad, threats, attack types	notes/01-fundamentals.md
3	Networking: OSI, TCP/IP, IP, subnetting	notes/02-networking.md
4	DNS, HTTP, ports; Wireshark intro	labs/wireshark-first-capture.md
5	Linux CLI (THM Linux Fundamentals)	notes/linux-cheatsheet.md
6	Linux permissions, processes, bash scripting	scripts/log_grep.sh
7	Review, week write-up	weekly-log/week-01.md

Week 2 (Oct 8–14): Python for security + Project 1
Day	Learn + Lab	GitHub
8	Python recap: files, functions, modules	scripts/py-basics/
9	Python sockets, build basic port scanner	Repo port-scanner v0.1
10	Threading + argparse for scanner	v0.2
11	Nmap deep dive	notes/nmap.md
12	Wireshark filters, traffic analysis	labs/wireshark-filters.md
13	Hashing vs encryption; password strength checker	Repo password-audit-tool
14	Polish scanner README, review	weekly-log/week-02.md

Week 3 (Oct 15–21): Security core
Day	Learn + Lab	GitHub
15	Cryptography, TLS	notes/crypto.md
16	Python AES/RSA demo	scripts/crypto-demo.py
17	Authentication, IAM, MFA	notes/iam.md
18	Malware types, social engineering	notes/malware-social-eng.md
19	Phishing email header analysis lab	labs/phishing-analysis.md
20	CVE, CVSS, OpenVAS scan of own VM	labs/vuln-scan-report.md
21	Review + quiz	weekly-log/week-03.md

Week 4 (Oct 22–28): Web security 1
Day	Learn + Lab	GitHub
22	HTTP, cookies, sessions; Burp setup	notes/burp-setup.md
23	OWASP Top 10; deploy DVWA/Juice Shop	notes/owasp-top10.md
24	SQL injection theory + DVWA	labs/sqli-dvwa.md
25	PortSwigger SQLi labs	writeups/portswigger-sqli.md
26	XSS (reflected, stored, DOM)	labs/xss.md
27	XSS labs + CSRF	writeups/xss-csrf.md
28	Review	weekly-log/week-04.md

Week 5 (Oct 29–Nov 4): Web security 2 + start Project 2
Day	Learn + Lab	GitHub
29	Broken auth, access control, IDOR	writeups/idor.md
30	File upload, command injection, path traversal	labs/injection-types.md
31	SSRF, XXE, deserialization overview	notes/advanced-web.md
32	Burp Repeater/Intruder workflow	labs/burp-workflow.md
33	Juice Shop challenges	writeups/juice-shop-1.md
34	Start Project 2: Python web vulnerability scanner (requests, BeautifulSoup)	Repo web-vuln-scanner init
35	Continue scanner; review	weekly-log/week-05.md

Week 6 (Nov 5–11): Project 2 + recon
Day	Learn + Lab	GitHub
36	Scanner: crawler + form detection	commit crawler
37	Scanner: SQLi/XSS payload checks	commit checks
38	Scanner: HTML/JSON report output	commit reporting
39	Tests, README, demo GIF	release v1.0
40	Recon, OSINT, Google dorking	notes/recon.md
41	Full pentest report on Juice Shop	writeups/juice-shop-pentest-report.md
42	Review	weekly-log/week-06.md

Week 7 (Nov 12–18): Pentest methodology
Day	Learn + Lab	GitHub
43	Pentest phases, Metasploit basics	notes/pentest-methodology.md
44	Enumeration: SMB, FTP, SSH	labs/enumeration.md
45	Exploitation (THM Metasploit room)	writeups/metasploit.md
46	Linux privilege escalation	writeups/linux-privesc.md
47	Windows privilege escalation	writeups/windows-privesc.md
48	Beginner CTF boxes (Blue, Kenobi)	writeups/ctf-boxes-1.md
49	Review	weekly-log/week-07.md

Week 8 (Nov 19–25): Network attacks + Active Directory
Day	Learn + Lab	GitHub
50	ARP spoofing/MITM (own lab only)	labs/mitm-lab.md
51	Firewalls, IDS/IPS, wireless theory	notes/network-defense.md
52	Active Directory basics	notes/active-directory.md
53	AD attacks overview (Kerberoasting)	writeups/ad-attacks.md
54	Easy machine 1	writeups/machine-1.md
55	Easy machine 2	writeups/machine-2.md
56	Mid-point retrospective	weekly-log/week-08.md

Week 9 (Nov 26–Dec 2): Blue team 1 + Project 3
Day	Learn + Lab	GitHub
57	SOC fundamentals, MITRE ATT&CK	notes/soc-attack.md
58	Linux/Windows event logs	labs/log-analysis.md
59	Splunk install + basics	notes/splunk-basics.md
60	Splunk searches, dashboards	labs/splunk-dashboard.md
61	Start Project 3: log analyzer / brute-force detector (Python)	Repo log-threat-detector init
62	Detection rules + alerts	commit detection
63	Review	weekly-log/week-09.md

Week 10 (Dec 3–9): Blue team 2
Day	Learn + Lab	GitHub
64	Project 3: dashboard/report output	commit
65	Project 3: README, sample logs, release	v1.0
66	Incident response lifecycle (NIST)	notes/incident-response.md
67	Forensics basics (Autopsy)	labs/forensics.md
68	Static malware analysis basics	labs/malware-static.md
69	THM SOC Level 1 rooms	writeups/soc-level1.md
70	Review	weekly-log/week-10.md

Week 11 (Dec 10–16): Cloud, secure coding, capstone plan
Day	Learn + Lab	GitHub
71	Cloud security basics (AWS IAM, S3 misconfig)	notes/cloud-security.md
72	AWS free-tier hardening lab	labs/aws-hardening.md
73	Docker/container security	labs/docker-security.md
74	Secure coding; review Java code for vulnerabilities	notes/secure-coding.md
75	Plan capstone: home-lab security assessment	Repo homelab-security-assessment
76	Build lab (vulnerable VMs + Splunk)	lab diagram
77	Review	weekly-log/week-11.md

Week 12 (Dec 17–23): Capstone
Day	Learn + Lab	GitHub
78	Recon + scanning	01-recon.md
79	Exploitation	02-exploitation.md
80	Detection in Splunk	03-detection.md
81	Hardening + fixes	04-hardening.md
82	Final assessment report (PDF)	report.pdf
83	README, architecture diagram, demo video	release
84	Review	weekly-log/week-12.md

Week 13 (Dec 24–30) + Day 92: Job-ready
Day	Learn + Lab	GitHub
85	Rebuild resume (projects, tools, links)	resume/ (PDF only)
86	Optimize LinkedIn; portfolio README	profile README update
87	Interview prep: networking, Linux, web	interview-notes/technical.md
88	Interview prep: SOC scenarios	interview-notes/scenarios.md
89	Mock interview + Security+ practice test	interview-notes/mock.md
90	Apply to 10 roles + 5 referral messages	job-tracker.md (no private info)
91	Apply 10 more; follow-ups	weekly-log/week-13.md
92 Dec 31	Final retro and 2027 roadmap	retrospective.md
LinkedIn: 1 post per week (Sundays)
Add 1–2 screenshots/GIFs and the GitHub link; end with a question. Use #cybersecurity #infosec #learninginpublic.

