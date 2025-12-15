A. Proposed features
1. Unified Misconfigurations List
Combine AWS, Azure and GCP issues in one table
Include cloud provider, resource, issue description, severity
2. Filters Tab (Left Side)
Cloud provider (AWS/ Axure/ GCP)
Severity (High/ Medium/ Low)
Resource Type (Compute, Storage, Network, IAM)
3. Summary Cards (Top of Dashboard)
Total High/ Medium/ Low issues
Number of affected accounts
4. Issue Details Drawer
When clicking on view issue details, a right-side panel opens with:
Root cause
Impact
Severity
Recommended fix
View in cloud console
Mark as resolved
These features focus on speed, clarity and reducing mental load.

B. Prioritization Rationale

I prioritized features based on: User’s most common task, reducing noise and ease of development 
1. Users primarily look for high risk issues, so summary cards + severity filters are top priority.
2. Filters reduce noise, helping users focus instantly.
3. Issue details drawer minimizes switching between tabs/tools.
4. The combination of simple table, filter and detail panel makes a clean and realistic MVP with no unnecessary complexity.

C. Success Metrics
1. Time to identify a critical issue- Reduce to under 30 seconds
2. Filter usage rate- Indicates meaningful navigation
3. Click through to detailed issue view- Shows engagement with the data
4. Reduction in unresolved high severity issues- Measures real impact
5. User Satisfaction- Aim for >8/10 from Security/ DevOps teams

