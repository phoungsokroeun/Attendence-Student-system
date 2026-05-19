# 🎓 Attendance Management System (AMS Portal)

A modern, lightweight, and fully responsive **Single-Page Application (SPA)** designed for tracking student attendance, managing schedules, and auditing compliance metrics. Built entirely with vanilla frontend technologies, this portal replicates a sleek corporate dashboard system with integrated hardware terminal emulation.

---

## 🚀 Features

### 1. Executive System Dashboard
* **Real-Time Analytics:** Tracks total roster enrollment, present submissions, late flags, and unexcused absences.
* **Chronological Analytics Flow:** Features a dynamic, CSS-driven column chart monitoring compliance rates over historic sessions.
* **Actionable Insights:** Lists high-risk student clusters whose attendance yields fall below critical operational thresholds (< 85%).
* **Active Timetable Runtimes:** Automatically surfaces localized class agendas and room allocations scheduled for the current calendar date.

### 2. Check-In Gateway Terminal
* **Peripheral Pipeline Emulation:** Simulate physical hardware tracking via **Contactless RFID Reader**, **Optic QR Scanner Matrix**, or **Overriding Admin Panels**.
* **Grace Cutoff Enforcement:** Automatically flags check-ins as `late` if the injection timestamp breaches configured session thresholds.
* **Live Telemetry Stream:** A reactive data log updating live check-in packet frames inside the selected class framework.

### 3. Management Core Registries
* **Student Registry Database:** Add, review, or purge student identities mapping to active program configurations. Includes structural metrics calculations per student.
* **Course Catalog:** Centralizes curriculum blueprint maps including module identification codes, titles, track routes, and assigned faculty components.
* **Class Session Frames:** Organizes historical and active temporal grids allocation tables (date, timeline windows, and physical hub locations).

### 4. Analytical Compliance Framework Reports
* **Curriculum Auditing:** Aggregates deep-dive calculations (On-Time Logs, Late Strikes, Absents) filtered by individual course contexts.
* **Status Action Code:** Automatically evaluates whether a student's metrics meet programmatic compliance constraints (`COMPLIANT PASS` vs `RISK PROBATION`).

---

## 🎨 Design & Theme Principles
The interface implements modern design mechanics tailored for clean data presentation:
* **Color Palette:** Tailored deep indigo base (`#3730a3`) complemented by reactive state indicators (Teal, Green, Amber, and Crimson).
* **Typography:** Clean font layout configurations using standard weights of `DM Sans` alongside `DM Mono` for strict tracking numbers.
* **Responsive Architecture:** Full viewport stabilization for both high-resolution workstations and handheld touchscreen resolutions using an overlay-backed slide out mobile drawer.

---

## 🛠️ Technology Stack
This project runs entirely on client-side compilation, removing heavy dependency overhead:
* **Markup:** HTML5
* **Styling:** CSS3 (incorporates CSS Variables, Flexbox, CSS Grid Layouts, and dynamic viewport viewports)
* **Logic:** Vanilla JavaScript (ES6+)

---

## ⚙️ Installation & Usage

Because the complete system is self-contained inside a **single unified codebase component**, deployment requires no compilation pipelines, compilers, or server nodes:

1. **Clone or Copy the Code:**
   Save the application source code as an `index.html` file on your machine.

2. **Launch locally:**
   Simply double-click the `index.html` file to run it directly inside any standard modern web browser (Chrome, Edge, Safari, Firefox), or serve it locally using extension tools like *Live Server* in VS Code.

3. **Reset System Seeds:**
   Click the **↺ Reset System Seeds** button located at the base of the sidebar to immediately purge modifications and flush standard mock demo data packages back into active memory arrays.
