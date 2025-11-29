# TryHackMe — [Offensive Security Intro](https://tryhackme.com/room/offensivesecurityintro)

This room introduced me to the basics of **offensive security** and gave me my first hands-on experience using a brute-force directory-enumeration tool to uncover hidden web pages on a vulnerable website.

---

## Concepts I Learned

### 1. What Offensive Security Is

- Offensive security is the practice of **simulating real attacker behaviour** to find weaknesses before malicious attackers do.
- The goal is not to break systems, but to help organisations **strengthen their security**.

### 2. How Attackers Approach a Target

- Attackers look for the **easiest and fastest way in**.
- Hidden files, directories, or misconfigurations are often the weakest points in a website.

---

## 🛠 Practical Skills I Learned

### 1. Directory Brute-Forcing (dirb)

I used **dirb** to perform a brute-force scan of a website:

- dirb takes a **wordlist**
- It tries each word as a possible folder or file name
- When a match exists, it reveals **hidden or unlinked pages**
- These pages can sometimes contain sensitive actions, admin panels, or vulnerable endpoints

### 2. Web Reconnaissance Basics

- How to scan a target website safely
- How to identify interesting pages in the scan results
- How hidden endpoints can lead to potential exploitation

---

## 🎯 Skills Gained

- Understanding _attacker mindset_
- Basic web reconnaissance
- Using **dirb** for directory enumeration
- Recognising why hidden pages can create vulnerabilities
- Foundational knowledge for web pentesting

---

## 📌 Completed

**Date:** 2025-11-28
