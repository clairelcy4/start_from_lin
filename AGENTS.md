# Start From Lin — Agent Instructions

## Project Overview

**Start From Lin** is a personal website built with Hugo and deployed on Netlify.

Production URL: https://startfromlin.netlify.app/

The site combines:
- Personal branding and an approachable online identity.
- A multi-topic personal blog (not limited to technology).
- A professional portfolio featuring selected projects and experience.
- A Connect portal linking to professional and social platforms.
- Practical experience in website development, deployment, and maintenance.

Do not treat this as a cybersecurity-only website or a purely technical portfolio.

## Technical Principles

- Use Hugo, Markdown, Git/GitHub, and the existing Netlify deployment workflow.
- Inspect the actual repository configuration before assuming paths, theme features, or build commands.
- Prefer Hugo configuration, data files, reusable partials, and site-level layout/style overrides.
- **Do not directly modify the third-party theme submodule.** Explain any exception before proceeding.
- Avoid unnecessary frameworks, JavaScript dependencies, or large architectural changes.
- Keep content and social links maintainable from a clear, preferably central source of truth.
- Preserve existing content, URLs, and working features unless the task explicitly requires changes.

## Visual Identity

Design direction: **Japanese-inspired Soft Tech Minimalism** — warm, approachable, airy, readable, and professionally credible.

| Role | Colour | Hex |
| --- | --- | --- |
| Primary brand | Sora Blue | `#5FA3D0` |
| Main background | Warm Ivory | `#FAF8F3` |
| Primary text/headings | Deep Slate | `#293F50` |
| Cards/surfaces | White | `#FFFFFF` |
| Soft section background | Mist Blue | `#E5F1F7` |
| Decorative accent | Sakura Pink | `#E9B9B7` |
| Borders/dividers | Soft Sand | `#E9DCC8` |
| Accessible links | Deep Blue | `#23638D` |

- Use Sora Blue for brand identity, not as the background of every section.
- Prioritise readable long-form articles, clear hierarchy, whitespace, and responsive layouts.
- Use restrained decoration, subtle borders, and minimal motion; avoid dashboard-like card overload, neon, or hacker aesthetics.
- Check WCAG 2.2 AA contrast requirements. Do not use light Sora Blue for small text on ivory or white without verifying contrast.
- Prefer maintainable design tokens and reusable styling over one-off overrides.

## Content & Information Architecture

- Target sections: **Home, About, Blog, Projects, Connect**. Contact details may live within Connect.
- Blog must support multiple subjects, Markdown articles, and categories/tags as content grows.
- Projects should present genuine, approved work and link to repositories or demos only when available.
- Social links may include LinkedIn, Instagram, Facebook, and GitHub; never invent profile URLs.
- Do not invent personal details, achievements, credentials, contact information, or published content.
- Avoid adding advanced features (search, pagination, related posts, third-party widgets) without a clear need or explicit request.

## Workflow & Change Boundaries

1. Read only files relevant to the current task; avoid repeating repository-wide audits without a reason.
2. Check Git status before editing and preserve unrelated or uncommitted changes.
3. Implement the smallest maintainable change that satisfies the requested scope.
4. Run the relevant Hugo build and targeted checks after changes; report anything that could not be verified.
5. Validate local versus production URLs, responsive behavior, accessibility, and existing functionality when affected.
6. **Never commit, push, merge, deploy, or change production settings without explicit approval.**
7. Do not upgrade Hugo, replace the theme, install dependencies, or perform broad refactoring without explicit approval.
8. If a decision requires new personal content, assets, or credentials, ask rather than guessing.

## Communication

- Respond to the owner in **Traditional Chinese (繁體中文)**, keeping standard technical terms and identifiers in English.
- Keep responses concise and actionable. Avoid restating previous audits or pasting entire files unless requested.
- After implementation, summarise: **changes made, files affected, tests/results, unresolved issues, and decisions needed**.
- Clearly distinguish verified findings from assumptions.

These instructions are standing project conventions, not a request to implement any specific backlog item. Follow the current task's explicit scope and stop at its approval boundary.
