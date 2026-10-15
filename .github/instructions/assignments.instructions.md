---
description: "Use when creating or editing assignment Markdown files to keep student instructions consistent, clear, and aligned with the project template."
applyTo: "assignments/**/*.md"
---

# Assignment Markdown Guidelines

Create or update assignment files as `README.md` files inside the appropriate assignment folder. Follow [`templates/assignment-template.md`](../../templates/assignment-template.md) and preserve its section order and heading format.

## Required structure

- **Title:** Use `# 📘 Assignment: [Assignment Title]` with a short, descriptive assignment name.
- **Objective:** Keep `## 🎯 Objective` and describe in 1–2 sentences what students will build or learn.
- **Tasks:** Keep `## 📝 Tasks`. Include one task section for each meaningful part of the assignment, using the template's heading and subsection format:
  - `### 🛠️ [Task Title]` with a specific, action-oriented title.
  - `#### Description` with a clear statement of what the student must do.
  - `#### Requirements` followed by `Completed program should:` and measurable bullet-point outcomes.

The template shows two task sections as examples. Repeat the task-section format as needed; do not omit the Objective or Tasks sections or change their order. Replace all template placeholders with assignment-specific content. Include example input/output in a code block when it helps clarify a requirement.

Do not add unrelated sections or requirements that are not part of the assignment.