# Homepage Editorial Showcase Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Rebuild the homepage into an editorial-style research showcase with a custom hero, curated selected works, lighter news presentation, and reorganized profile sections.

**Architecture:** Keep Hugo and the PaperMod theme, but replace the current homepage composition with custom partial-driven sections. Move away from homepage-as-raw-Markdown rendering by composing explicit sections in `layouts/home.html`, while keeping content largely sourced from existing site data and controlled literals for curated highlights.

**Tech Stack:** Hugo, Go templates, PaperMod theme overrides, custom CSS, light progressive JavaScript

---

### Task 1: Freeze the current homepage structure

**Files:**
- Inspect: `/Users/owen718/Code/Owen718.github.io/layouts/home.html`
- Inspect: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_info.html`
- Inspect: `/Users/owen718/Code/Owen718.github.io/content/_index.md`
- Inspect: `/Users/owen718/Code/Owen718.github.io/assets/css/extended/custom.css`

**Step 1: Record the current homepage render sources**

Review how the homepage currently pulls hero content and body Markdown.

**Step 2: Build the site to confirm baseline**

Run: `hugo`
Expected: exit code `0`

**Step 3: Commit the planning baseline if needed**

Run:

```bash
git status --short
```

Expected: no unexpected implementation edits beyond planning docs.

### Task 2: Define homepage data and section ownership

**Files:**
- Modify: `/Users/owen718/Code/Owen718.github.io/content/_index.md`
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_selected_works.html`
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_news_timeline.html`
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_research_profile.html`
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_academic_profile.html`

**Step 1: Decide what remains in Markdown**

Reduce `content/_index.md` to only the content that should still be data-backed or rendered in later sections.

**Step 2: Write the curated section content contract**

Use explicit partials with hard-coded curated entries where appropriate rather than trying to infer all structure from Markdown.

**Step 3: Build to verify templates still compile**

Run: `hugo`
Expected: exit code `0`

**Step 4: Commit**

Run:

```bash
git add content/_index.md layouts/partials/home_*.html
git commit -m "Refactor homepage section structure"
```

### Task 3: Rebuild the hero as an editorial showcase

**Files:**
- Modify: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_info.html`
- Modify: `/Users/owen718/Code/Owen718.github.io/layouts/home.html`
- Test: `/Users/owen718/Code/Owen718.github.io/content/_index.md`

**Step 1: Replace the current hero grid**

Implement a custom hero with:

- name
- role
- research statement
- tags: `AIGC`, `Diffusion Models`, `Foundation Models`
- social links
- CTA buttons
- showcase stack on the right

**Step 2: Populate showcase cards**

Add curated hero cards for:

- `UltraFlux`
- `LucidFlux`
- `LucidNFT`

Each card should have a title, short descriptor, and external link.

**Step 3: Ensure graceful mobile stacking**

Make the hero collapse into a single-column layout on narrow screens.

**Step 4: Build to verify output**

Run: `hugo`
Expected: exit code `0`

**Step 5: Commit**

Run:

```bash
git add layouts/home.html layouts/partials/home_info.html
git commit -m "Build editorial homepage hero"
```

### Task 4: Implement the Selected Works section

**Files:**
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_selected_works.html`
- Modify: `/Users/owen718/Code/Owen718.github.io/layouts/home.html`

**Step 1: Build a curated editorial grid**

Render cards for:

- `UltraFlux`
- `LucidFlux`
- `LucidNFT`
- `PosterCraft`
- `MagicInfinite`

**Step 2: Make one card visually dominant**

Use a larger featured card for the strongest anchor project.

**Step 3: Add external links and supporting metadata**

Each card should include a short line for venue, release type, or research category.

**Step 4: Build to verify output**

Run: `hugo`
Expected: exit code `0`

**Step 5: Commit**

Run:

```bash
git add layouts/home.html layouts/partials/home_selected_works.html
git commit -m "Add curated selected works section"
```

### Task 5: Redesign News into a lighter timeline

**Files:**
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_news_timeline.html`
- Modify: `/Users/owen718/Code/Owen718.github.io/layouts/home.html`
- Modify: `/Users/owen718/Code/Owen718.github.io/content/_index.md`

**Step 1: Limit homepage news count**

Show only the most recent 6 to 8 items.

**Step 2: Render dates as anchors**

Separate date labels from body text to create a cleaner timeline rhythm.

**Step 3: Preserve existing links**

Ensure all current linked news items still render with correct targets.

**Step 4: Build to verify output**

Run: `hugo`
Expected: exit code `0`

**Step 5: Commit**

Run:

```bash
git add layouts/home.html layouts/partials/home_news_timeline.html content/_index.md
git commit -m "Convert homepage news into timeline layout"
```

### Task 6: Rework profile sections into narrative and credentials blocks

**Files:**
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_research_profile.html`
- Create: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_academic_profile.html`
- Modify: `/Users/owen718/Code/Owen718.github.io/layouts/home.html`
- Modify: `/Users/owen718/Code/Owen718.github.io/content/_index.md`

**Step 1: Extract and condense research narrative**

Rewrite homepage-facing profile text into concise editorial paragraphs.

**Step 2: Split credentials into a quieter supporting section**

Group awards, academic services, education, and mentoring into compact blocks.

**Step 3: Keep the homepage scannable**

Avoid long undifferentiated bullet walls.

**Step 4: Build to verify output**

Run: `hugo`
Expected: exit code `0`

**Step 5: Commit**

Run:

```bash
git add layouts/home.html layouts/partials/home_research_profile.html layouts/partials/home_academic_profile.html content/_index.md
git commit -m "Refine homepage profile and credentials sections"
```

### Task 7: Replace the current CSS with a coherent editorial system

**Files:**
- Modify: `/Users/owen718/Code/Owen718.github.io/assets/css/extended/custom.css`

**Step 1: Remove homepage wallpaper-first styling**

Drop the current full-page photo wallpaper treatment for the homepage.

**Step 2: Define homepage design tokens**

Add CSS variables for:

- background layers
- text hierarchy
- accents
- borders
- shadows
- card fills

**Step 3: Style each section intentionally**

Add section-specific styles for:

- hero
- showcase cards
- selected works grid
- news timeline
- research profile
- academic profile

**Step 4: Add responsive behavior**

Verify desktop and mobile layouts both hold together.

**Step 5: Build to verify output**

Run: `hugo`
Expected: exit code `0`

**Step 6: Commit**

Run:

```bash
git add assets/css/extended/custom.css
git commit -m "Apply editorial homepage visual system"
```

### Task 8: Add light progressive motion

**Files:**
- Modify: `/Users/owen718/Code/Owen718.github.io/layouts/partials/extend_head.html`
- Modify: `/Users/owen718/Code/Owen718.github.io/assets/css/extended/custom.css`

**Step 1: Add minimal JS hooks if needed**

Use lightweight DOM-based reveal behavior only if CSS alone is insufficient.

**Step 2: Respect reduced-motion users**

Gate nonessential motion behind `prefers-reduced-motion`.

**Step 3: Keep interactions subtle**

No heavy parallax, no particle effects, no long-running animations.

**Step 4: Build to verify output**

Run: `hugo`
Expected: exit code `0`

**Step 5: Commit**

Run:

```bash
git add layouts/partials/extend_head.html assets/css/extended/custom.css
git commit -m "Add subtle homepage motion"
```

### Task 9: Verify the redesign end-to-end

**Files:**
- Verify: `/Users/owen718/Code/Owen718.github.io/layouts/home.html`
- Verify: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_info.html`
- Verify: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_selected_works.html`
- Verify: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_news_timeline.html`
- Verify: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_research_profile.html`
- Verify: `/Users/owen718/Code/Owen718.github.io/layouts/partials/home_academic_profile.html`
- Verify: `/Users/owen718/Code/Owen718.github.io/assets/css/extended/custom.css`

**Step 1: Run static build**

Run: `hugo`
Expected: exit code `0`

**Step 2: Run local preview**

Run: `hugo server --bind 127.0.0.1 --port 1313`
Expected: homepage renders without template errors

**Step 3: Spot-check key content**

Verify:

- hero tags are correct
- selected works links resolve
- latest news items render
- mobile layout stacks correctly

**Step 4: Commit final polish**

Run:

```bash
git add layouts/home.html layouts/partials assets/css/extended/custom.css content/_index.md
git commit -m "Finalize homepage editorial redesign"
```
