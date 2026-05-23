# Organza
### Under Construction... <3

> **Integrated Freelancer Workspace & Client Marketplace**

Organza is a web-based unified workspace for independent creative professionals and the clients who hire them. It consolidates the fragmented toolset that freelancers currently maintain — project trackers, invoice tools, contract builders, messaging apps — into a single coherent platform.

---

## The Problem

A typical freelancer juggles 6–10 separate tools: Figma, WhatsApp, Gmail, Google Drive, Wave, Notion, Calendly, and more. Clients are no better off — hiring a designer means searching on Instagram, vetting on LinkedIn, negotiating on WhatsApp, signing PDFs via email, and paying via bank transfer. Across five different apps.

Organza's core hypothesis: **if both the freelancer and their client live on the same platform, the friction of every transaction — brief to contract to delivery to invoice to payment — collapses to near zero.**

---

## What It Does

### For Freelancers
- **Project Tracker** — manage multiple concurrent clients and projects
- **Task Management** — break projects into tasks with deadlines
- **Time Logger** — log hours per project, no spreadsheet needed
- **Invoice Builder** — generate and send professional invoices
- **Contract Generator** — create legally-structured contracts in minutes
- **Proposal Builder** — send polished proposals that win trust
- **Integrations** — Figma, Adobe Creative Cloud, CapCut
- **Organza Messenger** — first-party messaging, replacing WhatsApp/email for project comms
- **Community** — peer discovery, community boards, referrals

### For Clients
- **Freelancer Marketplace** — discover and evaluate creatives
- **Project Brief** — submit a structured brief directly on platform
- **Contract Viewer** — review and acknowledge contracts
- **Invoice Receiver** — receive and track invoices in one place
- **Review System** — leave verified reviews after project completion

---

## Vision

> To become the life force of the independent creative economy — the single place where freelancers connect, create, showcase, and get paid.

---

## Target Users

| Persona | Description |
|---|---|
| **Samantha** | Independent graphic designer / brand strategist, 2–5 years experience, 3–8 concurrent clients. Wants to minimise admin and get paid faster. |
| **Shyamali** | Founder of a small bakery. Needs brand identity and social media creatives. Non-technical. Wants to find the right creative and keep everything in one place. |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML / CSS / JavaScript (v1 static) |
| Backend | Django (Python) |
| Database | PostgreSQL |
| Auth | Django Allauth |
| Hosting | GitHub Pages (frontend) · Railway / Render (backend) |
| Integrations | Figma API · Adobe Creative Cloud API · WhatsApp Business API (outbound notifications) |

> Stack is subject to change as the SRS is finalised.

---

## Out of Scope (v1)

- In-platform payment gateway (v2 item)
- Real-time video conferencing
- Mobile native apps (iOS / Android) — web-responsive only
- Multi-freelancer team billing and sub-contracting

---

## Course Details

| Field | Detail |
|---|---|
| Subject | CS401 Software Engineering |
| Instructor | Prof. Trupti Gondoliya |
| Prepared by | Apekshaa Yadav |
| Registration ID | UI24CS84 |
| Document Version | 1.0 — IEEE Std 830-1998 |

---

## Getting Started (Local)

> Instructions will be updated once the Django backend scaffold is ready.

```bash
# Clone the repo
git clone https://github.com/apekshaayy/organza.git
cd organza

# Create virtual environment
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the dev server
python manage.py runserver
```

Then open `http://127.0.0.1:8000` in your browser.

---

## License

This project is for academic purposes under CS401 Software Engineering, IIIT Surat.
