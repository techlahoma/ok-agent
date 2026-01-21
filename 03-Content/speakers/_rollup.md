This file is a merged representation of a subset of the codebase, containing specifically included files, combined into a single document by Repomix.

# File Summary

## Purpose
This file contains a packed representation of a subset of the repository's contents that is considered the most important context.
It is designed to be easily consumable by AI systems for analysis, code review,
or other automated processes.

## File Format
The content is organized as follows:
1. This summary section
2. Repository information
3. Directory structure
4. Repository files (if enabled)
5. Multiple file entries, each consisting of:
  a. A header with the file path (## File: path/to/file)
  b. The full contents of the file in a code block

## Usage Guidelines
- This file should be treated as read-only. Any changes should be made to the
  original repository files, not this packed version.
- When processing this file, use the file path to distinguish
  between different files in the repository.
- Be aware that this file may contain sensitive information. Handle it with
  the same level of security as you would the original repository.

## Notes
- Some files may have been excluded based on .gitignore rules and Repomix's configuration
- Binary files are not included in this packed representation. Please refer to the Repository Structure section for a complete list of file paths, including binary files
- Only files matching these patterns are included: 03-Content/speakers/**/*.md
- Files matching patterns in .gitignore are excluded
- Files matching default ignore patterns are excluded
- Files are sorted by Git change count (files with more changes are at the bottom)

# Directory Structure
```
03-Content/
  speakers/
    speaker-jane-doe.md
    speaker-tristan-kilgore.md
```

# Files

## File: 03-Content/speakers/speaker-jane-doe.md
```markdown
---
type: speaker
name: "Jane Doe"
organization: ""
role: ""
tags:
  - speaker
---

# Jane Doe

## Bio
Jane Doe is a data governance expert with extensive experience helping organizations establish and maintain effective data management practices. Her work spans multiple industries, with a focus on creating practical, implementable governance frameworks.

<!-- Additional bio paragraphs to be added -->

## Current Role
**Organization:** TBD
**Position:** TBD
**Focus Areas:** Data Governance, Data Quality, Compliance

## Expertise
- Data Governance
- Data Quality Management
- Regulatory Compliance
- Data Strategy

## Sessions at 200 OK
- [[session-data-governance]]

## Contact & Social
- Email: TBD
- LinkedIn: TBD
- Twitter/X: TBD
- Website: TBD
- GitHub: TBD

## Resources
- Slides/Materials: TBD
- Referenced Projects: TBD

## Categories
**Primary:** [[01-Speakers]]
```

## File: 03-Content/speakers/speaker-tristan-kilgore.md
```markdown
---
type: speaker
name: "Example Tristan Kilgore"
organization: ""
role: ""
tags:
  - speaker
---

# Tristan Kilgore

## Bio
Tristan Kilgore is a technology professional with expertise in artificial intelligence and its applications in the public sector. With a passion for leveraging technology to improve government services, Tristan has worked on numerous projects bringing modern tech solutions to public organizations.

<!-- Additional bio paragraphs to be added -->

## Current Role
**Organization:** TBD
**Position:** TBD
**Focus Areas:** AI, Government Technology, Public Sector Innovation

## Expertise
- Artificial Intelligence
- Government Technology
- Public Sector Modernization
- Data Strategy

## Sessions at 200 OK
- [[session-ai-in-government]]

## Contact & Social
- Email: TBD
- LinkedIn: TBD
- Twitter/X: TBD
- Website: TBD
- GitHub: TBD

## Resources
- Slides/Materials: TBD
- Referenced Projects: TBD

## Categories
**Primary:** [[01-Speakers]]
```
