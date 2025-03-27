# Dirty COW Privilege Escalation Exploit

Overview

This project demonstrates the exploitation of a vulnerable Linux virtual machine using the Dirty COW (CVE-2016-5195) exploit to escalate privileges and gain root access. The following steps were performed to achieve this:

Gained initial access to the target machine using Hydra to brute-force user credentials.

Escalated privileges using the Dirty COW exploit to obtain root access.

Retrieved admin credentials from the root directory.

Used the credentials to access a web application and capture the flag
