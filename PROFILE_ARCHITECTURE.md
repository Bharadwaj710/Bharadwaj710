# Profile Architecture: Engineering Notebook

This document serves as the design specification and rationale behind the GitHub profile for Bharadwaj. It is intended to guide the future maintenance and expansion of the profile while maintaining its core "Engineering Notebook" aesthetic.

## 1. Core Objective
To position Bharadwaj not as a student or a template-user, but as a **Software Engineer building intelligent systems**. The profile demonstrates a deliberate focus on system design, maintainability, and continuous engineering growth.

## 2. Visual Identity & Theme
- **Theme:** Engineering Notebook / Workshop
- **Vibe:** Timeless, Premium, Structural, Documented, Intentional
- **Color Palette:**
  - Background: `#0D0D0D` (Dark Charcoal)
  - Primary Text: `#FFFFFF` (White)
  - Accent: `#2E4028` (Muted Racing Green)
  - Secondary Accent: `#8A8D91` (Metallic Silver/Grey)
- **Typography:** Monospace/Industrial fonts (`JetBrains Mono`, `Inter`, `Roboto Mono`) to mimic precise documentation.

## 3. Banner Design Specification
Instead of a generic avatar or busy graphic, the hero banner should look like an engineering blueprint header or a technical telemetry readout.

- **Dimensions:** `1500px x 500px` (3:1 ratio for optimal GitHub scaling).
- **Background:** Solid `#0D0D0D` or a very subtle, dark technical grid.
- **Typography:**
  - **Name:** Large, clean, monospace font (`JetBrains Mono`). Color: `#FFFFFF`.
  - **Status Line:** Small text in the top right corner indicating `[SYSTEM.ONLINE] - v2024.1` in the `#8A8D91` accent color.
- **Layout:** Left-aligned text to mimic a document header. Avoid centered, bloated graphics.
- **Graphic Elements:** A single, subtle geometric shape (like an angled bracket `< >` or a minimal vector line) in the `#2E4028` accent color. No 3D renders, no heavy shadows.

## 4. Folder Structure for Assets
Keep the repository clean. If you create a special repository matching your GitHub username (`Bharadwaj710/Bharadwaj710`), organize assets as follows:

```
.
├── README.md
├── PROFILE_ARCHITECTURE.md
└── assets/
    ├── banner.svg          # The main hero banner
    ├── icons/              # Any custom SVG icons for the toolbox
    └── diagrams/           # (Optional) System architecture diagrams for featured projects
```

## 5. Rationale Behind Key Sections

- **Engineering Principles:** Differentiates you immediately. Recruiters see *how* you think before they see *what* you know.
- **Featured Blueprints:** Replaces standard "project cards". By breaking projects down into Problem -> Challenge -> Solution, it proves you understand software engineering at a product level, not just a coding level.
- **Toolbox (Categorized):** Avoids the "badge wall" anti-pattern. Grouping by "Build With", "Comfortable With", and "Exploring" shows honesty and self-awareness about your skill depth.
- **Build Log:** A manual changelog that proves the profile is "living" and active, without relying on gimmicky automated visitor counters.
- **Journey & Evolution:** Provides a narrative. People remember stories better than bullet points. It explains *why* you are moving toward backend/AI, showing intentionality.

## 6. Future Expansion & GitHub Actions

When you are ready to add automation, avoid generic stats cards. Instead, consider:
- **Custom Workflow:** A GitHub Action that automatically updates the `[SHIPPED]` section of your Build Log when you merge a PR in a specific repository.
- **WakaTime CLI:** If you want to show activity, use a highly minimalist WakaTime script that only outputs a single line: `Current Focus: Python (Backend) - 45 hrs this week`.
- **System Architecture Diagrams:** Consider using Mermaid.js directly in the `README.md` to draw actual system architectures for WDIP or the AI Routing System. This heavily reinforces the "Engineering Notebook" vibe.
