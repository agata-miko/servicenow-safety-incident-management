# Project Plan – ServiceNow BHP Incident Management

## 1. Project Overview
A ServiceNow developer instance implementation for automating workplace incident reporting and management.  
The system streamlines incident assignment to Safety staff, escalates serious/fatal incidents, automatically closes and archives incidents not requiring reporting under Polish law, and generates reports and dashboards.

---

## 2. Objectives
- Simplify workplace incident reporting for managers and leaders
- Ensure fair and efficient assignment of incidents to Safety staff
- Automate escalation of serious and fatal incidents to company management
- Automatically close non-qualifying incidents
- Improve safety monitoring through dashboards and reports

---

## 3. Scope
This project will include:
1. **Custom table** for incident records  
2. **Custom form** for managers to submit incidents  
3. **Flow Designer flows** for:
   - Incident assignment
   - Escalation of serious/fatal cases
   - Automatic closure of non-qualifying incidents
   - Email notifications
4. **Reports & dashboards**
5. **Test cases** for key workflows

---

## 4. Deliverables
| Deliverable | Description |
|-------------|-------------|
| **Custom Table** | Table to store incident data with all necessary fields |
| **Manager Form** | Form for incident submission |
| **Flow Designer Flows** | Automated workflows for assignment, escalation, and closure |
| **Email Templates** | Notification messages for relevant stakeholders |
| **Reports** | Incident summary and compliance metrics |
| **Dashboards** | Visual overview for management and Safety team |

---

## 5. Workflow Diagram

[Workflow Diagram](WORKFLOW.md)


---

## 6. Milestones & Checklist
- [x] **Setup**
  - [x] Create developer instance
  - [x] Create GitHub repository
  - [x] Add README.md and PLAN.md
- [ ] **Data Model**
  - [ ] Create `x_bhp_incident` table
  - [ ] Define required fields (date, description, location, severity, “Qualifies as workplace accident?”)
- [ ] **Form Design**
  - [ ] Create incident submission form
  - [ ] Add validation rules
- [ ] **Automation**
  - [ ] Flow for smart assignment to Safety staff with fewest open cases
  - [ ] Escalation flow for serious/fatal incidents
  - [ ] Automatic closure for non-qualifying incidents
  - [ ] Email notification templates
- [ ] **Reports & Dashboards**
  - [ ] Create incident summary report
  - [ ] Create compliance dashboard
- [ ] **Testing**
  - [ ] Prepare test cases
  - [ ] Run tests in developer instance
  - [ ] Document results
- [ ] **Finalization**
  - [ ] Clean up test data
  - [ ] Export update set
  - [ ] Update documentation

---

## 7. Tools & Resources
- ServiceNow Developer Instance
- Flow Designer
- ServiceNow Studio
- GitHub for version control
- Draw.io / Mermaid for diagrams

---

## 8. Notes
This is a proof-of-concept project designed for learning purposes, but it follows real-world business logic that can be applied in production environments.
