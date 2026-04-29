# 🚨emergency_ward_dashboard_Cycle3

A modern, interactive **Emergency Department (ED) Operations Dashboard** designed to monitor patient flow, staffing, and critical hospital metrics in real time.
Built using vanilla HTML, CSS, JavaScript, and Chart.js — no frameworks or build tools required.

---


## ✨ Features

### 🖥️ Multi-Screen Dashboard
- **📊 Overview** — Key KPIs and performance snapshot
- **🏃 Patient Flow** — Track arrivals, triage, and treatment stages
- **👩‍⚕️ Staffing & Beds** — Resource availability and allocation
- **🚨 Incident Command** — Emergency handling insights

### ⚡ Real-Time Interaction
- 🔍 Filter by:
  - Zone
  - Acuity level
  - Arrival mode
- 🔎 Instant search functionality
- 🔄 Dynamic updates across all panels

### 🧠 Smart Metrics
Automatically calculated:
- ⏱️ Patient turnaround time
- 🚪 Door-to-triage time
- 👨‍⚕️ Door-to-clinician time
- 🛏️ Bed turnaround time
- ⚠️ Breach rates

### 📤 Data Export
- Export filtered data as **CSV** for reporting and analysis

### 📱 Responsive Design
- Optimized for desktop, tablet, and mobile devices

---

## 🚀 Quick Start

### Option 1: Run Locally
1. Download or clone the repository
2. Open `index.html` in your browser

### Option 2: Deploy on GitHub Pages
1. Push the project to GitHub
2. Go to **Settings → Pages**
3. Select the `main` branch
4. Access your live dashboard 🎉

---

## 📁 Project Structure

```
emergency-ward-dashboard/
│
├── index.html      # 🏠 Main dashboard UI
├── styles.css      # 🎨 Styling and layout
├── app.js          # ⚙️ Core logic and data handling
└── README.md       # 📖 Documentation
```

---

## 🛠️ Customization

You can adapt the dashboard to your own dataset:
1. Open `app.js`
2. Modify the `demoData` object
3. Use ISO date format

---

## 🧮 Key Formulas Used

| Metric | Formula |
|---|---|
| ⏱️ Patient Turnaround Time | `departureAt − arrivalAt` |
| 🚪 Door to Triage Time | `triageAt − arrivalAt` |
| 👨‍⚕️ Door to Clinician Time | `clinicianAt − arrivalAt` |
| 🛏️ Bed Turnaround Time | `readyAt − vacatedAt` |

---

## 💻 Tech Stack

| Technology | Purpose |
|---|---|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Structure |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Logic |
| ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white) | Data Visualization |

---

## 🏥 Use Cases

- 🏨 Hospital emergency departments
- 📈 Healthcare analytics demonstrations
- 🎓 Academic projects
- 📊 Operational dashboards

---

## 📄 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute it. 🤝
