# Smart Design AutoHub
### Dealership Management System — Production Blueprint V1.1

> **Driving Your Business Forward**

---

## Overview

Smart Design AutoHub is a complete dealership management platform built for used vehicle dealerships, new vehicle dealerships, and multi-branch automotive operations. It provides full operational visibility across inventory, sales, profitability, CRM, leads, staff performance, and reporting — all in one elegant system.

---

## Live Demo

Deploy instantly to Vercel — see deployment instructions below.

---

## Features

### Dashboard
- Real-time KPIs: Total Vehicles, Available, Sold, Reserved, In Workshop
- Financial summary: Stock Value, Retail Value, Potential Gross Profit, Monthly Revenue & Profit
- Revenue vs Profit bar chart (6-month trend)
- Lead pipeline overview
- Staff performance summary
- Quick action shortcuts

### Vehicle Inventory
- Full vehicle profiles (Make, Model, Variant, Year, Mileage, Colour, Fuel, Transmission, VIN, Registration)
- Grid and list view toggle
- Filter by status: Available / Reserved / Sold / In Workshop
- Status badges with colour coding
- Days-in-stock tracking with ageing alerts
- Add, Edit, Archive vehicles

### Vehicle Purchase Module
- Capture seller details and all purchase costs
- Automatic calculation: Purchase Price + Repairs + Transport + Licensing + Preparation = **Actual Vehicle Cost**
- Projected Gross Profit displayed live as you type
- Purchase history table

### Vehicle Sales Module
- Select vehicle, auto-loads investment cost
- Capture buyer, sale price, deposit, finance institution, salesperson
- Live calculations: Gross Profit, Profit Margin, Commission
- Vehicle status auto-updates to SOLD on recording

### Executive Profit Dashboard
- Total inventory investment vs retail value
- Potential profit on current stock
- Monthly and annualised profit estimates
- Top salesperson, most profitable vehicle, fastest and slowest selling
- Staff profit contribution leaderboard with progress bars

### Lead Management
- Lead sources: Walk-In, Website, Facebook, WhatsApp, Referral, AutoTrader, cars.co.za
- Pipeline stages: New → Contacted → Test Drive Scheduled → Negotiating → Finance Approved → Sold / Lost
- Assign leads to salespersons
- Update lead status inline
- Full lead history

### Sales Performance
- Individual salesperson cards: Active Leads, Closed Deals, Monthly Sales Value, Gross Profit, Conversion Rate, Commission Earned
- Leaderboard ranking with progress bars

### Customer Management (CRM)
- Full customer profiles: Name, Phone, Email, Address, Vehicle Interests, Notes
- Searchable customer database
- Add and edit customers

### Vehicle Preparation Tracker
- Six-step checklist per vehicle: Mechanical Inspection, Valet, Licensing, Roadworthy, Photography, Website Listing
- Live percentage completion per vehicle
- Toggle each step on/off

### Stock Ageing Module
- Automatic ageing categories: 0–30, 31–60, 61–90, 90+ Days
- Colour-coded alerts
- Action required flags for 90+ day stock

### Tasks & Follow-ups
- Task types: Customer Calls, Quotations, Test Drives, Finance Updates, Delivery Arrangements
- Priority levels: High, Medium, Low
- Overdue task highlighting
- Mark tasks complete

### Reports
- Report types: Inventory, Sales, Profit, Staff, Lead, Ageing
- Date range selection
- Export to PDF / Excel (wired for Supabase backend)
- Lead source analysis chart
- Audit log viewer

### Document Management
- Categories: Registration Documents, Purchase Agreements, Sales Agreements, Finance Documents, Customer Documents
- Upload and search functionality

### Settings
- Dealership information
- User management
- Access code generation (single-use / multi-use, expiry dates)
- Commission rate configuration per salesperson

---

## Technology Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5 / CSS3 / Vanilla JS (zero dependencies) |
| Production Frontend | Next.js |
| Backend | Supabase |
| Database | PostgreSQL |
| Authentication | Supabase Auth |
| Storage | Supabase Storage |
| Hosting | Vercel |
| Version Control | GitHub |

---

## Colour Theme

| Token | Colour | Hex |
|---|---|---|
| Primary | Midnight Black | `#0F172A` |
| Secondary | Steel Grey | `#475569` |
| Accent | Electric Blue | `#2563EB` |
| Success | Emerald Green | `#10B981` |
| Warning | Amber | `#F59E0B` |
| Sold | Luxury Gold | `#D4AF37` |
| Background | Clean White | `#F8FAFC` |

---

## User Roles

| Role | Access |
|---|---|
| Super Administrator | Full system — inventory, sales, users, reports, settings, financial data |
| Sales Manager | Inventory view, lead assignment, team management, reports |
| Sales Consultant | Assigned leads, lead status updates, test drive scheduling |

---

## Deployment

### Option 1 — Vercel (Recommended, one click)

1. Fork or upload this repository to GitHub
2. Go to [vercel.com](https://vercel.com) and click **New Project**
3. Import your GitHub repository
4. Vercel auto-detects the project — click **Deploy**
5. Done. Your app is live.

### Option 2 — Manual HTML

Open `autohub_master.html` directly in any browser. No server required for the demo version.

---

## Environment Variables (Production Supabase)

When connecting to a real Supabase backend, add these to your Vercel project settings:

```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

---

## Roadmap — Phase 2

- WhatsApp Integration
- AI Vehicle Pricing Engine
- Workshop Management Module
- Finance & Insurance (F&I) Module
- Multi-Branch Management
- Customer Mobile App
- Online Vehicle Reservations
- Digital Deal Jackets
- Vehicle Inspection App

---

## Security

- Role-Based Access Control (RBAC)
- Two-Factor Authentication (2FA) via Supabase Auth
- SSL encryption on all connections
- Complete audit logging (user, date, time, action, before/after values)
- No records permanently deleted without Super Administrator authorisation
- All historical activity preserved

---

## License

Private and Confidential — Smart Design AutoHub  
© 2024 Smart Design. All rights reserved.  
Unauthorised copying, distribution or reverse engineering is prohibited.

---

*Built with ❤️ for South African motor dealerships*
