# Awesome-Project-Planning-Work-Breakdown

# Awesome Project Planning & Work Breakdown

> A curated list of top Project Planning and Work Breakdown platforms — both SaaS/Hosted commercial solutions and open-source alternatives for decomposing projects into tasks, estimating effort, and scheduling work.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Microsoft Project](#microsoft-project)
  - [Smartsheet](#smartsheet)
  - [Wrike](#wrike)
  - [GanttPRO](#ganttpro)
  - [TeamGantt](#teamgantt)
  - [LiquidPlanner](#liquidplanner)
- [Open-Source Software](#-open-source-software)
  - [LibrePlan](#libreplan)
  - [Leantime](#leantime)
  - [GanttProject](#ganttproject)
  - [OpenProject](#openproject)
  - [ProjectLibre](#projectlibre)
  - [Gnome Planner](#gnome-planner)
  - [Kanboard](#kanboard)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Project Planning and Work Breakdown platforms. These are not open-source but are included as reference points for feature comparison.

### Microsoft Project
**Type:** Enterprise project scheduling with WBS and resource management
Microsoft Project is the long-standing enterprise standard for project planning, with work breakdown structure (WBS) support, Gantt charts, resource allocation, and critical path analysis. It integrates with the broader Microsoft ecosystem and is available as both desktop and cloud (Project for the web) offerings. Pricing is per-user with tiered plans.

### Smartsheet
**Type:** Spreadsheet-based work management with Gantt and WBS
Smartsheet provides a spreadsheet-like interface for project planning with Gantt views, dependencies, and resource management. It is positioned for teams wanting familiar grid-based planning with project management capabilities layered on top. Pricing is per-user with tiered plans.

### Wrike
**Type:** Work management with Gantt and resource planning
Wrike provides project planning with Gantt charts, WBS-style task hierarchies, resource management, and workload views. It is positioned for mid-market to enterprise teams wanting a comprehensive work management platform. Pricing is per-user with tiered plans.

### GanttPRO
**Type:** Gantt-centric project planning
GanttPRO focuses on Gantt chart-based project planning with task dependencies, milestones, and resource management. It is positioned for teams wanting a dedicated Gantt tool rather than a full work management platform.

### TeamGantt
**Type:** Collaborative Gantt planning
TeamGantt provides collaborative Gantt chart planning with drag-and-drop scheduling, dependencies, and team collaboration. It is positioned for teams wanting straightforward Gantt-based project planning with a gentle learning curve.

### LiquidPlanner
**Type:** Predictive project scheduling with priority-based planning
LiquidPlanner uses predictive scheduling to automatically adjust project timelines based on priority, effort estimates, and resource availability. It is positioned for teams wanting dynamic, data-driven scheduling rather than static Gantt charts.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Project Planning and Work Breakdown tools. The open-source ecosystem spans **full project management suites**, **desktop Gantt applications**, **WBS-focused tools**, and **Kanban boards**.

### LibrePlan
**Stack:** Java / PostgreSQL | **License:** AGPL-3.0
LibrePlan is an open-source web-based project management platform designed for project planning, resource allocation, governance, and collaboration, with a specific focus on **Work Breakdown Structure (WBS)** . Key features include:
- **WBS management**: add tasks to a project in a Work Breakdown Structure, store tasks in containers and subcontainers, add requirements to tasks, and assign resources manually or automatically based on criteria 
- **Resource allocation**: assign materials to tasks with expected delivery dates, manage calendars and worker holidays, and see resource utilization and workload 
- **Project governance**: manage issues and risks, track progress, enter time spent via timesheets, and see budget vs. actual spend 
- **Reporting**: generate reports for project status, use templates for repetitive projects, and handle subcontracting workflows 
- **Integration**: schedule synchronization with JIRA or Tim using connectors, with email notifications via job scheduler 

LibrePlan has been used internationally since 2009 and is available under AGPL, making it suitable for public administrations, municipalities, educational institutions, and NGOs seeking self-hosted project governance without proprietary SaaS dependency [citation:3]. Version 1.6.1 is available via Docker [citation:1].  
**Best for:** Public sector organizations and project-driven teams wanting a proven, self-hosted platform with WBS-based planning, resource allocation, and project governance.

### Leantime
**Stack:** PHP / MySQL | **License:** AGPL-3.0
Leantime is an open-source project management system designed for non-project managers, with a focus on cognitive accessibility (ADHD, autism, dyslexia) . Key features include:
- **Task management** via Kanban boards, Gantt view, table, list, and calendar views 
- **Unlimited subtasks and dependencies**, milestone management, and sprint management 
- **Goal & metrics tracking**, project dashboards, and reports 
- **Time tracking and timesheets**, with iCal integration for external calendars 
- **Wikis/Docs, idea boards, retrospectives, SWOT analysis, and risk analysis** 
- **Integrations** with Slack, Mattermost, Discord, LDAP, and OIDC 

It is positioned as "as simple as Trello but as feature-rich as Jira" and is a direct alternative to ClickUp, Monday, or Asana . All features listed are included in the OSS version [citation:9].  
**Best for:** Teams wanting a feature-rich open-source project management platform with strong accessibility design and no per-user licensing for self-hosted use.

### GanttProject
**Stack:** Java | **License:** GPL-3.0
GanttProject is a free desktop project management app with a focus on Gantt-based scheduling . Key features include:
- **Task hierarchy and dependencies**, milestones, and baselines 
- **Gantt chart** with an option to generate PERT chart 
- **Resource load chart** and task cost calculation 
- **Export** to PDF, HTML, and PNG, with interoperability with MS Project and Excel 
- **Collaboration** via WebDAV and a commercial collaboration service (GanttProject Cloud) 

It is a desktop application rather than a web platform, with builds for Windows, macOS, and Linux [citation:5].  
**Best for:** Individual project managers and small teams wanting a free, desktop-based Gantt tool with MS Project compatibility.

### OpenProject
**Stack:** Ruby on Rails / PostgreSQL | **License:** GPL-3.0 (Community)
OpenProject is a mature open-source project management suite with work package hierarchies, Gantt charts, and scheduling modes. The platform supports **automatic and manual scheduling** per work package, with parent-child date propagation and duration bars on Gantt charts . It includes subproject boards, subtask boards (Parent-Child board), and time/cost tracking modules . The Community edition is GPL-3.0, with Enterprise add-ons available.  
**Best for:** Organizations wanting a comprehensive open-source project management suite with strong work package hierarchy and Gantt scheduling.

### ProjectLibre
**Stack:** Java | **License:** GPL-3.0
ProjectLibre is a free, open-source desktop project management tool positioned as a direct replacement for Microsoft Project. It supports Gantt charts, WBS, resource allocation, and critical path analysis, with compatibility for opening MS Project files. It is available for Windows, macOS, and Linux.

### Gnome Planner
**Stack:** C / GTK | **License:** GPL-3.0
Gnome Planner is a cross-platform project management tool based on the **Work Breakdown Structure (WBS)**, allowing users to visualize projects in time using Gantt charts, list the complete breakdown of a project with estimated cost and effort, and manage resource assignments [citation:4]. It is a desktop application with a GTK interface.

### Kanboard
**Stack:** PHP / SQLite | **License:** MIT
Kanboard is a free, open-source project management tool focused on the **Kanban methodology** . Features include visualizing work, limiting work in progress, customizing boards, multiple projects with drag-and-drop tasks, reports and analytics, and plugins/integrations with external services . It is self-hosted with a simple installation and a CLI client available via Debian packages [citation:7]. While not WBS-focused, it supports task breakdown and workflow visualization.

---

## 📊 Comparison at a Glance

| Software | License | Stack | WBS Support | Gantt | Resource Mgmt | Self-Hosted | Best For |
|----------|---------|-------|-------------|-------|---------------|-------------|----------|
| **Microsoft Project** | Proprietary | Cloud/Desktop | ✅ | ✅ | ✅ | ❌ | Enterprise scheduling |
| **Smartsheet** | Proprietary | Cloud | (Grid-based) | ✅ | ✅ | ❌ | Spreadsheet-style planning |
| **LibrePlan** | AGPL-3.0 | Java/Postgres | ✅ Deep WBS | ✅ | ✅ | ✅ | WBS + governance |
| **Leantime** | AGPL-3.0 | PHP/MySQL | (Subtasks) | ✅ | (Time tracking) | ✅ | Accessible PM + Gantt |
| **GanttProject** | GPL-3.0 | Java | (Task hierarchy) | ✅ | ✅ | ✅ (Desktop) | Desktop Gantt + MS Project |
| **OpenProject** | GPL-3.0 | Ruby/Postgres | (Work packages) | ✅ | ✅ | ✅ | Full PM suite |
| **ProjectLibre** | GPL-3.0 | Java | ✅ | ✅ | ✅ | ✅ (Desktop) | MS Project replacement |
| **Gnome Planner** | GPL-3.0 | C/GTK | ✅ WBS-focused | ✅ | ✅ | ✅ (Desktop) | WBS + cost/effort |
| **Kanboard** | MIT | PHP/SQLite | (Task breakdown) | ❌ | ❌ | ✅ | Kanban workflow |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Project Planning or Work Breakdown tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between **full web-based project management suites** (LibrePlan, Leantime, OpenProject), **desktop Gantt tools** (GanttProject, ProjectLibre, Gnome Planner), and **Kanban-focused boards** (Kanboard). **LibrePlan** is the most WBS-centric open-source option with deep task decomposition, resource allocation, and governance features . **Leantime** offers the most feature-dense self-hosted alternative to ClickUp or Monday with strong accessibility design . For desktop users wanting MS Project compatibility, **GanttProject** and **ProjectLibre** are the strongest free options .

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
