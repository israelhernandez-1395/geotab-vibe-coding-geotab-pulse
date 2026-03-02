# ⚡ Geotab Pulse: Real-Time DSD Control Tower

**Geotab Pulse** is a high-impact logistics dashboard designed for **Direct Store Delivery (DSD) and Last-Mile operations**. 

The core problem it solves is the "visibility gap" during retail distribution. While vehicles are tracked, fleet managers often lack real-time alerts when a truck exceeds its allowed dwell time at a customer location (tienditas) or a warehouse. This results in route bottlenecks, increased costs, and disrupted service levels.

# 🤖 The Vibe Coding Journey

This project was developed through a **"Vibe Coding"** methodology—a collaborative dialogue between human strategic intent and AI technical execution.

* **The Vision:** I envisioned a "Pulse" monitor that could transform raw Geotab telemetry into actionable logistics insights.
* **The Process:** Using **Gemini**, I rapidly prototyped the dashboard's logic, shifting from a hardcoded interface to a dynamic system integrated with the Geotab SDK.
* **The Iteration:** We overcame technical challenges, such as handling asynchronous API calls for `ZoneVisits` and implementing adjustable time thresholds, all within a record-breaking development window.

# 🌟 Key Features

* **Live Stay Monitoring:** A clean, dark-mode interface that identifies active vehicle stays in retail geofences.
* **Adjustable Time Thresholds:** A user-controlled slider that allows managers to define what constitutes a "delay" (e.g., 15, 30, or 60 minutes) on the fly.
* **Critical Delay Alerts:** Visual cues that highlight "Red Zones" when a vehicle exceeds 1.5x its allowed time.
* **Strategic Historical Reporting:** A one-click CSV export feature that allows management to audit bottlenecks and optimize future routes.

# 🛠️ Project Components

* **[Geotab Pulse Add-in JSON](./config.json):** The final, AI-optimized configuration ready to be deployed in MyGeotab.
* **[The Vibe Coding Prompt](./vibe_coding_prompt.md):** A detailed log of the prompts and the iterative process used with Gemini to build this solution.
---
*Developed for the Geotab Hackathon | Focus: Retail Distribution & Route Efficiency*
