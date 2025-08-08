🔥 Task 4:Setup and Use a Firewall on Windows/Linux

📌 Objective

Configure and test basic firewall rules to allow or block network traffic, ensuring better system security.

🛠 Tools Used

**Parrot Security OS** (Debian-based penetration testing distribution)

**UFW** (Uncomplicated Firewall) (for Linux/ParrotSec users)

📋 Steps Followed

1️⃣ Open Firewall Configuration Tool
In Parrot Security, UFW is available via the terminal.  

2️⃣ Enable the UFW Uncomplicated Firewall.

3️⃣ List current firewall rules.

4️⃣ Add a rule to block inbound traffic on port 23 (Telnet).

5️⃣ Test the rule.

6️⃣ Remove the Test Rule.

7️⃣ Remove the test block rule
If it’s rule number 1 in your list, for example:

    #sudo ufw delete 1
Or Simply,

    #sudo ufw delete deny 23

📜 Commands Summary
| Action                        | Command                   |
| ----------------------------- | ------------------------- |
| List firewall rules           | `sudo ufw status verbose` |
| Block port 23 (Telnet)        | `sudo ufw deny 23`        |
| Allow SSH (port 22)           | `sudo ufw allow 22`       |
| Delete block rule for port 23 | `sudo ufw delete deny 23` |
| Enable firewall               | `sudo ufw enable`         |


🧠 How Firewall Filters Traffic

A firewall acts as a gatekeeper for your network by filtering incoming and outgoing traffic based on predefined rules.
Allow Rule: Lets traffic pass through.
Deny Rule: Blocks traffic completely.
Default Policy: Decides what happens if no specific rule matches.

📸 Deliverables

Terminal output of applied firewall rules.


✅ Outcome

By completing this task, I gained hands-on experience in:
Managing firewall rules.
Blocking and allowing network traffic.
Understanding how firewalls protect systems from unauthorized access.

🔐 Security Tip:

Always ensure SSH access is allowed before applying strict firewall rules to avoid being locked out of remote systems.







