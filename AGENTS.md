
# Weibo Gaming Archive — Project Instructions

## 1. Project Overview

Weibo Gaming Archive is an independent fan-made archive dedicated to the 博七 era of the Identity V division of Weibo Gaming (WBG), also known as Beijing WBG.

The archive focuses on five core starting players:

- Huiyi（回憶）— Survivor
- Guoker（過客）— Survivor
- Persica（桃晚安）— Survivor
- Koting（空調）— Survivor
- N1e（捏捏）— Hunter

These five players define the identity of 博七. Substitute players, coaches, and other team members may appear in relevant records, but changes to supporting roles do not redefine this core lineup.

The 博七 era began when N1e and Koting officially joined WBG on 2025-05-27. It ended when Koting transferred in May 2026.

The archive covers:
- 2025 IVL Summer
- 2025 IVL Autumn
- COA IX（深淵的呼喚 IX）
- Important events between the formation and the end of 博七

This is an independent fan project. It is not an official website of Weibo Gaming or Identity V League (IVL).

## 2. Project Goals

- Preserve the history and shared experiences of the five core starting players.
- Organize tournament results, match records, achievements, and important events.
- Present the development of the 博七 era in a clear chronological structure.
- Provide an immersive and easy-to-browse archive.
- Maintain a consistent visual identity across all pages.
- Make the project easy for AI agents and future contributors to maintain and expand.

## 3. Language and Terminology

- Traditional Chinese（繁體中文）is the primary interface language.
- Follow Taiwan Traditional Chinese conventions.
- Use English for filenames, code, technical identifiers, and appropriate terminology.
- Use「博七」when referring to this period.
- Do not use「B7」as a replacement for「博七」in website content.
- Use「WEIBO GAMING」as the website's main brand name. Do not add a period after GAMING.
- Use「深淵的呼喚 IX」as the Chinese name of COA IX.
- Keep player names and nicknames consistent throughout the website.

## 4. Project Structure

The current project structure is:

```text
weibo-gaming-archive/
├── AGENTS.md
├── README.md
├── index.html
├── players.html
├── tournaments.html
├── moments.html
├── achievements.html
└── images/
    ├── tournament.jpg
    ├── moments.jpg
    ├── achievements.jpg
    └── other image assets
```

### File Responsibilities

- `index.html`: Homepage, project introduction, and navigation to other sections.
- `players.html`: Profiles and information about the five core starting players.
- `tournaments.html`: Tournament history, match records, and official video references.
- `moments.html`: Important events and the chronological timeline of the 博七 era.
- `achievements.html`: Tournament placements and significant competitive achievements.
- `images/`: All local image assets used by the website.
- `AGENTS.md`: Project rules and instructions for AI agents.
- `README.md`: Project introduction, website links, and documentation.

When adding files, update this structure in `AGENTS.md` if the project organization changes.

## 5. Website Design Direction

### Visual Identity

- Theme: Dark.
- Style: Modern, editorial, immersive, and archive-oriented.
- The website should feel like a carefully curated esports history archive.
- Use dark backgrounds, muted text, and burgundy or red accent colors.
- Maintain consistent typography, spacing, borders, and visual hierarchy.
- Avoid unnecessary decoration, excessive animations, and cluttered layouts.

### Layout

- Use consistent header navigation across all pages.
- Use consistent footer styling.
- Keep page titles and section headings visually clear.
- Use cards, timelines, and content sections according to each page's purpose.
- Ensure images do not distort or overflow their containers.

### Responsive Design

- Desktop is the primary design target.
- All pages must remain usable on tablets and mobile devices.
- Navigation must adapt to smaller screens.
- Text must remain readable without horizontal scrolling.
- Cards, images, and content sections must fit smaller screens.

## 6. Page Structure and Content Rules

### Homepage — index.html

Purpose:
- Introduce the archive.
- Explain the project's scope.
- Provide navigation to the main content sections.

Rules:
- Keep the homepage focused on introducing the 博七 archive.
- Archive cards should link to the corresponding independent pages.
- Keep section descriptions concise.
- Do not duplicate entire sections from other pages.

### Players — players.html

Purpose:
- Document the five core starting players.

Rules:
- Include Huiyi, Guoker, Persica, Koting, and N1e.
- Clearly distinguish Survivors from the Hunter.
- Keep player names, nicknames, and roles consistent.
- Use the same card structure for player profiles.
- Do not invent player biographies, statistics, or career information.
- Information outside the 博七 period should only be included when relevant.

### Tournaments — tournaments.html

Purpose:
- Record important tournaments and match results.

Rules:
- Organize tournaments chronologically.
- Use a consistent card structure for each tournament.
- Include tournament names, years, results, and relevant match records.
- Make final placements visually distinguishable from match details.
- Keep match records in chronological order.
- Clearly distinguish qualification stages, group stages, and knockout stages when applicable.
- Do not invent match scores or results.
- Keep official video references clearly identified.

### Moments — moments.html

Purpose:
- Preserve important events during the 博七 era.

Rules:
- Use a chronological timeline.
- Each event should have a date, title, description, and optional tag.
- Keep descriptions concise but preserve important historical context.
- Use consistent timeline styling.
- Place relevant photographs near the events they illustrate.
- Do not invent dates or present uncertain events as confirmed facts.

### Achievements — achievements.html

Purpose:
- Present important tournament placements and achievements.

Rules:
- Use a consistent card structure.
- Clearly display each tournament's final result.
- Keep the descriptions consistent with the tournament records.
- Do not confuse tournament qualification results with final tournament placements.
- Do not exaggerate achievements or invent awards.

## 7. Rules for Adding New Pages

When adding a new page:

1. Read this file and inspect the existing pages first.
2. Identify which existing page provides the closest layout and visual reference.
3. Reuse the established header, navigation, footer, colors, typography, and spacing.
4. Give the new page a clear purpose and avoid unnecessary duplication.
5. Use a descriptive lowercase English filename ending in `.html`.
6. Add a navigation link if the new page is intended to be part of the main website.
7. Ensure the new page links correctly to the other relevant pages.
8. Check desktop and mobile layouts.
9. Update the project structure in this document and README.md when necessary.

Do not create a completely different visual style for a new page unless explicitly requested.

## 8. Rules for Adding New Content

When adding content to existing pages:

- Follow the structure and formatting already used on that page.
- Keep headings, paragraphs, cards, tags, and dates consistent.
- Place information in the page that best matches its purpose.
- Avoid duplicating the same long description across multiple pages.
- Preserve existing content unless the user explicitly requests a change.
- Do not add unrelated historical information merely to increase page length.

When adding tournament records:
- Verify the tournament name, date, stage, result, and score.
- Keep match records in chronological order.

When adding player information:
- Verify the player's name, nickname, role, and relevant period.
- Do not assume that every registered player was one of the five core starters.

When adding timeline events:
- Use the actual event date whenever it is known.
- Keep the timeline chronological.
- Clearly distinguish verified events from personal interpretations.

## 9. File and Asset Naming Rules

### HTML Files

- Use lowercase English filenames.
- Use hyphens to separate words when necessary.
- Keep filenames descriptive.

Examples:
- `players.html`
- `tournaments.html`
- `moments.html`

### Image Files

- Store local images in the `images/` directory.
- Use lowercase English filenames.
- Use hyphens for multiword filenames.
- Use descriptive names related to the image's purpose.
- Avoid spaces and special characters in filenames.

Examples:
- `tournament.jpg`
- `moments.jpg`
- `achievements.jpg`
- `koting-farewell.jpg`

### Image Usage

- Use relative paths, such as `images/example.jpg`.
- Preserve the original image proportions unless cropping is intentional.
- Provide meaningful alternative text for informative images.
- Do not reference files that do not exist.
- Respect copyright and image usage rights.
- Do not imply that fan-made images or materials are official.

## 10. Information Accuracy and Sources

- Never fabricate player information, tournament results, dates, statistics, or historical events.
- Use reliable sources whenever possible.
- Provide source references for factual information when available.
- Distinguish confirmed information from uncertain information.
- Do not present fan speculation or personal opinions as official facts.
- Preserve important historical context.
- If information cannot be verified, ask the user or clearly mark it as unconfirmed.
- Do not silently replace user-provided historical interpretations with assumptions.

## 11. Technical Requirements

- Use HTML and CSS for the website unless the user requests otherwise.
- Maintain compatibility with GitHub Pages.
- Use relative paths for local pages and assets.
- Ensure all navigation links and internal links work.
- Avoid unnecessary external libraries and dependencies.
- Keep code readable and maintainable.
- Use semantic HTML elements where appropriate.
- Use responsive CSS for different screen sizes.
- Avoid introducing unnecessary complexity.

The existing pages use individually written HTML and CSS. Follow the existing implementation unless there is a clear reason to reorganize it.

Do not introduce a framework, build system, or complex folder structure without the user's approval.

## 12. Development Rules for AI Agents

### Before Making Changes

1. Read this `AGENTS.md` file.
2. Inspect the relevant HTML file and existing project structure.
3. Understand the current layout and styling.
4. Identify the exact section that needs modification.
5. Check whether the requested feature already exists.
6. Ask the user when essential information is missing.

### While Making Changes

- Follow all project rules in this document.
- Make the smallest reasonable changes.
- Preserve existing working features.
- Do not rewrite entire files when a small modification is sufficient.
- Do not silently remove existing content or functionality.
- Do not invent information to fill missing details.
- Explain where the user should insert, replace, or remove code.
- For beginner users, provide clear and specific instructions.
- Do not claim to have modified GitHub files unless the modification was actually performed.

### After Making Changes

Check the following where applicable:

- HTML structure is valid.
- CSS changes do not unintentionally affect other sections.
- Navigation links work.
- Local images load correctly.
- No existing content has disappeared.
- Desktop and mobile layouts remain usable.
- GitHub Pages paths work correctly.
- The public website displays the latest version after deployment.

Report any unverified information or incomplete functionality clearly.

## 13. Accessibility and Usability

- Use semantic HTML.
- Provide meaningful alternative text for informative images.
- Maintain sufficient text contrast.
- Make links identifiable.
- Keep navigation consistent.
- Use clear page titles.
- Avoid interactions that depend only on hover.
- Ensure the website remains usable on smaller screens.

## 14. Project Priorities

Development priorities, in order:

1. Historical accuracy and preservation of the 博七 era.
2. Clear information architecture.
3. Consistent visual identity.
4. Complete and understandable content.
5. Responsive design and usability.
6. Maintainable code and future expansion.

Do not sacrifice historical accuracy or important context merely to simplify implementation.

## 15. Deployment

- The project is hosted through GitHub Pages.
- The main branch is `main`.
- The website is published from the repository root.
- Keep all required HTML files and assets in the repository.
- Verify deployment settings when configuration changes.
- Test the public website after publishing.
- Ensure README.md and AGENTS.md remain available in the repository.

## 16. Future Expansion

This archive may be expanded with additional pages or content when requested.

Possible extensions include:
- More detailed player profiles.
- Additional tournament records.
- More important moments.
- Additional photographs and media references.
- New sections related to the history of the 博七 era.

All future additions must follow the existing project structure, visual identity, terminology, and information accuracy rules.

The goal is not simply to create more pages, but to ensure that every new page feels like part of the same archive.
