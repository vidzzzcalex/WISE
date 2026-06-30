# WISE — Brand Guidelines & Application Rules

> **Version:** 1.0  
> **Last Updated:** June 2026  
> **Application Type:** AI-Powered Workforce Intelligence Platform

---

## 1. About WISE

**WISE** is an AI-powered Workforce Intelligence & Strategy Engine designed for HR leaders, People Officers, and organizational decision-makers. The platform delivers real-time insights across talent health, skill mapping, redundancy analysis, career trajectory, and AI-driven recommendations — enabling data-backed workforce decisions at scale.

### Core Value Proposition
- Organization Health Scoring with predictive risk flags
- Employee Digital Twin Profiles with skill clouds
- AI Recommendations for talent mobility and upskilling
- Workforce Productivity Indexing with trend analysis
- Critical Gap Detection across departments and roles

### Target Users
- Chief People Officers (CPOs)
- HR Business Partners
- Talent Acquisition & L&D Teams
- C-Suite Executives reviewing org-wide workforce data

---

## 2. Brand Identity

### 2.1 Brand Name
- **Full Name:** WISE
- **Always written in:** ALL CAPS
- **Never written as:** Wise, wise, W.I.S.E.
- **Tagline (optional use):** *Workforce Intelligence, Simplified.*

### 2.2 Brand Personality
| Trait | Expression |
|---|---|
| Intelligent | Data-dense layouts; precise labels; no fluff copy |
| Trustworthy | Consistent color coding; clear error states; honest metrics |
| Modern | Dark UI; smooth gradients; clean sans-serif typography |
| Empowering | Action-oriented CTAs; AI nudges framed as suggestions, not commands |
| Professional | No emojis in UI; no casual language in system messages |

---

## 3. Color System

All colors must be applied consistently across every screen, component, and exported asset.

### 3.1 Primary Palette

| Token | Name | Hex | Usage |
|---|---|---|---|
| `--color-bg-primary` | Deep Navy | `#0D0F1A` | Main app background |
| `--color-bg-surface` | Surface Dark | `#13162A` | Cards, panels, sidebars |
| `--color-bg-elevated` | Elevated Surface | `#1C2040` | Modals, tooltips, dropdowns |
| `--color-accent-primary` | Electric Violet | `#7C5CFC` | Primary CTAs, active nav, key highlights |
| `--color-accent-teal` | Teal Glow | `#00C9B1` | Success states, positive metrics, skill tags |
| `--color-accent-blue` | Bright Blue | `#4B9EFF` | Links, secondary actions, chart lines |

### 3.2 Semantic / Status Colors

| Token | Name | Hex | Usage |
|---|---|---|---|
| `--color-critical` | Alert Red | `#FF4D6A` | Critical risks, negative delta, urgent flags |
| `--color-warning` | Amber | `#F5A623` | Medium risk, warnings, burnout indicators |
| `--color-success` | Mint Green | `#00C9A7` | Healthy scores, completed actions |
| `--color-neutral` | Slate | `#6B7280` | Inactive states, secondary labels |

### 3.3 Text Colors

| Token | Hex | Usage |
|---|---|---|
| `--text-primary` | `#FFFFFF` | Headings, primary data values |
| `--text-secondary` | `#A0A8C0` | Subheadings, meta labels |
| `--text-muted` | `#5A6382` | Placeholder text, disabled states |
| `--text-inverse` | `#0D0F1A` | Text on light/accent backgrounds |

### 3.4 Gradient Tokens

| Token | Value | Usage |
|---|---|---|
| `--gradient-accent` | `linear-gradient(135deg, #7C5CFC, #4B9EFF)` | Logo, primary buttons, circular score rings |
| `--gradient-surface` | `linear-gradient(180deg, #13162A, #0D0F1A)` | Page section transitions |
| `--gradient-teal` | `linear-gradient(135deg, #00C9B1, #4B9EFF)` | Skill tags, positive stat highlights |

### 3.5 Color Rules
- **Never** place light text on `--color-accent-teal` without checking contrast (minimum 4.5:1 ratio).
- **Never** use pure white `#FFFFFF` as a background — always use surface tokens.
- **Always** use `--color-critical` for negative metrics, never amber or orange.
- Status colors must **only** be used for their designated semantic purpose — do not repurpose `--color-success` as a decorative accent.

---

## 4. Typography

### 4.1 Typefaces

| Role | Typeface | Weight | Usage |
|---|---|---|---|
| Display / Headings | **Inter** | 700 (Bold) | Page titles, section headers, metric values |
| Body | **Inter** | 400 (Regular) | Descriptions, paragraph text, tooltips |
| Data / Labels | **Inter** | 500 (Medium) | Table cells, tags, stat labels, nav items |
| Mono | **JetBrains Mono** | 400 | Code snippets, IDs, API references (if shown) |

### 4.2 Type Scale

| Level | Size | Weight | Line Height | Token |
|---|---|---|---|---|
| Display | 32px | 700 | 1.2 | `--text-display` |
| H1 | 24px | 700 | 1.3 | `--text-h1` |
| H2 | 18px | 600 | 1.4 | `--text-h2` |
| H3 | 14px | 600 | 1.5 | `--text-h3` |
| Body | 13px | 400 | 1.6 | `--text-body` |
| Caption | 11px | 400 | 1.5 | `--text-caption` |
| Label | 11px | 500 | 1.4 | `--text-label` |

### 4.3 Typography Rules
- **Sentence case** for all UI labels, button text, and nav items. (e.g., "View all insights" not "View All Insights")
- **ALL CAPS** only for: the brand name WISE, section eyebrows/category tags (e.g., "HIGH POTENTIAL")
- **Never** use decorative or serif fonts in the product UI.
- Metric values (scores, percentages, counts) must always use `--text-display` or `--text-h1` at Bold weight.
- Never set body text below **11px**.

---

## 5. Spacing & Layout

### 5.1 Spacing Scale (8px base grid)

| Token | Value | Usage |
|---|---|---|
| `--space-1` | 4px | Internal icon padding |
| `--space-2` | 8px | Tight component gaps |
| `--space-3` | 12px | Between label and value |
| `--space-4` | 16px | Card internal padding |
| `--space-5` | 24px | Between cards |
| `--space-6` | 32px | Section gaps |
| `--space-7` | 48px | Page-level vertical rhythm |

### 5.2 Layout Rules
- **Mobile-first** — all components must be responsive down to 375px.
- Cards use `border-radius: 12px` consistently. Never mix radii within the same screen.
- Panels and sidebars use `border-radius: 0` on the attached edge, `12px` on the free edge.
- Maximum content width: **1280px** centered on large screens.
- Sidebar width: **240px** (collapsed: **64px**).
- Navigation is always **bottom tab bar on mobile**, **left sidebar on desktop**.

### 5.3 Grid
- Desktop: 12-column grid, 24px gutters, 32px margins
- Mobile: 4-column grid, 16px gutters, 16px margins

---

## 6. Component Rules

### 6.1 Cards
- Background: `--color-bg-surface`
- Border: `1px solid rgba(255,255,255,0.06)`
- Border radius: `12px`
- Padding: `16px`
- Shadow: `0 4px 24px rgba(0,0,0,0.3)`
- Cards must never contain more than **one primary action**.

### 6.2 Buttons

| Variant | Background | Text | Border | Use |
|---|---|---|---|---|
| Primary | `--gradient-accent` | `#FFFFFF` | None | One per screen max |
| Secondary | `transparent` | `--color-accent-primary` | `1px solid --color-accent-primary` | Secondary actions |
| Ghost | `transparent` | `--text-secondary` | None | Tertiary / nav actions |
| Destructive | `--color-critical` | `#FFFFFF` | None | Delete / remove actions |

- Button border radius: `8px`
- Button height: `36px` (default), `28px` (compact), `44px` (large/CTA)
- **Never** use more than one Primary button per view.
- All buttons must have a visible focus ring for keyboard accessibility.

### 6.3 Tags & Badges
- Skill tags: `--gradient-teal` background, white text, `border-radius: 20px`, `padding: 4px 10px`
- Status badges (Critical / At Risk / Healthy): use semantic color tokens only
- Font: `--text-label` (11px, medium weight)

### 6.4 Progress / Score Rings
- Use circular SVG rings for percentage scores (e.g., Organization Health Score)
- Active arc color: `--gradient-accent`
- Track color: `rgba(255,255,255,0.08)`
- Always show the numeric value centered in the ring at `--text-display` size

### 6.5 Charts & Data Visualization
- Line charts: `--color-accent-blue` for primary line, `--color-accent-teal` for secondary
- Area fills: use 15% opacity of the line color
- Bar charts: use `--color-accent-primary` for positive, `--color-critical` for negative/gap
- Grid lines: `rgba(255,255,255,0.05)`
- Always include axis labels in `--text-caption`

### 6.6 Navigation
- Active item: `--color-accent-primary` icon + label
- Inactive item: `--text-muted` icon + label
- Bottom nav (mobile): 5 items max, icon + label, `48px` height
- Left sidebar (desktop): icons with labels, grouped by section, collapsible

### 6.7 AI Recommendation Cards
- Left border accent: `3px solid --color-accent-primary`
- Icon: sparkle / brain icon in `--color-accent-primary`
- Tone of copy: Specific and action-oriented. Never vague ("Consider hiring" ✗ → "Ajay is the best replacement for Ria's role, based on 91% skill match" ✓)

---

## 7. Iconography

- **Icon set:** Lucide Icons (preferred) or Heroicons — outline style only
- **Size:** 16px (inline), 20px (nav), 24px (feature icons)
- **Color:** Inherit from context — never hardcode icon colors
- **Never** mix filled and outline icons on the same screen
- Status icons (warning ⚠, critical 🔴, success ✅) must always be accompanied by a text label — never rely on color alone

---

## 8. Motion & Animation

- **Default transition:** `all 0.2s ease`
- **Card hover:** `transform: translateY(-2px)`, `box-shadow` elevation increase
- **Score ring:** Animate arc draw on mount (`stroke-dashoffset` transition, 800ms ease-out)
- **AI suggestions:** Fade in with `opacity: 0 → 1`, `translateY(8px → 0)`, 300ms delay
- **Respect `prefers-reduced-motion`:** All animations must be disabled when this media query is active
- **Never** use looping animations on data dashboards — they distract from information

---

## 9. Voice & Tone

### 9.1 UI Copy Rules
- Write from the user's perspective: "Your organization is operating at…" not "The system has calculated…"
- Use active voice always: "Assign Ajay" not "Ajay can be assigned"
- Be specific with numbers: "3 roles at risk" not "several roles at risk"
- AI suggestions are **suggestions**, not commands: Use "Recommend", "Consider", "Suggest" — never "You must" or "You should"
- Error messages: state what happened + how to fix it. Never say "Something went wrong."

### 9.2 Prohibited Copy Patterns
- ❌ "Leveraging synergies across the talent ecosystem"
- ❌ "Unlock your workforce potential"
- ❌ "Seamless HR experience"
- ✅ "92% of employees are meeting quarterly goals"
- ✅ "4 critical deadlines are at risk this week"
- ✅ "Reskilling in Cloud Architecture closes a 46% skill gap"

---

## 10. Accessibility

- **Minimum contrast ratio:** 4.5:1 for all body text, 3:1 for large text and UI components
- All interactive elements must have visible focus indicators (`:focus-visible` ring in `--color-accent-primary`)
- All icons used as interactive elements must have `aria-label`
- Charts must have a text-based data summary accessible to screen readers
- Color must never be the **only** indicator of status — always pair with icon or label
- Form inputs must have explicit `<label>` associations, never placeholder-only

---

## 11. Brand Consistency Checklist

Before shipping any screen or component, verify:

- [ ] Background uses `--color-bg-primary` or `--color-bg-surface` — never raw black or white
- [ ] Only `--gradient-accent` is used for the primary CTA button
- [ ] Status indicators use semantic color tokens only
- [ ] Typography uses Inter at the correct scale — no custom sizes
- [ ] Spacing follows the 8px grid
- [ ] WISE is written in ALL CAPS wherever the brand name appears
- [ ] AI suggestions use recommendation language, not directive language
- [ ] No more than one primary action button per view
- [ ] All charts have labeled axes and accessible text alternatives
- [ ] Motion is disabled when `prefers-reduced-motion` is active

---

## 12. What WISE Is NOT

To maintain brand integrity, the following are explicitly out of scope and must never appear in WISE:

- ❌ Light/white mode UI (dark theme is non-negotiable for the core product)
- ❌ Playful or rounded bubbly design elements
- ❌ Cartoon or illustrated avatars — use real profile photos or initials-based avatars
- ❌ Generic stock photography in the product UI
- ❌ Passive, vague AI output ("The team seems to be doing okay")
- ❌ Multiple competing accent colors per screen beyond the defined palette

---

*This document governs all design and development decisions for the WISE platform. Any deviation requires explicit approval from the design lead.*
