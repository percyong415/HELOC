** <u>Objective:</u> **
Ensure the HELOC Live Tracker platform provides bankers with a clear, accurate, and user-friendly way to monitor application stages, pending tasks, and deadlines, reducing reliance on fragmented systems.

Scope:
- Application lifecycle visual tracking

- Applicant task management visibility

- Reminder/notification triggers

- User interaction and task triggering by banker

🛠️ Test Scenarios

| Test Case ID | Scenario | Steps | Expected Result | Pass/Fail |
|:---|:---|:---|:---|:---|
| TC-001 | Application Status Visibility | 1. Log into Live Tracker<br>2. Open active HELOC application | Banker sees the full lifecycle map with current stage clearly highlighted | |
| TC-002 | Pending Task Visibility | 1. Open an application where applicant has pending document upload<br>2. View \"Pending Tasks\" panel | Banker sees applicant's required documents and due dates | |
| TC-003 | Trigger Reminder to Applicant | 1. Click \"Send Reminder\" next to pending document<br>2. Confirm notification sent | System confirms reminder sent; applicant receives notification | |
| TC-004 | Processor Action Visibility | 1. Open application<br>2. View upcoming stage under Processor responsibility | Banker can view next stage tasks and responsible party | |
| TC-005 | Deadline Escalation | 1. Let applicant task expire past due date<br>2. Observe system escalation behavior | Banker receives an escalation alert; task is flagged overdue | |
| TC-006 | Cross-System Integration | 1. Update document in back-end processor system<br>2. Refresh Live Tracker view | Updated status correctly reflected in Live Tracker in real time | |

📋 Acceptance Criteria:
- 95% of UAT scenarios must pass without major defects

- No critical usability barriers found during pilot tests

- Reminder and escalation triggers must function correctly

- Bankers must complete common actions (view stage, send reminder) in under 2 clicks

⚠️ Risks
- Backend sync latency may cause slight delays in status refresh

- User training required for full feature adoption
