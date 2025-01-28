
# Known Seclinq Production Bugs&Issues!

This document outlines the key issues identified in production to inform the team and facilitate resolution. Each issue is described briefly, along with its associated problem area.

## 1. [Frontend] Update Policy Bug (Controls List - Controls) 

![update-policy-bug-(controls_list-controls)](https://github.com/user-attachments/assets/ccc6a565-4e2f-44ef-a7a1-7fc6649e8eb0)

### Description:

-   When updating a policy, a bug occurs in the controls list, causing an inconsistency in the control updates.


### Potential Impact:

-   Incorrect or incomplete updates to policy controls.


### Suggested Solution:

-   Update payload with a Set of controls in variable (controls).

----------


## 2. [Backend] Update Assessment - Can't Change Clauses

![update-assessment-cant-change-clauses](https://github.com/user-attachments/assets/562bde14-a8b6-40c6-babf-666c0b77f473)

### Description:

-   Users are unable to modify clauses during an assessment update.

### Potential Impact:

-   Reduces the flexibility and usability of the assessment update feature.

### Suggested Solution
- build a new custom update serializer method.



----------

## 3. [Backend] Update Incident Error

![update-incident-error](https://github.com/user-attachments/assets/c7b486f4-ad89-4ade-a885-3857967340b1)

### Description:

-   An error occurs while updating incidents, preventing successful updates.

### Potential Impact:

-   Incident data may remain outdated, potentially impacting incident tracking and reporting.


### Suggested Solution
- Fix serializer custom validation class.

----------

## 4. Create Issue Error When Disabling Automated Due Date

![create-issue-error-when-disable-automated-due-date](https://github.com/user-attachments/assets/4ed85b3f-f6e2-4049-8594-07fad1e2c570)

### Description:

-   Errors are triggered when users attempt to create an issue with the automated due date feature disabled.

### Potential Impact:

-   Users may be unable to create issues without enabling automated due dates, affecting workflows.

----------

## 5. User Manual Error

![user-manual-error](https://github.com/user-attachments/assets/3ac06e63-4f98-4e1c-9964-87f001aca987)

### Description:

-   Errors are found within the user manual, either through incorrect information or broken functionality.

### Potential Impact:

-   Users may face confusion or challenges while navigating or using the system.

----------

### Next Steps:

-   Assign each issue to the appropriate team members for resolution.
-   Set priorities for fixing these issues based on their impact on production.
-   Conduct thorough testing after fixes are implemented to prevent regressions.
