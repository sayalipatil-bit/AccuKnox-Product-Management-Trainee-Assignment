# AccuKnox-Product-Management-Trainee-Assignment

## Cloud Posture Dashboard: Design a simple way for users to view and filter misconfigurations across multiple cloud accounts.

## Problem Statement :-
Nowadays organizations use multiple cloud accounts AWS, Azure and GCP. Each cloud has its own dashboards, policies and security alerts, which makes it hard for teams to track misconfigurations in one place. Because of this, issues often go unnoticed and fixing them becomes slow and reactive.
There is need for a single, easy to understand dashboard where users can quickly view, filter, and prioritize misconfigurations across all cloud accounts at once.

## Goal :-
Design a Cloud posture Dashboard that gives a simple, centralized way to view, filter and prioritize cloud misconfigurations across multiple cloud accounts.

## User Persona:-
Primary User- Cloud Security Engineer/ DevOps Engineer
Manages multiple cloud accounts
Responsible for identifying and fixing misconfigurations 
Works with limited time and high alert volume
Needs a quick way to see high risk issues first 
Relies on clear filters to narrow down problems 
Values a simple UI because thy switch between many tools daily

## User Goals-
See all cloud issues in one view
Prioritize high risk misconfigurations
Filter quickly by cloud, severity or resource type
Understand what to fix first
Reduce time spent navigating different cloud consoles

## Proposed features
Unified Misconfigurations List Combine AWS, Azure and GCP issues in one table Include cloud provider, resource, issue description, severity
Filters Tab (Left Side) Cloud provider (AWS/ Axure/ GCP) Severity (High/ Medium/ Low) Resource Type (Compute, Storage, Network, IAM)
Summary Cards (Top of Dashboard) Total High/ Medium/ Low issues Number of affected accounts
Issue Details Drawer When clicking on view issue details, a right-side panel opens with: Root cause Impact Severity Recommended fix View in cloud console Mark as resolved These features focus on speed, clarity and reducing mental load.

## Prioritization Rationale
I prioritized features based on: User’s most common task, reducing noise and ease of development
Users primarily look for high risk issues, so summary cards + severity filters are top priority.
Filters reduce noise, helping users focus instantly.
Issue details drawer minimizes switching between tabs/tools.
The combination of simple table, filter and detail panel makes a clean and realistic MVP with no unnecessary complexity.

## Success Metrics
Time to identify a critical issue- Reduce to under 30 seconds
Filter usage rate- Indicates meaningful navigation
Click through to detailed issue view- Shows engagement with the data
Reduction in unresolved high severity issues- Measures real impact
User Satisfaction- Aim for >8/10 from Security/ DevOps teams

## References:
https://www.elastic.co/docs/solutions/security/dashboards/cloud-security-posture-dashboard
https://docs.trendmicro.com/en-us/documentation/article/trend-vision-one-cloud-overview-dashboard
https://www.tenable.com/cloud-security/solutions/cspm
https://accuknox.com/
