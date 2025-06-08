# Thingworx-NPI-Dashboards
A collection of modular ThingWorx dashboards for real-time visualization of engineering, project, and document-level data. These dashboards are designed to integrate with PLM systems (e.g., Windchill) and support advanced filtering, dynamic charts, document analytics, and status tracking.

---

## 📊 Dashboards Included

### 1. Parts Failure Dashboard
- Visualizes part failure records by:
  - Product Category
  - Failure Mode
  - Region and City
- Includes:
  - Interactive pie charts
  - Export to Excel/CSV
  - Reset filters
  - Data drill-down with grid view

### 2. Project Status Dashboard (NPI Dashboard)
- Tracks project-level metrics like:
  - Project Types
  - Phases and Delays
  - Bottlenecks and Deliverables
- Features:
  - Phase-wise timelines
  - Chart-driven filtering
  - Tabular deliverables linked to selected phases

### 3. Incubation Dashboard
- Monitors document lifecycle and turnaround time (TAT)
- Key Features:
  - Document Status Breakdown (Approved, Locked, Rejected)
  - TAT chart generation
  - Filtering by Product Category and Project Type
  - Real-time interaction with backend REST services

---

## 🔧 Tech Stack

- **Platform:** PTC ThingWorx
- **Backend:** ThingWorx Services, REST API Integration
- **Frontend:** ThingWorx Mashups (Mashup Builder)
- **Data Sources:** PLM system (e.g., Windchill), internal DataTables/InfoTables

---

## 📁 Repository Contents

- `Mashups/` — ThingWorx mashup XMLs
- `Services/` — Thing Services for querying, filtering, and data formatting
- `Deployment/` — Deployment guide and environment prerequisites
- `Documentation/` — Functional test cases, technical logic, and unit testing notes

---

## 🚀 Deployment

1. Export entities from ThingWorx DEV
2. Import `Entities.xml` into the target environment (QA/PROD)
3. Run sanity tests using included test case documents
4. Commit changes to version control (if applicable)

Detailed instructions available in `Deployment Document.docx`

---

## 📄 Documentation Highlights

- `Dashboard Documentation - Functional & Technical.docx`  
  Describes service architecture, user flows, and feature-wise breakdown

- `Dashboards_Unit Testing.docx`  
  Unit testing checklist per dashboard feature and backend logic

- `*_Test Cases.xlsx`  
  End-user test scenarios for each dashboard (non-technical friendly format)

---

## 🛡️ Notes

- This project is built for internal deployment and PLM integration.
- Client-specific identifiers have been removed to comply with NDA.
- For production use, ensure secure REST authentication and proper access controls in ThingWorx.

---

## 🔖 Tags

`thingworx` `plm-dashboard` `windchill-integration` `iot-visualization` `project-tracking` `smart-manufacturing` `ptc` `mashup-development`
