# Session 2 Reflection

### Q1. How do Issues and pull requests together support change control?

Issues help developers record problems, tasks or feature requests before starting work. They provide a clear description of what needs to be changed and the expected result. Pull requests allow developers to submit their completed changes for review before merging them into the main branch. Together, they make changes easier to track, review and manage.

### Q2. Why did the conflict in Part 4 happen, and how could a team reduce such conflicts?

The merge conflict happened because two branches changed the same lines in the same file differently. Git could not automatically decide which changes should be kept, so manual resolution was needed. A team can reduce these conflicts by communicating regularly, pulling the latest changes before starting work and avoiding changes to the same files at the same time. Developers should also merge their branches regularly to identify conflicts earlier.

### Q3. What would be lost if people merged straight into main without a pull request?

Merging directly into the main branch without a pull request would remove the opportunity for others to review the changes before they are included. Mistakes or incomplete changes could enter the main branch without being noticed. The team would also lose useful review discussions and a clear record of why changes were made. This would make collaboration, quality control and change tracking more difficult.
