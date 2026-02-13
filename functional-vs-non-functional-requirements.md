# Functional vs Non-Functional Requirements

Understanding the difference between Functional Requirements (FR) and Non-Functional Requirements (NFR) is fundamental in software architecture.

---

## 1. Functional Requirements (FR)

Functional Requirements define what the system must do.

Examples:
- The system must allow user login.
- The system must generate a PDF report.
- The system must process online payments.

They describe behavior and business rules.

---

## 2. Non-Functional Requirements (NFR)

Non-Functional Requirements define how the system should perform or behave.

Examples:
- Login must be processed in under 2 seconds.
- The system must handle 10,000 concurrent users.
- Data must be encrypted using TLS 1.3.
- System uptime must be 99.9%.

They define quality attributes and operational constraints.

---

## 3. Architectural Impact

Ignoring NFRs often leads to architectural failures.

Example trade-off:

Security vs Performance  
- Strong encryption increases protection  
- But may increase latency  

Architecture must balance risks according to domain context.

Banking systems prioritize security.  
Streaming platforms prioritize performance.

---

## 4. Engineering Insight

Functional requirements deliver features.  
Non-functional requirements sustain the system.

A system that works but is slow, insecure or unscalable is architecturally fragile.

Good architecture anticipates growth, risk and operational complexity.

---

> Architecture is the art of balancing what the system does with how well it must do it.
