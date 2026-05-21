# AccessGuard – Identity & Access Management Dashboard

A lightweight, browser-based **Identity & Access Management (IAM)** demo dashboard built with vanilla HTML, CSS, and JavaScript.

Designed to illustrate core IAM workflows relevant to modern enterprise access control — including access request lifecycle management, periodic access reviews, audit logging, and compliance monitoring.

> Live demo: [GitHub Pages](https://yourusername.github.io/access-management-dashboard/)

---

## Features

| Module | Description |
|---|---|
| **Dashboard** | Real-time overview of pending requests, active users, overdue reviews, and compliance score |
| **Access Requests** | Full request lifecycle — submit, approve, reject with filterable status views |
| **User Accounts** | Directory of active/revoked accounts with searchable table |
| **Access Review** | Periodic certification queue (Q2 cycle) with progress tracking and certify actions |
| **Audit Log** | Immutable timestamped event log for all access changes, filterable by event type |
| **Compliance** | Policy adherence scorecard covering MFA, SoD, orphaned accounts, and more |

---

## Concepts Demonstrated

- **Least Privilege** – access requests require business justification and admin approval
- **Segregation of Duties (SoD)** – role separation tracked in the compliance view
- **Periodic Access Reviews** – certification cycles with overdue flagging
- **Access Revocation** – manual and automated revocation with full audit trail
- **Non-repudiation** – every action is logged with actor, timestamp, and method
- **Orphaned Account Detection** – inactive accounts surfaced for remediation

These principles align with ISO 27001, SOC 2, and common enterprise IAM frameworks.

---

## Tech Stack

- Pure HTML5 / CSS3 / JavaScript (ES6+) — zero dependencies, zero build step
- Runs entirely in the browser; no backend required
- All state is in-memory (suitable for demo/portfolio use)

---

## Getting Started

```bash
git clone https://github.com/yourusername/access-management-dashboard.git
cd access-management-dashboard
open index.html
```

Or deploy to GitHub Pages:

1. Push to a public repository
2. Go to **Settings → Pages → Source: main branch / root**
3. Your dashboard will be live at `https://yourusername.github.io/access-management-dashboard/`

---

## Project Structure

```
access-management-dashboard/
└── index.html          # Single-file application (HTML + CSS + JS)
└── README.md           # This file
```

---

## Use Case Context

This project was built as a portfolio piece for an **IT Access Management Specialist** role, demonstrating familiarity with:

- Access control lifecycle (provisioning → review → revocation)
- Audit-readiness and compliance reporting
- User-friendly tooling for IAM operations
- ServiceNow-style request management workflows

---

## Roadmap / Possible Extensions

- [ ] REST API backend (Node.js / Express) with persistent storage
- [ ] ServiceNow API integration for ticket synchronisation
- [ ] Active Directory / LDAP query simulation
- [ ] Export audit log to CSV for audit packages
- [ ] Role-Based Access Control (RBAC) rule engine
- [ ] Email notifications for pending approvals

---

## License

MIT — free to use, modify, and adapt.
