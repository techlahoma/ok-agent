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
- Only files matching these patterns are included: 01-Primary-Categories/**/*.md, 02-Secondary-Categories/**/*.md, 03-Content/**/*.md
- Files matching patterns in .gitignore are excluded
- Files matching default ignore patterns are excluded
- Files are sorted by Git change count (files with more changes are at the bottom)

# Directory Structure
```
01-Primary-Categories/
  01-Conference-Logistics.md
  01-Resources.md
  01-Sessions.md
  01-Speakers.md
02-Secondary-Categories/
  02-Keynotes.md
  02-Networking.md
  02-Technical-Sessions.md
  02-Venue-Details.md
  02-Workshops.md
03-Content/
  sessions/
    example-session-ai-in-government.md
  speakers/
    speaker-jane-doe.md
    speaker-tristan-kilgore.md
  Things to plan.md
```

# Files

## File: 01-Primary-Categories/01-Conference-Logistics.md
```markdown
---
type: category
level: primary
tags:
  - category
  - logistics
---

# Conference Logistics

This is the primary hub for all logistics-related information for the 200 OK Conference.

## Quick Links
- [[02-Venue-Details]]
- [[02-Networking]]

## Key Information

### Dates
- **Conference Date:** TBD
- **Registration Opens:** TBD
- **Speaker Deadline:** TBD

### Venue
See [[02-Venue-Details]] for complete venue information.

### Registration
<!-- Registration details and links -->

### Code of Conduct
<!-- Link to or embed code of conduct -->

## Timeline
| Date | Milestone |
|------|-----------|
| TBD | Registration Opens |
| TBD | Speaker Submissions Due |
| TBD | Schedule Announced |
| TBD | Conference Day |

## Contact
- **General Inquiries:** TBD
- **Speaker Questions:** TBD
- **Sponsor Inquiries:** TBD

## Related Categories
- [[01-Sessions]]
- [[01-Speakers]]
- [[01-Resources]]
```

## File: 01-Primary-Categories/01-Resources.md
```markdown
---
type: category
level: primary
tags:
  - category
  - resources
---

# Resources

This is the primary hub for all conference resources, materials, and references.

## Resource Types

### Code Examples
Located in `03-Content/resources/code-examples/`
- Sample code from sessions
- Starter templates
- Demo repositories

### Slides
Located in `03-Content/resources/slides/`
- Presentation decks
- Visual materials
- Handouts

### References
Located in `03-Content/resources/references/`
- External articles
- Documentation links
- Further reading

## Resources by Session
<!-- Auto-generated list of resources linked to sessions -->

## How to Add Resources

### For Speakers
1. Navigate to appropriate subfolder in `03-Content/resources/`
2. Create a new file using [[template-resource]]
3. Link to your session page
4. For large files (slides, videos), upload externally and add links

### File Hosting
- **Slides:** Upload to Google Drive or Speaker Deck
- **Code:** Host on GitHub
- **Videos:** Upload to YouTube (unlisted) or Vimeo

## Related Categories
- [[01-Sessions]]
- [[01-Speakers]]
- [[01-Conference-Logistics]]
```

## File: 01-Primary-Categories/01-Sessions.md
```markdown
---
type: category
level: primary
tags:
  - category
  - sessions
---

# Sessions

This is the primary hub for all session information at the 200 OK Conference.

## Session Types
- [[02-Technical-Sessions]] - Deep-dive technical talks
- [[02-Workshops]] - Hands-on learning experiences
- [[02-Keynotes]] - Featured presentations

## All Sessions

### By Track
<!-- Sessions organized by track -->

### By Difficulty
#### Beginner
<!-- Beginner-friendly sessions -->

#### Intermediate
<!-- Intermediate sessions -->

#### Advanced
<!-- Advanced sessions -->

## Session Schedule
| Time | Room A | Room B |
|------|--------|--------|
| 9:00 | TBD | TBD |
| 10:00 | TBD | TBD |
| 11:00 | TBD | TBD |

## How to Add a Session
1. Navigate to `03-Content/sessions/`
2. Create a new file using [[template-session]]
3. Fill in all session details
4. Link to your [[01-Speakers|speaker profile]]

## Related Categories
- [[01-Speakers]]
- [[01-Resources]]
- [[01-Conference-Logistics]]
```

## File: 01-Primary-Categories/01-Speakers.md
```markdown
---
type: category
level: primary
tags:
  - category
  - speakers
---

# Speakers

This is the primary hub for all speaker information at the 200 OK Conference.

## Featured Speakers
<!-- Keynote and featured speakers -->

## All Speakers

### By Organization
<!-- Speakers grouped by company/organization -->

### Alphabetical
<!-- All speakers A-Z -->

## Speaker Directory

| Speaker | Organization | Session(s) |
|---------|--------------|------------|
| [[speaker-tristan-kilgore]] | TBD | [[session-ai-in-government]] |
| <!-- Add more --> | | |

## For Speakers

### How to Add Your Profile
1. Navigate to `03-Content/speakers/`
2. Create a new file: `speaker-firstname-lastname.md`
3. Use [[template-speaker]] as your starting point
4. Fill in your bio, contact info, and session links
5. Add your headshot to `Attachments/` folder

### What to Include
- Professional bio (2-3 paragraphs)
- Current role and organization
- Areas of expertise
- Social media links
- Links to your session materials

### Questions?
Contact the organizing team via Slack or email.

## Related Categories
- [[01-Sessions]]
- [[01-Resources]]
- [[01-Conference-Logistics]]
```

## File: 02-Secondary-Categories/02-Keynotes.md
```markdown
---
type: category
level: secondary
parent: "[[01-Sessions]]"
tags:
  - category
  - keynote
---

# Keynotes

Featured presentations from industry leaders and thought-provoking speakers.

## Parent Category
[[01-Sessions]]

## Keynote Schedule
| Time | Keynote | Speaker |
|------|---------|---------|
| Opening | TBD | TBD |
| Closing | TBD | TBD |

## Featured Keynotes
<!-- List of keynote sessions -->

## About Our Keynotes
Keynote sessions are designed to inspire, challenge, and set the tone for the conference. These talks address big-picture themes relevant to all attendees regardless of technical specialty.

## Related Categories
- [[02-Technical-Sessions]]
- [[02-Workshops]]
- [[01-Speakers]]
```

## File: 02-Secondary-Categories/02-Networking.md
```markdown
---
type: category
level: secondary
parent: "[[01-Conference-Logistics]]"
tags:
  - category
  - networking
---

# Networking

Opportunities to connect with fellow attendees, speakers, and sponsors.

## Parent Category
[[01-Conference-Logistics]]

## Networking Events

### Before the Conference
- **Slack Channel:** Join #200ok on Techlahoma Slack
- **Pre-event Meetup:** TBD

### During the Conference
- **Morning Coffee:** 8:00 AM - 9:00 AM
- **Lunch Break:** Noon - 1:00 PM
- **Hallway Track:** Throughout the day
- **After Party:** TBD

### After the Conference
- **Follow-up Slack:** #200ok-alumni
- **Monthly Meetups:** Check Techlahoma calendar

## Tips for Networking
1. Introduce yourself to someone new during breaks
2. Share your contact info (business cards, LinkedIn)
3. Follow up within 48 hours
4. Join the Slack community to continue conversations

## Sponsor Tables
Visit our sponsors in the main hall:
<!-- List of sponsors with booth locations -->

## Related Categories
- [[02-Venue-Details]]
- [[01-Speakers]]
- [[01-Conference-Logistics]]
```

## File: 02-Secondary-Categories/02-Technical-Sessions.md
```markdown
---
type: category
level: secondary
parent: "[[01-Sessions]]"
tags:
  - category
  - technical
---

# Technical Sessions

Deep-dive technical talks covering programming, architecture, and hands-on implementation.

## Parent Category
[[01-Sessions]]

## Sessions in This Category

### Web Development
<!-- Sessions about web technologies -->

### Cloud & Infrastructure
<!-- Sessions about cloud, DevOps, infrastructure -->

### Data & AI
<!-- Sessions about data engineering, ML, AI -->

### Security
<!-- Sessions about security topics -->

### Mobile Development
<!-- Sessions about mobile app development -->

## Upcoming Technical Sessions
| Session | Speaker | Difficulty |
|---------|---------|------------|
| [[session-ai-in-government]] | [[speaker-tristan-kilgore]] | Intermediate |

## Related Categories
- [[02-Workshops]]
- [[02-Keynotes]]
- [[01-Resources]]
```

## File: 02-Secondary-Categories/02-Venue-Details.md
```markdown
---
type: category
level: secondary
parent: "[[01-Conference-Logistics]]"
tags:
  - category
  - venue
---

# Venue Details

Everything you need to know about the conference venue.

## Parent Category
[[01-Conference-Logistics]]

## Venue Information
**Name:** TBD
**Address:** TBD
**City:** Tulsa, Oklahoma

## Getting There

### By Car
<!-- Driving directions and parking info -->

### Parking
- **On-site Parking:** TBD
- **Nearby Lots:** TBD
- **Street Parking:** TBD

### Public Transit
<!-- Bus routes, etc. -->

### From the Airport
<!-- Directions from Tulsa International Airport -->

## Venue Map
<!-- Embed or link to venue floor plan -->

### Session Rooms
| Room | Capacity | Location |
|------|----------|----------|
| Room A | TBD | TBD |
| Room B | TBD | TBD |

### Key Locations
- **Registration:** TBD
- **Main Hall:** TBD
- **Lunch Area:** TBD
- **Sponsor Area:** TBD
- **Restrooms:** TBD

## Accessibility
- Wheelchair accessible: Yes/No
- Accessible parking: TBD
- Accessible restrooms: TBD
- Hearing assistance: TBD

## Nearby Amenities

### Food
<!-- Nearby restaurants -->

### Hotels
<!-- Recommended hotels with conference rates -->

### Coffee Shops
<!-- Nearby coffee shops -->

## Contact
For venue-specific questions, contact: TBD

## Related Categories
- [[02-Networking]]
- [[01-Conference-Logistics]]
```

## File: 02-Secondary-Categories/02-Workshops.md
```markdown
---
type: category
level: secondary
parent: "[[01-Sessions]]"
tags:
  - category
  - workshop
---

# Workshops

Hands-on learning experiences where you'll build something practical.

## Parent Category
[[01-Sessions]]

## What to Expect
- Interactive, hands-on sessions
- Bring your laptop
- Follow along with the instructor
- Leave with working code/project

## Workshop Schedule
| Time | Workshop | Instructor | Room |
|------|----------|------------|------|
| TBD | TBD | TBD | TBD |

## Prerequisites
Each workshop has specific prerequisites. Check the individual session page for:
- Required software installations
- Prior knowledge needed
- Materials to bring

## Workshops in This Category
<!-- List of workshop sessions -->

## Related Categories
- [[02-Technical-Sessions]]
- [[02-Keynotes]]
- [[01-Resources]]
```

## File: 03-Content/sessions/example-session-ai-in-government.md
```markdown
---
type: session
title: "Example: AI in Government"
speaker: "[[speaker-tristan-kilgore]]"
date: TBD
time: TBD
track: AI/ML
difficulty: intermediate
tags:
  - session
  - ai
  - government
---

# AI in Government

## Session Details
**Speaker:** [[speaker-tristan-kilgore]]
**Date:** TBD
**Time:** TBD
**Track:** AI/ML
**Difficulty:** Intermediate
**Room:** TBD

## Abstract
This session explores the practical applications of artificial intelligence in government settings. Learn how AI is being used to improve public services, increase efficiency, and serve citizens better while navigating the unique challenges of the public sector.

Topics covered include:
- Current state of AI adoption in government
- Case studies of successful implementations
- Ethical considerations and responsible AI use
- Procurement and implementation challenges
- Future opportunities and trends

## Learning Objectives
- Understand the current landscape of AI in government
- Learn practical approaches to AI implementation in public sector
- Recognize common challenges and how to address them
- Identify opportunities for AI in your organization

## Prerequisites
- Basic understanding of AI/ML concepts helpful but not required
- Interest in public sector technology

## Resources
- Slides: TBD
- Code Repository: TBD
- Additional Links: TBD

## Notes
<!-- Session notes, Q&A, follow-ups will be added during/after the conference -->

## Related Sessions
- [[session-data-governance]]

## Categories
**Primary:** [[01-Sessions]]
**Secondary:** [[02-Technical-Sessions]]
```

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

## File: 03-Content/Things to plan.md
```markdown
- Sponsors
    - [Progress.com](http://Progress.com)
    - Atlas
    - Zeeco?

- Swag: Stickers, Shirts, Hoodies
    - Design Inspiration

- Event Signage and print materials
    - Title, H1, H2, H3 logo placements
    - Printing
    - Day of Schedule
    - Venue map(Source from )

- Food/Catering: Breakfast, Lunch, Dinner
    - Breakfast Lunch Dinner Sponsors
    - Sam has preferred caterer

- Venue Prep
    - Plan venue prep and clean up

- How many tables needed

- AVL Testing

- Speakers prep
```
