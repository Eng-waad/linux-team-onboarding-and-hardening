# Bonus Challenges Solutions

## Challenge 1 – List All Human Users

```bash
awk -F: '$3 >= 1000 {print $1}' /etc/passwd
Challenge 2 – Verify Group Membership

groups hammam
groups maitha

Challenge 3 – Check Sudo Privileges

sudo -l -U maitha
sudo -l -U renad

Challenge 4 – Verify SSH Hardening

cat /etc/ssh/sshd_config | grep PermitRootLogin

Expected:
PermitRootLogin no
