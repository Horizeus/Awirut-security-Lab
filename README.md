# Awirut Security Lab

This repository documents ethical security reconnaissance and attack surface research on public web assets.

The goal of this lab is to understand how modern organizations expose systems to the internet — including web applications, APIs, cloud infrastructure, and supporting services — and to identify where risk emerges from visibility, misconfiguration, and forgotten assets.

All work in this repository is based on:
- Passive and active reconnaissance
- Publicly accessible information
- Non-intrusive testing
- Responsible research principles

No unauthorized access, exploitation, or data modification is performed.

---

## What You Will Find Here

This repository contains structured research across multiple targets, including:

- Subdomain enumeration  
- URL and endpoint discovery  
- API surface mapping  
- JavaScript analysis  
- Cloud and infrastructure exposure  
- Authentication and access models  
- Security-relevant misconfigurations  

Each target has its own directory with raw data and notes.  
Each finding has a report explaining what was discovered, why it matters, and how it can be fixed.

---

## Why This Exists

Security failures rarely begin with a single exploit.  
They begin with **unknown surface area** — systems that exist but are not tracked, monitored, or protected.

This lab focuses on making the invisible visible.

By documenting real-world attack surfaces, this repository serves as:
- A learning environment  
- A technical portfolio  
- A reference for defenders and researchers  

---

## Methodology

The research process generally follows:

1. Identify domains and subdomains  
2. Determine which assets are live  
3. Collect URLs, endpoints, and APIs  
4. Analyze JavaScript and client-side logic  
5. Observe authentication and access behavior  
6. Identify exposed, forgotten, or misconfigured assets  
7. Document findings clearly and reproducibly  

Tools used include industry-standard reconnaissance and security testing utilities.

---

## Ethics & Scope

All targets are:
- Publicly accessible  
- Not protected by login or authorization  
- Not subject to private agreements or restricted scopes  

Any sensitive discoveries are handled with responsible disclosure when appropriate.

This lab exists to improve security, not to harm it.
