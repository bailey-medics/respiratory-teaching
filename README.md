# Respiratory Teaching

Public reference repository for respiratory medicine teaching content.

Contains MCQ assessment question banks and learning modules for chest X-ray interpretation.

## Structure

```
questions/          — MCQ question banks (YAML + images)
learning/           — Learning modules (MDX, added later)
scripts/            — Validation and build scripts
.github/workflows/  — CI/CD (validate on PR, deploy on merge)
```

## Local development

This repo is cloned inside the `quillmedical` monorepo at `teaching-repos/respiratory-teaching/` (git-ignored by the parent repo).
