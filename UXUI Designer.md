# UX/UI Designer — Roadmap & Onboarding

**Product:** BlueInventory — enterprise AI customer support platform
**Scope:** Product redesign, design system, and end-to-end user experience
**Duration:** 12 months, 4 phases

---

## Role Summary

You own how BlueInventory looks and feels. The product today reads as a prototype; your first job is to make it read as an enterprise platform. Over the year you will build and maintain a design system, design every major surface — help desk, document library, analytics, admin, billing — and extend it to mobile, white-label, and marketplace experiences.

### Collaboration

| Works closely with | On |
| --- | --- |
| Frontend Developer | Component implementation, design system in code, Storybook |
| Full Stack Developer | Admin panels, billing flows, onboarding |
| Data Engineer | Dashboard and reporting data models |

### Brand Guidelines

| Token | Value |
| --- | --- |
| Primary (navy) | `#09275e` |
| Accent (gold) | `#e8b042` |
| Corner radius | Square (0px) |

---

## Phase 1 — Foundation Design (Months 1–3)

**Objective:** Establish the design system and reposition the product visually as an AI SaaS platform.

- Redesign the homepage and marketing site for AI SaaS positioning, removing all remaining inventory-management references
- Build a comprehensive design system on the BlueInventory brand guidelines — colour, type scale, spacing, elevation, iconography, component states
- Design the responsive Help Desk interface for both public customers and internal staff operations
- Design the Library interface for document management: drag-and-drop uploads, folders, bulk actions, status indicators
- Design the Reports & Analytics dashboard, including the data visualisation component set

**Deliverables:** Design system file with documented tokens; high-fidelity designs for marketing site, Help Desk, Library, and Analytics; redlines handed to the Frontend Developer.

---

## Phase 2 — Advanced UI Components (Months 4–6)

**Objective:** Design the surfaces that make the platform sellable to organisations rather than individuals.

- Multi-tenant organisation management interfaces — org switching, member lists, role assignment, invitations
- Advanced chat components: typing indicators, file sharing, message threading, read states
- Billing and subscription management interfaces for enterprise plans, including usage display and upgrade paths
- Mobile-responsive designs across every major component
- Accessibility-compliant interfaces to WCAG 2.1 AA — contrast, focus order, keyboard paths, error messaging

**Deliverables:** Component library covering all Phase 2 surfaces; documented accessibility specification; responsive breakpoints defined and handed off.

---

## Phase 3 — Enterprise Features (Months 7–9)

**Objective:** Support enterprise buyers, administrators, and the integration ecosystem.

- White-label customisation options for enterprise clients — theming model, logo and colour overrides, custom domains
- Advanced analytics and business intelligence dashboards
- Integration marketplace and third-party app interfaces
- Administrator panels for system management
- A/B testing frameworks for conversion optimisation, including variant design and measurement plans

**Deliverables:** White-label theming specification; BI dashboard designs; marketplace and admin UI; documented A/B test variants with hypotheses.

---

## Phase 4 — Market Expansion (Months 10–12)

**Objective:** Extend the experience beyond the web app.

- Mobile app interfaces for iOS and Android, designed to React Native principles
- Browser extension interfaces for the major browsers
- Voice interface components and the accessibility features that support them
- Gamification and customer satisfaction tracking interfaces
- Onboarding flows aimed at enterprise customer acquisition

**Deliverables:** Mobile app design set; extension UI; voice interaction patterns; enterprise onboarding flow with measured drop-off points.

---

## First Month — Onboarding Tasks

Five real production tasks, chosen so you learn the product by shipping to it.

### 1. Homepage Redesign
Update landing page copy, hero section, and feature cards to reflect AI SaaS positioning.
**Done when:** No inventory-management language remains anywhere on the marketing site, and the hero states what the product does in one sentence.

### 2. Help Desk Interface
Improve empty states and conversation flow so the product reads as professional rather than as a demo.
**Done when:** Every empty state has copy, an illustration or icon, and a primary action.

### 3. Plans Page
Make the current plan obvious and show clear upgrade paths.
**Done when:** A signed-in user can identify their plan and the next tier without reading more than one screen.

### 4. Mobile Responsiveness
Ensure all dashboard components work on mobile devices.
**Done when:** Every dashboard surface is designed at 375px with no horizontal scroll and no truncated primary actions.

### 5. Privacy & Terms Pages
Create the legal pages linked from the footer.
**Done when:** Both pages exist, are styled to the design system, and are reachable from every page footer.

---

## Success Metrics

| Metric | Target |
| --- | --- |
| Design system coverage | 90%+ of shipped UI built from documented components |
| Accessibility | WCAG 2.1 AA across all core flows |
| Mobile | All dashboard surfaces usable at 375px |
| Onboarding completion | Measured and improving quarter over quarter |
| Customer satisfaction | 95%+ CSAT by end of Phase 2 |

## Tools

Design system file, Storybook (maintained jointly with the Frontend Developer), prototyping for key flows, and a documented handoff process with redlines and tokens exported for code.
