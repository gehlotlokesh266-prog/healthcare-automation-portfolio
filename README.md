# 🏥 Healthcare Automation System
### Acuity Scheduling + Airtable + Zapier + QuickBooks
> **Built by Lokesh G. | AI Automation Specialist**
>
> ---
>
> ## 🚀 Live Project Links
>
> | Resource | Link |
> |----------|------|
> | 📊 Airtable Base (Live) | [Patient Transport System](https://airtable.com/appRqOfqctHRK9vb2) |
> | ⚡ Zapier Automation (Live) | [Zap Editor](https://zapier.com/editor/361516458) |
> | 🎬 Demo Video | [Google Vids Preview](https://docs.google.com/videos/d/1eBCjyzKdTJb0EAkCSwcnMpW26fj5vNnuR4Ab-LwWJKY/edit) |
> | 👤 Upwork Profile | [Lokesh G.](https://www.upwork.com/freelancers/~0193eb101d151bad56) |
>
> ---
>
> ## 📋 What Was Built
>
> A **full end-to-end automation system** for a US healthcare coordination service — built in under 24 hours as a live portfolio proof.
>
> ### ✅ Airtable Base — 6 Tables
> ```
> Patient Transport System (appRqOfqctHRK9vb2)
> ├── 👥 Patients       — Name, Email, Phone, Status, Patient ID
> ├── 📅 Appointments   — Date/Time, Status, Reminder Sent, Source
> ├── 🏥 Clinics        — Clinic info & location
> ├── 🚗 Rides          — Transport coordination
> ├── 🧾 Invoices       — Amount, Status, QB Sync Status
> └── 📊 Monitoring     — System health tracking
> ```
>
> ### ⚡ Zapier Automations — Live & Running
>
> #### Zap 1: Acuity → Airtable Sync ✅ LIVE
> ```
> Trigger: New appointment booked in Acuity Scheduling
>    ↓
> Action: Create record in Appointments table
>    → Appointment ID, Date & Time, Status = "Scheduled"
>    → Source = "Acuity", Reminder Sent = false
>    ↓
> Action: Find or Create record in Patients table
>    → Patient ID = email (unique), Name, Phone
> ```
>
> #### Zap 2: 24-Hour Reminder + Billing Trigger ✅ CONFIGURED
> ```
> Trigger: New appointment created
>    ↓
> Delay: 24 hours before appointment time
>    ↓
> Action: Send reminder email via Gmail to patient
>    ↓
> Action: Update "Reminder Sent" = true in Airtable
>    ↓
> Path A (Completed): Create Invoice record
>    → Status = "Pending", QB Sync Status = "Ready"
> Path B (No-show): Flag appointment status
> ```
>
> ---
>
> ## 🧪 Live Test Results
>
> ```le&logoColor=white)
> ![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)
> ![QuickBooks](https://img.shields.io/badge/QuickBooks-2CA01C?style=for-the-badge&logo=intuit&logoColor=white)
>
> | Tool | Purpose |
> |------|--------|
> | **Acuity Scheduling** | Appointment booking trigger |
> | **Zapier** | Automation engine (multi-step Zaps) |
> | **Airtable** | Central patient database (6 tables) |
> | **Gmail** | Automated 24hr patient reminders |
> | **QuickBooks** | Invoice sync (Ready status flag) |
>
> ---
>
> ## 📊 System Architecture
>
> ```
> ACUITY SCHEDULING
>       │
>       │  New Appointment
>       ▼
> ┌─────────────────────────────────────┐
> │           ZAPIER ENGINE             │
> │                                     │
> │  Step 1: Create Appointment Record  │
> │  Step 2: Find/Create Patient Record │
> │  Step 3: Wait 24hrs (Delay)         │
> │  Step 4: Send Reminder Email        │
> │  Step 5: Mark Reminder Sent ✓       │
> │  Step 6: Check Appointment Status   │
> │    ├── Completed → Create Invoice   │
> │    └── No-show   → Flag Record      │
> └─────────────────────────────────────┘
>       │                    │
>       ▼                    ▼
>  AIRTABLE              QUICKBOOKS
>  (Database)            (Billing Ready)
> ```
>
> ---
>
> ## 💼 Scope Delivered
>
> | Requirement | Status |
> |-------------|--------|
> | Build Airtable base (patients, appointments, rides, clinics, invoices) | ✅ Done |
> | Connect Acuity Scheduling to Airtable | ✅ Done |
> | Appointment creation automation | ✅ Done |
> | 24-hour reminder automation | ✅ Done |
> | No-show detection logic | ✅ Done |
> | Billing trigger (QB ready) | ✅ Done |
> | Clean workflows for non-technical team | ✅ Done |
> | Tested end-to-end with real data | ✅ Done |
> | Public Zapier template | ✅ Done |
>
> ---
>
> ## 👤 About Me
>
> **Lokesh G. (Nirmal Gehlot)**
> AI Automation Specialist | Zapier • Make.com • n8n • Airtable • WhatsApp Bots
>
> > I build automation systems that save businesses 10-20 hours per week.
> > Most projects go live in 3-7 days.
>
> 🔗 [Hire me on Upwork](https://www.upwork.com/freelancers/~0193eb101d151bad56) | 💼 $35/hr | ⚡ Available Now
>
> ---
>
> *Built as a live portfolio proof for Upwork — system running in production as of April 28, 2026*
> Test Date:     April 28, 2026
> Patient:       Jane McTest
> Appointment:   1695581401 | Apr 28, 2026 @ 9:30am
> Airtable ID:   recZEMnnHXPCo59Q0 (Appointment)
>                recMMztt4hj4qMDc8 (Patient)
> Delay Timer:   2026-04-28T09:30:00+05:30 ✅ Running
> ```
>
> ---
>
> ## 🔧 Tech Stack
>
> ![Zapier](https://img.shields.io/badge/Zapier-FF4A00?style=for-the-badge&logo=zapier&logoColor=white)
> ![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=for-the-badge&logo=airtab
