# Maintainers Guide – ADR Repository

This guide explains how to review and manage Architectural Decision Record (ADR) submissions.

---

## Reviewing Incoming ADRs

1. Go to the repository's **Pull Requests** tab.
2. Click on the submitted ADR pull request.
3. Check:
   - The file is in `Proposals/` (e.g., `Proposals/ADR001-Title.md`)
   - The content is complete and appropriate

4. Use the **"Files changed"** tab to review the ADR.
5. Add comments or request changes if needed.
6. When satisfied, click **“Approve”**, then **“Merge pull request”**.

---

## Branch Protection Settings (Configured in Settings > Branches)

Ensure the following rules are active on `main`:

- [x] Require pull request before merging
- [x] Require at least 1 approval
- [x] Restrict who can push (only maintainers)

This ensures all ADRs go through review.

---

## Optional Enhancements

- Add a `CODEOWNERS` file to auto-assign reviewers
- Use labels like `awaiting-review`, `changes-requested`, `approved`
- Track status in a GitHub Project board

---

## Proposals Folder

All merged ADRs are stored in: ADR/Proposals/


Do not store ADRs in the root or `Template/` folder.

---

## Template

Teams must base new ADRs on: Template/templateADR99.md

Do not modify the template without team agreement.

