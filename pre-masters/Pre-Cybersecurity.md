# Pre-Cybersecurity: 20-Day Compressed Preparation Plan

This plan condenses the original 40-day preparation sequence into **20 study
days**. Each day is limited to **2 hours and 10 minutes of active study** and
**3 hours total, including breaks**.

That gives you **43 hours and 20 minutes of focused study** across 20 days.
This is a fast orientation plan, not the same depth as the original 40 days.
Prioritize completing the guided labs, understanding the main ideas, and
recording questions for your master's program. You are not expected to master
every topic or memorize every command.

## How to use this plan

- Use TryHackMe Pre Security as the main beginner path.
- Use the other resources listed below only when they support that day's task.
- Work only in TryHackMe rooms, your own systems, or environments where you
  have explicit permission.
- Keep notes short. For a simple room, record the main idea, useful commands,
  one takeaway, and anything unclear.
- If a lab runs long, write down where you stopped and continue the next time.
  Do not sacrifice the final wrap-up or extend the session.
- Skip optional material before skipping the core topic or guided lab.
- Use the final focus block to capture notes, check understanding, and name the
  next action. Do not spend it decorating your notes.

## Daily time structure: 3 hours total

Follow these blocks each study day:

| Time | Activity | Minutes |
|---|---|---:|
| 00:00–00:30 | Focus block 1: learn the day's main concept | 30 |
| 00:30–00:35 | Short break | 5 |
| 00:35–01:00 | Focus block 2: guided material or lab | 25 |
| 01:00–01:10 | Break | 10 |
| 01:10–01:35 | Focus block 3: practical exercise | 25 |
| 01:35–01:40 | Short break | 5 |
| 01:40–02:05 | Focus block 4: continue the lab or apply the concept | 25 |
| 02:05–02:35 | Long break: food, movement, and rest | 30 |
| 02:35–03:00 | Focus block 5: short notes, recall, and next step | 25 |
| **Total** | **130 active minutes + 50 minutes of breaks** | **180** |

If you need a different start time, shift the whole schedule while keeping the
same lengths. Stop after three hours.

## Resources

Use the resources that fit the task; you do not need to complete every course
or collect extra materials.

- **TryHackMe Pre Security:** main beginner path for computers, networking,
  Linux, and web basics.
- **Linux Journey:** Linux concepts and command-line explanations.
- **OverTheWire Bandit:** optional beginner command-line practice.
- **Cisco introductory networking material:** optional networking reference.
- **PortSwigger Web Security Academy:** free web-security lessons and legal
  practice labs.
- **Wireshark:** inspect traffic from your own machine or a provided legal
  capture.
- **Nmap:** scan only your own system, an isolated lab, or an explicitly
  authorized TryHackMe target.
- **OWASP Juice Shop:** optional intentionally vulnerable web application for
  legal practice.

## The 20-day plan

### Day 1 — Cybersecurity foundations and computer basics

**Combines original Days 1–2.**

Study and practise:

- cybersecurity and the confidentiality, integrity, and availability (CIA)
  triad;
- threat, vulnerability, risk, exploit, and security control;
- offensive versus defensive security, and why testing needs authorization;
- CPU, RAM, storage, operating systems, applications, processes, and services;
- files, directories, users, and permissions.

Complete the relevant introductory TryHackMe Pre Security material.

**Output:** a short baseline assessment, a glossary of key terms, and a simple
diagram showing how a user action moves through an application, operating
system, process, CPU/RAM, and storage or network.

### Day 2 — Linux navigation, users, and permissions

**Combines original Days 3–4.**

Practise `pwd`, `ls`, `cd`, `cat`, `less`, `head`, `tail`, `mkdir`, `cp`, `mv`,
`rm`, `find`, and `grep`. Learn users and groups, read/write/execute
permissions, `chmod`, `chown`, hidden files, environment variables, and `sudo`.

Use a safe practice directory or the authorized TryHackMe Linux material.
Check paths before using `rm`; do not change permissions or ownership on system
files.

**Output:** a short command reference with examples and a basic Linux-user
hardening checklist.

### Day 3 — Processes, services, and Linux practice

**Combines original Days 5–6.**

Practise identifying processes, services, and logs. Use `ps`, `top`, or
`htop`; explore `systemctl` and `journalctl` in an appropriate lab. Continue
Linux practice in TryHackMe or attempt one beginner OverTheWire Bandit level.

Do not look up a solution immediately: try, record what you attempted, research
one specific obstacle, then record the lesson.

**Output:** a short list of services you inspected, what they do, and where you
would look for related logs; add one brief Bandit note if you attempted a
challenge.

### Day 4 — Review and network concepts

**Combines original Days 7–8.**

Briefly review Days 1–3, then study network interfaces, IP and MAC addresses,
ports, protocols, clients and servers, and private versus public networks.
Complete the introductory TryHackMe networking material.

**Output:** a simple home or lab network diagram and a list of three concepts
you want to review.

### Day 5 — TCP, UDP, and DNS

**Combines original Days 9–10.**

Study TCP versus UDP, the TCP handshake, connection reliability, common ports,
and why services listen on ports. Study domain names, resolvers, DNS records,
and nameservers. Practise `nslookup` or `dig` on ordinary public domains.

**Output:** explain in a few sentences how a browser finds and connects to a
web server; include one DNS lookup and identify what its result means.

### Day 6 — HTTP/HTTPS and Nmap

**Combines original Days 11–12.**

Study HTTP requests and responses, methods, status codes, headers, cookies, and
TLS at a high level. Inspect a request with browser developer tools or `curl`.
Learn what Nmap host discovery, port scanning, and service detection report.

Scan only your own machine, an isolated lab, or an explicitly authorized
TryHackMe target.

**Output:** annotate one HTTP request and write a short, factual summary of one
authorized Nmap result. A scan identifies possible services; it does not prove
that a service is vulnerable.

### Day 7 — Wireshark and networking review

**Combines original Days 13–14.**

Use Wireshark with traffic from your own machine or a provided legal capture.
Practise locating DNS traffic, following a TCP stream, and recognizing basic
connection patterns. Review host, service, and port concepts.

**Output:** a short packet-capture explanation or, if no capture is available,
a beginner network-assessment note that records the host, services, concerns,
and next questions. Do not exploit anything.

### Day 8 — Linux permissions, services, processes, and logs

**Combines original Days 15–16.**

Review ownership, users, groups, `sudo`, environment variables, and absolute
versus relative paths. Practise identifying processes and services and reading
relevant logs in a legal lab.

**Output:** a short Linux hardening and service/log checklist. Explain one way
poor permissions could create a security problem.

### Day 9 — Bash and Windows basics

**Combines original Days 17–18.**

Learn the basics of Bash variables, conditions, loops, pipes, redirection, and
searching command output. Study Windows users and groups, processes, services,
shares, event logs, and basic PowerShell.

**Output:** a small, commented Bash exercise or command pipeline, plus a short
comparison of how Linux and Windows represent users, services, and logs.

### Day 10 — Virtual machines, lab safety, and hardening

**Combines original Days 19–20.**

Review snapshots, NAT versus host-only networking, isolated lab design, and
why vulnerable machines should not be exposed to the public internet. Review
legal testing boundaries. Study updates, firewalls, SSH security, logging,
backups, unnecessary services, and least privilege.

**Output:** a small lab-network diagram and a short Linux/Windows hardening
checklist.

### Day 11 — Operating-system review and web-application basics

**Combines original Days 21–22.**

Recall what a process, service, port, permission, log entry, firewall rule, and
virtual-machine network are. Then study browsers, web servers, application
servers, databases, HTTP, cookies, and sessions.

**Output:** draw the flow of a login request from browser to server and database
and back. Mark any step you cannot explain yet.

### Day 12 — Burp Suite and access control

**Combines original Days 23–24.**

In an introductory PortSwigger or TryHackMe lab, practise viewing HTTP history
and using Burp Proxy and Repeater. Learn authentication versus authorization,
sessions, access control, IDOR, and privilege boundaries.

**Output:** explain one request you inspected and why being logged in does not
automatically mean a user may access every object.

### Day 13 — SQL injection, XSS, and CSRF

**Combines original Days 25–26.**

Use beginner web-security labs to understand unsafe input handling, database
queries, parameterized queries, reflected and stored XSS, output encoding,
CSRF tokens, and same-origin concepts. Focus on why each weakness occurs and
how to prevent it, not memorizing payloads.

**Output:** explain the difference between SQL injection, XSS, and CSRF in your
own words and record one defensive measure for each.

### Day 14 — Other web vulnerabilities and a mini-assessment

**Combines original Days 27–28.**

Study introductory examples of path traversal, file-upload flaws, command
injection, and information disclosure. Apply the ideas to a short, explicitly
authorized PortSwigger lab or OWASP Juice Shop exercise.

**Output:** a compact assessment note with scope, what you tested, one
observation or finding, evidence, potential impact, remediation, and
limitations. If you do not confirm a vulnerability, report that honestly.

### Day 15 — Pentest methodology and reconnaissance

**Combines original Days 29–30.**

Study authorization, scope, rules of engagement, reconnaissance, enumeration,
validation, reporting, and retesting. Practise identifying hosts and services
in a legal lab and deciding what to investigate next.

**Output:** a one-page beginner testing workflow and a short enumeration
checklist.

### Day 16 — Vulnerability validation and exploitation concepts

**Combines original Days 31–32.**

Learn why scanner results need manual verification, how false positives occur,
and how evidence, severity, and business impact relate. Understand the
conceptual difference between an exploit, payload, shell, reverse shell, bind
shell, privilege escalation, and post-exploitation.

Keep activity inside authorized training environments; advanced exploitation
is not required.

**Output:** assess three example findings for what needs verification and
explain the difference between finding a vulnerability and successfully
exploiting it.

### Day 17 — Digital forensics and evidence

**Combines original Days 33–34.**

Study digital evidence, timestamps, filesystems, logs, evidence preservation,
and chain of custody. With a legal sample, inspect a small log set or PCAP and
identify relevant timestamps and events.

**Output:** a short evidence-preservation checklist and a brief incident
timeline or analysis note.

### Day 18 — Integrated mini-assessment and report improvement

**Combines original Days 35–36.**

In a legal beginner lab, perform a small scoped assessment: reconnaissance,
enumeration, basic vulnerability identification, evidence collection, and
remediation thinking. Improve the report for clarity, structure, severity,
evidence, remediation, grammar, and professional tone.

Do not force an advanced exploit chain.

**Output:** one concise beginner report with scope, method, finding(s), evidence,
impact, remediation, and limitations. Clearly label anything that remains
unverified.

### Day 19 — Active recall and timed practical

**Combines original Days 37–38.**

Start by answering from memory: what happens after entering a URL, what DNS and
ports do, TCP versus UDP, cookies, authentication, authorization, SQL injection,
XSS, privilege escalation, Nmap, Burp Suite, and false positives. Check your
answers, then do a short, authorized practical exercise with a timer.

**Output:** a timed activity log, three weak areas, and one next step for each.

### Day 20 — Master's preparation pack and final review

**Combines original Days 39–40.**

Create a compact reference containing a networking glossary, Linux commands,
HTTP terms, a web-vulnerability checklist, Nmap notes, a reporting template,
questions for your professors, and topics you found difficult. Do one brief
Linux exercise, one networking exercise, one web-security exercise, and
explain the basic testing workflow.

Do not start a new major topic or cram. Finish by writing what you understand,
what remains unclear, and what you want to improve during the first month of
your master's. Then stop and rest.

**Output:** a one-place reference pack and a short list of questions and
priorities for the master's.

## Practical note-taking template

Keep short-room notes proportional to the room. This is enough:

```markdown
# [Room or lab name]

- **Link:**
- **Date:**
- **Status:** In progress / Complete

## Main idea
Write 2–4 sentences.

## What I learned
- 
- 

## Commands or actions
- `command` — what it did

## One takeaway
Write the most useful thing to remember.

## Still unclear
- None, or list a question.

## Next step
- 
```

Do not save passwords, API keys, access tokens, session cookies, private keys,
VPN configuration files, or personal information in your notes or GitHub.
Write your own explanations; do not upload complete copied solutions to active
course exercises.

## End-of-plan check

At the end of Day 20, check whether you can:

- describe the CIA triad and the difference between a threat and a
  vulnerability;
- navigate a Linux system and explain basic permissions;
- describe processes, services, and logs;
- explain IP addresses, ports, TCP/UDP, DNS, and a basic HTTP request;
- explain what Nmap, Wireshark, and Burp Suite do at a beginner level;
- recognize common beginner web-security concepts;
- describe the stages of an authorized security assessment;
- record evidence and write a clear, limited finding;
- identify what you still need to learn during the master's.

You do not need to answer every item perfectly. Use gaps to guide your next
month of study.