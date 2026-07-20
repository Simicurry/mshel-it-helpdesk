# Mshel Homes — IT Helpdesk System

A lightweight, browser-based IT Helpdesk and Asset Management tool built as a proposed internal solution for **Mshel Homes Limited**, a real estate company in Abuja, Nigeria.

## 🎯 Purpose

This tool addresses a core responsibility of an IT Support Officer:
- Logging and tracking IT support tickets from staff
- Managing IT equipment inventory
- Monitoring issue status and priority
- Providing visibility into the IT support workload

## ✨ Features

### 🎫 Ticket Management
- Log new IT issues with staff name, department, category, and priority
- Track tickets through: **Open → In Progress → Resolved → Closed**
- Filter tickets by status, priority, or category
- View full ticket details and update status in a modal

### 🖥️ Asset Inventory
- Register IT equipment (laptops, printers, routers, CCTV, biometrics, etc.)
- Track asset assignment, department, and condition
- Auto-generate asset tags (e.g. `MH-LT-001`)
- Mark assets as Good, Needs Repair, or Retired

### 📊 Dashboard Stats
- Live count of Open, In Progress, and Resolved tickets
- Total IT assets count

## 🚀 How to Run

No installation required. This is a pure HTML/CSS/JS application.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/mshel-it-helpdesk.git
   ```

2. Open `index.html` in any modern browser.

That's it — no server, no dependencies, no build step.

> Data is stored in **localStorage** so it persists across browser sessions on the same device.

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Storage | Browser localStorage |
| Dependencies | None |

## 📁 File Structure

```
mshel-it-helpdesk/
└── index.html      # Complete single-file application
└── README.md       # This file
```

## 🔮 Potential Enhancements (Future)

- Backend integration (Node.js + MySQL or Firebase)
- Email notifications when tickets are assigned or resolved
- Microsoft 365 / Active Directory integration
- Role-based access (Admin vs. Staff view)
- PDF report generation
- Mobile app version

## 👤 Author

Built by **[Your Name]** as a practical IT support solution proposal for Mshel Homes Limited.

---

> *"This tool was designed to solve real operational challenges in a real estate IT environment — reducing response time, improving asset visibility, and ensuring no staff issue goes untracked."*
