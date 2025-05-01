---
title: "CSCE 413: Software Security"
collection: teaching
type: "Regular UnderGrad Course"
permalink: /teaching/sw-security
venue: "TAMU"
date: 2025-01-01
location: "USA"
---

What to expect from this course?

The educational approach will be inspired from:

* Reverse Engineering
* Exploit Development
* Capture-the-flags (CTF)

The content will cover typical vulnerabilities in:

* Linux servers.
* Android Apps.
* Web Apps.

The projects will be hands-on. Students are expected to be able to find vulnerabilities in real apps.

Covered content:

* Introduction to Security:
    * What is Security: ACID Properties.
* Web Security:
    * OWASP Top-10 Web.
    * Directory Traversal.
    * Google Dorks.
    * Replay Attacks.
    * Authentication Failures.
    * Web Vulnerability Scanners.
    * Cross-Site Scripting (XSS).
    * SQL Injection.
* Network Security:
    * Man-In-The-Middle (MITM) Attacks.
    * MITM with ARP Spoofing.
    * Multi-Stage Attacks.
    * Services open to the Internet (Shodan).
    * Service Discovery (NMAP).
    * Secure APIs.
    * Port Scanning and Port Knocking.
    * Honeypots.
* Mobile Apps Security:
    * OWASP Top-10 Mobile.
    * Smali Code & App Repackaging.
* Application Security:
    * CVEs & Outdated Software (ExploitDB).
    * Buffer Overflows.
    * Ret2LibC.
    * Return-Oriented Programming (ROP).
    * Shellcode Development.
    * Encoding: Metasploit. 
    * ROP Defenses: Control Flow Integrity.
* Malware:
    * Rootkits & LD PRELOAD.
    * Detection with YARA Rules.
* Crypto Miscellaneous:
    * Password Cracking, Rainbow Tables, and Salting.
    * Pseudo RNGs and Ransomware Key Recovery.
* Automated Tools:
    * Vulnerability Scanners & Static Analyzers: CodeQL.
    * Fuzzing for Bug Finding with AFL.
    * Symbolic Execution with Angr.
* Tracing:
    * Syscall Tracing with Strace.
    * Function Tracing with Ltrace.
    * Performance-based Tracing with Linux Perf.
* Debugging:
    * Debugging with GDB and its Extensions (PwnTools).
    * Creating your own Debugger with PTRACE.

A few classes were recorded; Check them [HERE](https://www.youtube.com/watch?v=E8qVzi0nBII&list=PLVYZ2jULLUDu8UhB8INpfEp9jukxAvzpM)

## What we achieved in Spring/25

The students were divided in teams that inspected real applications. They discovered several vulnerabilities, as follows:

* The students developed a series of Google Dorks to query open websites: ![Google Dorks](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-12.png)

* The students easily found misconfigured websites, such as those vulnerable to directory traversal: ![Open Directories](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-11.png)

* Many web applications have their security depending only on client-side configuration parameters that can be changed: ![Privilege Escalation](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-16.png)

* These parameters can be changed pragmatically, such as by manipulating headers: ![Header Manipulation](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-9.png)

* These manipulations completely bypass authentication schemes, which cause data leakage ![Unauthorized Access with Data Leakage](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-10.png)

* Most of the findings were classical XSS attacks: ![Classic XSS 1](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-1.png)

* XSS were found in multiple websites by multiple students: ![Classic XSS 2](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-5.png)

* XSS abuse can be taken to the next level if used to inject code to steal data. The vulnerable form can be turned into a keylogger: ![Keylogger](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-6.png)

* Another post-exploitation action is cookie stealing. One can systematize stealing via a panel: ![Cookie Stealing Panel](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-8.png)

* A next level exploitation is to perform MITM attacks against application, another classic vulnerability type. One application might for instance end up transferring  credits in plain: ![MITM 1](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-2.png)

* One team could manipulate those cases to add a clearly exaggerated number of credits to their own account: ![MITM 2](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-3.png)

* One could use the control over tokens passing on the network to cause the remote deletion of one's account: ![MITM 3](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-4.png)

* Vulnerabilities are also common in mobile applications. If the application is protected by a password, one can bruteforce it: ![Bruteforce](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-7.png)

* With an unlocked phone, one team was able to trigger an intent to make an application to go to foreground while screenshoting its sensitive information: ![Accessibility Service Abuse](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-14.png)

* Don't worry though. The students were also able to patch and verify patches in the applications: ![Patches](https://marcusbotacin.github.io/teaching/FIGS/2025-sw-15.png)

All vulnerabilities were discovered to the developers.
