# OpenMRS Jira Guide for Beginners

This guide helps new contributors navigate OpenMRS Jira, find issues, and start contributing.

---

## 1. Accessing Jira
1. Open your web browser and go to [OpenMRS Jira](https://issues.openmrs.org).  
2. You can browse as a guest, but to create or comment on issues, **sign up for an OpenMRS ID**.

---

## 2. Understanding the Jira Dashboard
- **Projects:** Shows all OpenMRS-related projects.  
  - Most contributions go to the **TRUNK** project.  
- **Filters:** Allows you to search issues by type (Bug, Task, Improvement) or label.  
- **Status:** Indicates progress (Open, In Progress, Resolved, Closed).

---

## 3. Searching for Issues
- Use the **Global Search** bar at the top to find specific issues or keywords.  
- Use **Filters → Labels** to find beginner-friendly issues (labels like `intro` or `docs`).  
- Example search: `project = TRUNK AND labels = intro AND status = Open`

---

## 4. Viewing Issue Details
Click on any issue to see:
- **Issue ID:** e.g., `TRUNK-6123`  
- **Summary:** Short description of the issue  
- **Description:** Detailed explanation  
- **Assignee:** Who is currently working on it  
- **Comments:** Discussion by other contributors  
- **Attachments:** Screenshots, logs, or files related to the issue

---

## 5. Commenting and Asking Questions
- Scroll down to the **Comments** section.  
- Write clearly and politely — for example:  
  > “Hi, I am interested in working on this issue. Could I get it assigned to me?”  
- Maintain open communication to avoid duplicate work.

---

## 6. Claiming or Assigning Issues
- Once you’re ready to work on an issue, **ask the maintainers to assign it** to you.  
- Include your OpenMRS ID so they can update the issue.  
- Example comment:  
  > “I would like to work on this TRUNK issue. My OpenMRS ID is `YourID`.”

---

## 7. Referencing Jira Issues in Your Pull Request
- When submitting code on GitHub, **reference the Jira issue ID** in your commit message:  
  ```bash
  git commit -m "TRUNK-6123: Corrected typo in documentation"
