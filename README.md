# Thailand-Flood-Monitor
# 🌊 Thailand Flood Monitoring System (TH-Water 2025)

![Project Status](https://img.shields.io/badge/Status-Prototype-orange)
![License](https://img.shields.io/badge/License-MIT-blue)
![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS%20%7C%20Leaflet-green)

[English](#english-description) | [ภาษาไทย](#thai-description)

---

<a name="english-description"></a>
## 🇬🇧 English Description

**Thailand Flood Monitoring System** is a responsive web-based dashboard designed to simulate flood situation monitoring, emergency response, and shelter management. The system operates based on real hydrological data scenarios from the **Royal Irrigation Department's report (December 1, 2025)**.

This project demonstrates the use of frontend technologies to visualize geospatial data, manage emergency requests (SOS), and provide actionable insights for both citizens and government officials.

### ✨ Key Features

* **Role-Based Access:**
    * **Citizen:** Can view flood status, locate nearest shelters, and send SOS distress signals with specific categories (Elderly, Children, Injured, etc.).
    * **Government Official:** Can monitor risk levels, view victim locations, and deploy drone scans to find stranded people.
* **Interactive Maps (Leaflet.js):**
    * **Flood Situation:** Visualizes risk zones (Critical, High, Medium, Low) using color-coded circles based on real data (e.g., Bang Rakam, Phak Hai).
    * **Victims:** Real-time marker clustering for SOS signals.
    * **Shelters:** Locations of safe zones (Temples, Schools, Government buildings).
* **Smart Routing:** Integrated **OSRM (Open Source Routing Machine)** to calculate routes and distance from a user's location to the nearest shelter.
* **Data & Reporting:**
    * Dynamic sidebar showing detailed area statistics (Rainfall, Water Level, Overflow status).
    * **PDF Export:** Generate situation reports instantly using `jsPDF`.
* **Simulation Features:**
    * **Drone Scan Animation:** Simulates searching for victims in critical areas.
    * **Real-time Clock:** Displays current local time.

### 🛠 Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Responsive Design), JavaScript (ES6+)
* **Mapping API:** [Leaflet.js](https://leafletjs.com/)
* **Routing Engine:** [Leaflet Routing Machine](https://www.liedman.net/leaflet-routing-machine/)
* **Icons:** [FontAwesome 6](https://fontawesome.com/)
* **PDF Generation:** [jsPDF](https://github.com/parallax/jsPDF)


### 📊 Data Reference
The simulation data uses specific metrics from the **Royal Irrigation Department Report (01 Dec 2025)**:
* **Critical Zones:** Bang Rakam (Phitsanulok), Phak Hai (Ayutthaya).
* **Metrics:** Water levels referencing real station codes (e.g., Y.64, C.67) and overflowing heights.

### 🚀 How to Run

1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/thailand-flood-monitor.git](https://github.com/your-username/thailand-flood-monitor.git)
    ```
2.  Navigate to the project folder.
3.  Open `index.html` in any modern web browser (Chrome, Firefox, Edge).
    * *Note: No backend server installation is required.*

