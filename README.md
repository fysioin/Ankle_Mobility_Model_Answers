# RGUHS MPT Paper IV - Ankle Mobility Model Answers

An interactive, accessible HTML study guide built from the **RGUHS Master of Physiotherapy (MPT)**
**Paper IV - Physiotherapy Interventions in Musculoskeletal Disorders** topic
(Q.P. Code 8132):

> **Impaired Mobility in Ankle Injuries & Evidence-Based Mobilization Management**

The whole resource is a **single self-contained HTML file** - no build step, no dependencies, no
internet connection required. Just open it in a browser.

## Files

| File | Purpose |
| --- | --- |
| `RGUHS_MPT_PaperIV_Ankle_Mobility_Study_Guide.html` | The interactive study page (open this). |
| `index.html` | Minimal landing page used by the GitHub Pages site. |
| `README.md` | This documentation. |

## Contents of the study guide

1. Pathophysiological mechanisms of impaired mobility (four pathways, with a flow diagram).
2. Osteokinematic & arthrokinematic joint deficits (comparison table).
3. Clinical assessment protocol (goniometry, posterior talar glide test, ligamentous laxity screening, sensorimotor control).
4. Evidence-based mobilization management (Maitland system; Mulligan MWM; comparison table).
5. Phased rehabilitation & sensorimotor progression (Phase 1-3, with a flow diagram).
6. High-yield clinical takeaway.
7. References.

## Components

### 1. Toolbar (sticky, top)
Minimal, monochrome by default. Contains: three highlight swatches, **Erase**, **Clear all**,
**Term notes** (toggles the popup underlines), **Night mode**, and **Fit to screen**.

### 2. Content sections (`.card > section.q`)
One `<section class="q">` per question. Each has a heading row (with its notes pill) and a body
containing the answer, tables and diagrams.

### 3. Term popups (`.term[data-note]`)
Every difficult word is wrapped in `<span class="term" data-note="...">`. Hovering or tapping shows a
plain-English definition in a floating popup. Definitions also appear in the collapsible **glossary**
at the foot of the page.

### 4. Study Notes (auto-saving)
Two synced entry points, both saved automatically in the browser:

- **Floating "Study Notes" button** (`#notesFab`, bottom-right, always visible) opens a slide-out
  drawer (`#notesDrawer`) listing every question with its own notes box. A badge shows how many
  questions have notes.
- **Notes pill on each question heading** (`.notes-toggle`) opens a notes box beside the question
  (wide screens) or under the heading (narrow screens).

### 5. Night mode
A light/dark toggle; the choice is remembered.

### 6. Fit to screen
Toggles between a comfortable reading width and full-window width; remembered between visits.

### 7. Highlighting
Select text, then click a colour swatch (yellow / green / pink). **Erase** removes highlights in the
selection; **Clear all** removes every highlight.

### Storage keys
All user data is stored locally in the browser (nothing is uploaded), namespaced so it does not mix
with other papers on the same site:

- `rguhsAnkleMob-mpt-highlights` - your highlights
- `rguhsAnkleMob-note-qN` - notes for question N
- `rguhsAnkleMob-theme` - `dark` / `light`
- `rguhsAnkleMob-fit` - `1` / `0`

## Accessibility

- Semantic headings (`h1`-`h4`), real `<table>` elements with header cells, and real lists.
- Interactive controls are native `<button>` elements with `aria-expanded` / `aria-controls` on the
  notes toggles and `aria-live` on the save status.
- Term popups are keyboard reachable (`tabindex="0"`, opened with Enter/Space, dismissed with Escape).
- Readable default font size, generous line height, and a print stylesheet.

## Sources

Definitions are written in plain English to explain the topic's terminology, drawing on standard
musculoskeletal physiotherapy references. Clinical content is referenced to Maitland's Peripheral
Manipulation, Mulligan's Manual Therapy, Hertel (2002), Verhagen et al. (2004), Vicenzino et al.
(2006), the International Ankle Consortium ROAST consensus (2018), Bleakley et al. (2012) and Nordin
& Frankel. See the References section at the foot of the study page. They are study aids, not
quotations.

## Disclaimer

Study aid only - not a substitute for clinical judgement, and not an official university marking
scheme.
