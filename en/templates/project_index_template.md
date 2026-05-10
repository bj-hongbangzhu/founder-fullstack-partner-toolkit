# Project Index

> Automatically maintained by the main controller, recording basic information of all projects. Do not edit manually.

---

## Project List

| Project Name | Creation Date | Last Updated | Current Stage | Status | Project Path |
|---------|---------|---------|---------|------|---------|
| [项目名称] | [YYYY-MM-DD] | [YYYY-MM-DD] | [阶段名] | In Progress/Paused/Delivered | ./[项目名称]/ |

---

## Status Description

| Status | Description |
|-----|------|
| **In Progress** | Project is progressing normally |
| **Paused** | Founder actively paused, waiting to resume |
| **Delivered** | Project documentation fully delivered, ready for development phase |
| **Terminated** | Project has been terminated |

---

## Stage Description

| Stage | Description | Corresponding Sub-skill |
|-----|------|----------|
| **Profile Listening** | Initial idea collection and project foundation | Main Controller |
| **Market Analysis** | Comprehensive detection and feasibility assessment | Sub-skill A |
| **Business Planning** | Business engine and fundraising planning | Sub-skill A |
| **Blueprint Co-creation** | Product blueprint design | Sub-skill B |
| **UI Planning** | UI design planning | Sub-skill B |
| **Tech Stack Selection** | Tech stack and architecture determination | Sub-skill C |
| **Microservice Split** | Microservice decomposition and open source evaluation | Sub-skill C |
| **Final Delivery** | Layered PRD and development specification delivery | Sub-skill C |

---

## Usage Instructions

### Main Controller Maintenance Rules
1. **When creating project**: Add a new row
2. **When updating project**: Update "Last Updated" and "Current Stage"
3. **When pausing project**: Update status to "Paused"
4. **When delivering project**: Update status to "Delivered"
5. **When terminating project**: Update status to "Terminated"

### Cross-session Recovery
1. When a new session starts, main controller reads this file
2. Display all "In Progress" and "Paused" projects
3. After founder selects, read the corresponding checkpoint recovery file

---

## Update Log

| Date | Operation | Project Name | Description |
|-----|------|---------|------|
| [日期] | Create/Update/Pause/Deliver | [项目名] | [说明] |
