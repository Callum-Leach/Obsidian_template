---
project: 
created:
---
## Notes
```dataview
TABLE date as "Date"
FROM "Scratch Notes"
WHERE this.file.frontmatter.project = file.frontmatter.project
SORT date DESC
```

## Meetings
```dataview
TABLE date as "Date"
FROM "Meetings"
WHERE this.file.frontmatter.project = file.frontmatter.project
SORT date DESC
```
