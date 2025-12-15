# AccuKnox-Product-Management-Trainee-Assignment

Cloud Posture Dashboard: Design a simple way for users to view and filter misconfigurations across multiple cloud accounts.

## Problem Statement
Nowadays organizations use multiple cloud accounts AWS, Azure and GCP. Each cloud has its own dashboards, policies and security alerts, which makes it hard for teams to track misconfigurations in one place. Because of this, issues often go unnoticed and fixing them becomes slow and reactive.
There is need for a single, easy to understand dashboard where users can quickly view, filter, and prioritize misconfigurations across all cloud accounts at once.

## Goal
Design a Cloud posture Dashboard that gives a simple, centralized way to view, filter and prioritize cloud misconfigurations across multiple cloud accounts.

## User Persona
Primary User- Cloud Security Engineer/ DevOps Engineer
1. Manages multiple cloud accounts
2. Responsible for identifying and fixing misconfigurations
3. Works with limited time and high alert volume
4. Needs a quick way to see high risk issues first
5. Relies on clear filters to narrow down problems
6. Values a simple UI because thy switch between many tools daily

## User Goals-
1. See all cloud issues in one view
2. Prioritize high risk misconfigurations
3. Filter quickly by cloud, severity or resource type
4. Understand what to fix first
5. Reduce time spent navigating different cloud consoles

## Proposed features
1. Unified Misconfigurations List Combine AWS, Azure and GCP issues in one table
2. Include cloud provider, resource, issue description, severity
3. Filters Tab (Left Side)
   Cloud provider (AWS/ Axure/ GCP)
   Severity (High/ Medium/ Low)
   Resource Type (Compute, Storage, Network, IAM)
4. Summary Cards (Top of Dashboard) High/ Medium/ Low and Total issues
5. By clicking on view issue details, a right-side panel opens with: Root cause, Impact, Severity, Recommended fix, View in cloud console, Mark as resolved

These features focus on speed, clarity and reducing mental load.

## Prioritization Rationale
I prioritized features based on: User’s most common task, reducing noise and ease of development
1. Users primarily look for high risk issues, so summary cards + severity filters are top priority.
2. Filters reduce noise, helping users focus instantly.
3. Issue details drawer minimizes switching between tabs/tools.
4. The combination of simple table, filter and detail panel makes a clean and realistic MVP with no unnecessary complexity.

## Success Metrics
1. Time to identify a critical issue- Reduce to under 30 seconds
2. Filter usage rate- Indicates meaningful navigation
3. Click through to detailed issue view- Shows engagement with the data
4. Reduction in unresolved high severity issues- Measures real impact
5. User Satisfaction- Aim for >8/10 from Security/ DevOps teams

## Wireframes
Main Dashboard Screen- 
<img width="1440" height="800" alt="Main Dashboard" src="https://github.com/user-attachments/assets/4b26d4e0-7d30-45bf-a57b-788f383050fc" />
Filter Screen- 
<img width="1440" height="800" alt="Filter Page" src="https://github.com/user-attachments/assets/26d66d87-2c6f-4d79-98a1-95f483c03a36" />
Issue Details Screen- 
<img width="1440" height="800" alt="Issue Details Page" src="https://github.com/user-attachments/assets/7b0848fa-557c-42b6-8999-81b8b340de2c" />

## Figma Design Links
Figma File (includes annotations)
https://www.figma.com/design/6g3dSk9OXF8ODxM6fmUEYb/Cloud-Posture-Dashboard?node-id=0-1&t=H1ZdHHX0m8xF5EWV-1

Figma Prototype (click through flow)
https://www.figma.com/proto/6g3dSk9OXF8ODxM6fmUEYb/Cloud-Posture-Dashboard?node-id=0-1&t=H1ZdHHX0m8xF5EWV-1

## References:
https://www.elastic.co/docs/solutions/security/dashboards/cloud-security-posture-dashboard
https://docs.trendmicro.com/en-us/documentation/article/trend-vision-one-cloud-overview-dashboard
https://www.tenable.com/cloud-security/solutions/cspm
https://accuknox.com/
