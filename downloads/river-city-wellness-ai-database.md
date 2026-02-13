# River City Wellness AI Database

## Organization Profile

| Field | Detail |
|---|---|
| **Name** | River City Wellness ATX |
| **Location** | Austin, Texas |
| **Industry** | Health & Wellness |
| **Platform** | GitHub Pages (Jekyll) |
| **Repository** | rivercitywellnessatx/skills-github-pages |

---

## Database Context

This file serves as the central AI reference database for River City Wellness ATX. All future AI-assisted development, content generation, and project context should reference this document.

---

## Business Context

### Mission
Provide holistic wellness services and resources to the Austin, Texas community through accessible digital and in-person experiences.

### Service Categories

| ID | Category | Description |
|---|---|---|
| SVC-001 | Wellness Programs | Structured programs for physical and mental well-being |
| SVC-002 | Community Resources | Guides, articles, and educational wellness content |
| SVC-003 | Digital Presence | Website, blog, and online engagement via GitHub Pages |
| SVC-004 | Client Support | Personalized wellness guidance and follow-up |

---

## Technical Infrastructure

### Current Stack

| Component | Technology | Status |
|---|---|---|
| Hosting | GitHub Pages | Active |
| Static Site Generator | Jekyll | Configured |
| Theme | Minima | Default |
| CI/CD | GitHub Actions | Active (6 workflows) |
| Dependency Management | Dependabot | Monthly updates |

### Repository Structure

```
skills-github-pages/
├── .github/
│   ├── dependabot.yml
│   ├── steps/              # Learning/setup progression
│   └── workflows/          # Automation workflows
├── downloads/              # Downloadable resources & database files
│   └── river-city-wellness-ai-database.md  (this file)
├── .gitignore
├── LICENSE                 # MIT
└── README.md
```

---

## Content Database Schema

### Blog Posts / Articles

| Field | Type | Description |
|---|---|---|
| `post_id` | String | Unique identifier (e.g., POST-001) |
| `title` | String | Article title |
| `category` | Enum | wellness, nutrition, fitness, mindfulness, community |
| `date` | Date | Publication date |
| `author` | String | Content author |
| `tags` | Array | Searchable tags |
| `status` | Enum | draft, published, archived |

### Services

| Field | Type | Description |
|---|---|---|
| `service_id` | String | Unique identifier (e.g., SVC-001) |
| `name` | String | Service name |
| `description` | Text | Service description |
| `category` | Enum | program, resource, digital, support |
| `availability` | Enum | active, seasonal, upcoming |

### Client Resources

| Field | Type | Description |
|---|---|---|
| `resource_id` | String | Unique identifier (e.g., RES-001) |
| `title` | String | Resource title |
| `format` | Enum | pdf, video, article, guide |
| `topic` | String | Wellness topic covered |
| `access_level` | Enum | public, registered, premium |

---

## AI Integration Notes

### Context Rules
- All AI-generated content for this project should align with the wellness-focused mission of River City Wellness ATX.
- Content tone: informative, supportive, community-oriented.
- Location context: Austin, Texas ("River City").
- Prioritize evidence-based wellness information.

### Data Handling
- No personally identifiable information (PII) is stored in this database.
- Client data references are schema-only; actual data is managed externally.
- All public-facing content follows MIT license terms per repository LICENSE.

---

## Changelog

| Date | Change | Author |
|---|---|---|
| 2026-02-13 | Initial database creation | AI Assistant |

---

*This database is maintained as part of the River City Wellness ATX digital infrastructure. All updates should be committed to the `downloads/` directory of the repository.*
