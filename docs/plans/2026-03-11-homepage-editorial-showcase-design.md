# Homepage Editorial Showcase Design

**Date:** 2026-03-11

**Goal:** Redesign the homepage into an editorial-style showcase that balances academic credibility with a stronger portfolio-driven first impression.

**Reference Direction:** [wenhaochai.com](https://wenhaochai.com/)

## Objectives

- Make the homepage feel intentionally designed rather than theme-customized.
- Put research identity and flagship work ahead of long-form profile text.
- Preserve academic trust signals without overwhelming the first screen.
- Keep the implementation maintainable within the current Hugo + PaperMod setup.

## Current Problems

- The homepage is content-rich but lacks a dominant visual focal point.
- The current layout presents all sections with similar visual weight.
- Generic glassmorphism and a full-page wallpaper create atmosphere, but not a coherent visual system.
- Important signals such as flagship projects, open-source impact, and research positioning are not front-loaded.

## Chosen Direction

The redesign will use an `Editorial Showcase` approach:

- content-led rather than effect-led
- stronger hero composition
- curated project showcase
- lighter, more deliberate supporting sections
- restrained motion and richer typography

This direction should feel like a serious research portfolio, not a generic academic homepage and not a startup landing page.

## Information Architecture

The homepage will be reorganized into five sections:

1. **Hero**
2. **Selected Works**
3. **News**
4. **Research Profile**
5. **Academic Profile**

## Section Design

### 1. Hero

**Purpose:** Establish identity, research focus, and quality bar within the first screen.

**Content:**

- Name: `Tian (Owen) YE`
- Role: `PhD Student at HKUST(GZ)`
- Research statement: concise sentence emphasizing practical, reusable generative vision research
- Tags:
  - `AIGC`
  - `Diffusion Models`
  - `Foundation Models`
- Social links
- Primary CTA: `View Publications`
- Secondary CTA: `Selected Works`

**Layout:**

- Two-column composition
- Left: identity, statement, tags, CTA, social links
- Right: stacked showcase cards rather than a plain profile image

**Showcase cards:**

- `UltraFlux`
- `LucidFlux`
- `LucidNFT`

Each card should contain a title, short label or venue, and a one-line summary.

### 2. Selected Works

**Purpose:** Present the most representative work as designed artifacts rather than raw list items.

**Initial set:**

- `UltraFlux`
- `LucidFlux`
- `LucidNFT`
- `PosterCraft`
- `MagicInfinite`

**Card contents:**

- title
- venue or tag
- one-line value statement
- external link

**Layout:**

- editorial card grid
- one featured large card
- remaining cards in supporting positions

### 3. News

**Purpose:** Keep the homepage fresh without taking over the page.

**Design:**

- compact timeline or list with date anchors
- show only recent items on the homepage
- keep styling lighter than project cards

### 4. Research Profile

**Purpose:** Replace broad bullet-heavy self-description with a more editorial narrative.

**Content direction:**

- what problems are being pursued
- how research spans generation, restoration, and deployable systems
- how academic work connects to open-source and industry translation

**Layout:**

- two-column narrative block
- one side for research story
- one side for concise supporting details

### 5. Academic Profile

**Purpose:** Preserve academic trust signals while reducing clutter.

**Content:**

- awards
- academic services
- education and experience
- mentoring

**Layout:**

- compact cards or split columns
- visually quieter than hero and selected works

## Visual Language

### Background

- remove the large photographic wallpaper from the homepage
- use a clean light editorial base with layered gradients or blurred color fields
- prioritize readability and hierarchy over decorative texture

### Color

Preferred palette direction:

- charcoal
- ivory
- muted gold or orange accent
- blue-gray or olive supporting tones

Avoid purple-heavy gradients and default dark-mode aesthetics.

### Typography

Use clearer title and body contrast:

- heading font: more expressive, editorial, or serif-leaning
- body font: clean sans-serif for readability

Suggested direction:

- headings: `Cormorant Garamond` or `Bricolage Grotesque`
- body and UI: `Manrope` or `Instrument Sans`

### Components

- reduce overuse of uniform bordered glass cards
- use different card weights for hero, project showcase, and supporting content
- rely more on spacing, scale, and contrast

### Motion

Use restrained motion only:

- staged hero entrance
- subtle hover lift for project cards
- light section reveal on scroll

Do not introduce heavy parallax, particle effects, or complex 3D interactions.

## Content Strategy

### Keep Prominent

- identity and positioning
- flagship work
- recent news
- research narrative
- academic entry points

### Down-rank

- full news archive
- long reviewer and service lists
- dense bullet blocks
- less critical supporting details

## Implementation Constraints

- Hugo remains the site generator
- PaperMod remains the base theme
- homepage becomes a custom landing page on top of the theme
- avoid framework migration
- keep the solution maintainable and fast

## Likely File Changes

- `layouts/home.html`
- `layouts/partials/home_info.html`
- new partials for homepage sections
- `assets/css/extended/custom.css`
- possible small JS enhancement for reveal behavior

## Success Criteria

- The homepage has a clear focal point and visual rhythm.
- Flagship work is visible above the fold or immediately below it.
- Academic credibility remains obvious without dominating the layout.
- The page feels custom and memorable while staying readable and maintainable.
