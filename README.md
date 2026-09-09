# CO3133 course project pages

Static skeleton for the three assignment pages.
Plain HTML/CSS (no build step).

## Files

```
index.html         landing page (institution, course, group, member table, assignment index)
assignment1.html    Assignment 1 page
assignment2.html    Assignment 2 page
assignment3.html    Assignment 3 page
assets/style.css    shared stylesheet
```

## To be updated in the skeleton

- Every `[bracketed]` placeholder is a value to replace (group ID, names,
  student IDs, links).
- Every dashed `TODO` box marks a section to write once results exist.
- `<span class="tag tag-todo">` badges track submission/approval status -
  swap the class to `tag-mandatory` styling or plain text once resolved, or just delete the badge.
- Resource links (`Source code`, `Checkpoints`, `Report`, `Slides`,
  `YouTube video`) start as inert placeholders (`class="pending"`) -
  remove that class and set a real `href` once each artifact exists.

## Reproducibility checklist (repo root, not this site)

Per the spec, the code repository itself (separate from these pages) needs:
`README.md` with install steps, dataset prep scripts/instructions, explicit
train/eval commands, config files, documented seeds, `requirements.txt`,
hardware info, checkpoint access, and links back to the report and this
GitHub Pages site - with every reported result traceable to a specific
config, split, checkpoint, and commit/tag.