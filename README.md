# Linux Team Onboarding & Server Hardening Lab

## Project Overview

This project simulates onboarding a new technical team on a Linux server following security best practices.

The lab covers:

- User and group management
- Role-based access control
- Sudo configuration
- SSH key authentication
- Server hardening
- Principle of Least Privilege implementation

---

## Users Created

| Username | Role       |
|-----------|------------|
| hammam    | Developer  |
| muath     | Developer  |
| saad      | Developer  |
| maitha    | Sysadmin   |
| renad     | Deployer   |

---

## Groups

- developers
- sysadmins
- deployers

---

##  Sudo Configuration

- Sysadmin granted full sudo access.
- Deployer granted limited scoped sudo access.
- Developers have no sudo privileges.

---

## SSH Security

- Ed25519 keys generated.
- Root login disabled.
- SSH hardened.
- Hostname configured.

---

##  Screenshots

All execution proof is available inside the `screenshots` folder.

---

## Security Concepts Applied

- Individual accounts
- Role-based group design
- Least privilege principle
- Scoped sudo rules
- SSH key authentication
- Root login disabled

---

##  Notes

This repository contains my personal implementation and verification of the lab environment.
Original assignment instructions are not included. 
