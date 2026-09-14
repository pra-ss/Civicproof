

CivicProof 🛡️

Proof before “resolved.”

«Don’t just mark it resolved. Prove it.»

CivicProof is a verifiable civic complaint platform designed to create an auditable trail for every report, action, and resolution.

Instead of allowing a complaint to simply be marked “Resolved,” CivicProof requires verifiable resolution evidence and gives citizens the ability to confirm or dispute the outcome.

---

🚨 The Problem

Citizens report civic issues, but often cannot clearly see what happens afterward.

- Complaints can disappear into the system.
- Status updates can overwrite the original history.
- A complaint may be marked “Resolved” without strong evidence that the issue was actually fixed.
- Citizens may have limited ability to challenge an incorrect resolution.
- Public accountability can be difficult without exposing citizens' private information.

CivicProof solves this by making proof part of the resolution process.

---

💡 Our Solution

CivicProof turns every important civic action into a verifiable event.

The core flow

Report → Track → Prove → Verify

1. Citizen submits a complaint with evidence.
2. Evidence receives a unique fingerprint.
3. The department accepts and acts on the complaint.
4. The responsible officer submits resolution evidence.
5. The system checks the evidence.
6. The citizen confirms or disputes the resolution.

If the required proof is missing or inconsistent, the system does not silently accept “Resolved.”

---

⭐ Key Features

1. 🧬 Complaint DNA

Every complaint receives a unique identity.

The Complaint DNA links:

- Complaint ID
- Original report
- Evidence fingerprint
- Timestamp
- Subsequent events

Example:

"CIV-2026-004821"

Sensitive evidence is kept off-chain while a verifiable fingerprint/reference can be used for integrity checking.

---

2. 📜 Immutable Timeline

Every important action becomes a traceable event.

Example:

10:42 AM  Complaint submitted
10:43 AM  Evidence registered
11:05 AM  Assigned to Electrical Department
12:17 PM  Officer accepted
Next day   Repair evidence uploaded
2:30 PM   Citizen verification requested

The purpose is to prevent silent changes to the history of a complaint.

---

3. 🚫 Proof Before “Resolved”

An officer cannot simply click Mark Resolved.

The system requires resolution proof such as:

- After image
- Location
- Timestamp
- Resolution note

The evidence then goes through verification checks before the case becomes eligible for citizen verification.

---

4. 🔎 Evidence Verification

CivicProof can check for potential evidence anomalies, including:

- Location consistency
- Timestamp sanity
- Before/after comparison
- Duplicate evidence
- Missing or weak proof

AI assistance is intended as an anomaly-detection aid, not absolute proof.

---

5. 👤 Citizen Verification & Disputes

After a resolution is submitted, the citizen can choose:

- ✅ Issue fixed
- 🟡 Partially fixed
- ❌ Still unresolved

If a citizen disputes a resolution:

- The evidence remains visible.
- The original resolution remains in the history.
- The case can be escalated for review.

---

6. 🧾 Civic Resolution Receipt

Verified resolutions can generate a compact, shareable Civic Resolution Receipt.

It can contain:

- Complaint category
- Complaint ID
- Department
- Before evidence verification
- After evidence verification
- Integrity verification
- Location consistency
- Citizen verification
- Resolution status

A public verification page can show safe, non-sensitive information while protecting citizen identity.

---

🎯 Additional Features / Future Scope

The platform can be extended with:

- 👻 Ghost Resolution Detector
- ⏱️ SLA Countdown
- 🚨 Automatic Escalation
- 🗺️ Accountability Heatmap
- 🔁 Duplicate Issue Clustering
- ⭐ Resolution Quality Score
- 🔒 Privacy-Preserving Identity
- 🔍 One-click Audit Mode

These features focus on accountability and verified outcomes rather than simply counting closed complaints.

---

🏗️ Proposed Architecture

                 CIVICPROOF
                     │
        ┌────────────┴────────────┐
        │                         │
    FRONTEND                  CITIZEN PORTAL
        │                         │
        └────────────┬────────────┘
                     │
                  BACKEND
                     │
       ┌─────────────┼─────────────┐
       │             │             │
 Complaint API   SLA Engine   Notifications
       │
       ▼
 VERIFICATION LAYER
       │
 ┌─────┼─────────────────────┐
 │     │          │          │
Hashing Evidence  AI       Disputes
       Checks     Anomaly
                  Detection
                     │
                     ▼
                 WEB3 LAYER
                     │
          Immutable Event Hashes
             Smart-Contract Rules
                     │
                     ▼
                  STORAGE
                     │
       Encrypted Off-chain Evidence
                     +
        On-chain Fingerprints/References

The blockchain layer is intended specifically for integrity and auditability, rather than adding unnecessary complexity.

---

🛠️ Technology Stack

Current Prototype

- HTML5
- CSS3
- JavaScript
- Responsive web interface
- Client-side prototype logic

Planned Production Stack

- Frontend web application
- Backend complaint API
- Authentication
- Encrypted evidence storage
- Hashing and evidence verification
- AI-assisted anomaly detection
- Blockchain transactions
- Smart contracts
- SLA and escalation engine

---

🎬 Demo Flow

The prototype is designed around a failure-first demonstration:

Citizen reports broken streetlight
             ↓
Officer clicks "Mark Resolved"
             ↓
       ❌ BLOCKED
       Proof Required
             ↓
Officer uploads unrelated proof
             ↓
     ❌ LOCATION MISMATCH
             ↓
Correct resolution evidence uploaded
             ↓
      ✅ VERIFICATION PASSED
             ↓
Citizen receives verification request
             ↓
Citizen selects "Still unresolved"
             ↓
        ⚠️ DISPUTE
             ↓
Timeline preserves the complete history

The goal is simple: a resolution should be proven, not merely declared.

---

🔐 Privacy

CivicProof is designed so that public verification does not require exposing a citizen's private identity.

Public verification is intended to reveal only safe information such as:

- Complaint category
- Approximate location
- Date
- Status
- Evidence verification
- Audit history

Sensitive citizen information and raw evidence are intended to remain protected.

---

📁 Project Structure

CivicProof/
│
├── index.html
├── style.css
├── app.js
├── README.md
│
└── assets/
    ├── dashboard.png
    ├── verification.png
    ├── dispute.png
    └── receipt.png

---

🚀 Running the Prototype

Option 1 — Browser

Download/clone the repository and open:

index.html

Option 2 — VS Code

Open the project folder in VS Code and run "index.html" using Live Server.

No backend setup is required for the current prototype.

---

⚠️ Prototype Disclaimer

This repository contains a working front-end prototype.

Blockchain transactions, smart contracts, production authentication, encrypted storage, real GPS verification, AI anomaly detection, notifications, and backend APIs are represented as prototype concepts/simulations rather than a complete production deployment.

---

🌍 Vision

CivicProof aims to create a civic accountability layer where:

Every report has an identity.
Every action leaves a trail.
Every resolution requires proof.
Every citizen gets a voice.

Report it. Track it. Verify it.

«Don't just mark it resolved. Prove it.»

---

VIBETHON · CIV-2026

CivicProof — Proof before “resolved.”
