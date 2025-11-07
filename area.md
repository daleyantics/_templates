---
type: area
created: {{date}}
review: {{date+90d}}
tags: [area]
---

# {{title}}

## Purpose
A short statement of why this Area exists and what you’re responsible for here.

## Standards / Principles
- Define what “good” looks like in this Area.
- List rules, values, or expectations to uphold.

## Related Projects
```dataview
LIST FROM "Projects"
WHERE contains(area, this.file.link)
SORT status ASC
```

## Active Tasks
```tasks
path includes {{title}}
status.type is not done
```

## Resources
External links, references, tools.

## Maintenance / Routines
- Weekly review
- Monthly health check
- Update standards when needed

## Notes
Free‑form notes, insights, or observations related to this Area.
