---
name: The Franchise OG
description: A signed letter from a franchising veteran, set in navy, brass and warm paper.
colors:
  boardroom-navy: "#14233A"
  boardroom-navy-raised: "#1E3150"
  watch-brass: "#C4953F"
  watch-brass-bright: "#D3A85A"
  watch-brass-deep: "#7D5A1C"
  parchment: "#F8F4EC"
  sand: "#ECE3D2"
  stone: "#5F5A51"
  rule-light: "#DDD2BE"
  rule: "#8A7F6D"
  white: "#FFFFFF"
typography:
  display:
    fontFamily: "Fraunces, Georgia, 'Times New Roman', serif"
    fontSize: "64px"
    fontWeight: 600
    lineHeight: "70px"
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Fraunces, Georgia, 'Times New Roman', serif"
    fontSize: "40px"
    fontWeight: 600
    lineHeight: "48px"
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Fraunces, Georgia, 'Times New Roman', serif"
    fontSize: "28px"
    fontWeight: 600
    lineHeight: "34px"
  stat:
    fontFamily: "Fraunces, Georgia, 'Times New Roman', serif"
    fontSize: "56px"
    fontWeight: 700
    lineHeight: "64px"
    letterSpacing: "-0.01em"
    fontFeature: "tnum"
  signoff:
    fontFamily: "Fraunces, Georgia, 'Times New Roman', serif"
    fontSize: "26px"
    fontWeight: 600
    lineHeight: "34px"
  lead:
    fontFamily: "'Source Sans 3', 'Source Sans Pro', system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: "34px"
  body:
    fontFamily: "'Source Sans 3', 'Source Sans Pro', system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: "28px"
  label:
    fontFamily: "'Source Sans 3', 'Source Sans Pro', system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: "20px"
rounded:
  btn: "4px"
  photo: "16px"
spacing:
  gutter: "24px"
  gap: "30px"
  pad-stats: "64px"
  pad-section: "96px"
  pad-hero: "128px"
  container: "1170px"
components:
  button-primary:
    backgroundColor: "{colors.watch-brass}"
    textColor: "{colors.boardroom-navy}"
    typography: "{typography.label}"
    rounded: "{rounded.btn}"
    padding: "16px 28px"
  button-primary-hover:
    backgroundColor: "{colors.watch-brass-bright}"
    textColor: "{colors.boardroom-navy}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.parchment}"
    typography: "{typography.label}"
    rounded: "{rounded.btn}"
    padding: "12px 22px"
  button-secondary-hover:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.boardroom-navy}"
  photo:
    backgroundColor: "{colors.boardroom-navy-raised}"
    rounded: "{rounded.photo}"
  stats-bar:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.boardroom-navy}"
    padding: "64px 0"
---

# Design System: The Franchise OG

## Overview

**Creative North Star: "The Founder's Letter"**

The page reads like a personal letter from someone who has been in the business longer than almost anyone. Fraunces serif headlines speak in his voice, the body copy is set in plain, generous Source Sans, and the letter is signed in italic: *Sincerely, The Franchise OG*. Warm paper surfaces (parchment and sand) carry the reading. Boardroom navy frames the opening and the close like a suit jacket, and a single brass accent, the watch in the hero photo, marks the one action that matters.

Density is low and the pace is unhurried. Each section is a full-width band with one idea, set on a 12-column-equivalent grid inside a 1170px container. Structure comes from hairline rules and ruled rows, the way a ledger or a letterhead would organize a page, not from cards, shadows, or icons. Nothing is decorated for its own sake; authority comes from restraint.

**Key Characteristics:**
- Navy bookends (header, hero, final CTA) around alternating parchment and sand reading bands.
- One brass accent, reserved for the primary booking action and small step labels.
- Serif voice for every heading, stat and the sign-off; sans for everything people read at length.
- Hairline rules and ruled rows instead of cards and boxes.
- Flat surfaces; the only shadow is a hover response on the primary button.

## Colors

A two-temperature palette: cool boardroom navy for authority, warm paper and brass for the personal voice.

### Primary
- **Boardroom Navy** (`boardroom-navy`): the page's ink. Headings and the About letter on light bands, and the full background of the header, hero and final CTA. The topic dividers are 2px rules in this color.
- **Boardroom Navy Raised** (`boardroom-navy-raised`): one step lighter. The header's bottom border and the hero photo's loading background. Use it to separate surfaces inside a navy band, never as a new band color.

### Secondary
- **Watch Brass** (`watch-brass`): the call-to-action color. Fills the primary booking button and serves as the focus ring inside navy bands. Never used for text on light backgrounds; it fails contrast there.
- **Watch Brass Bright** (`watch-brass-bright`): primary button hover only.
- **Watch Brass Deep** (`watch-brass-deep`): the readable brass for light surfaces. Step labels, footer links and the default focus ring.

### Neutral
- **Parchment** (`parchment`): the main reading surface and the text color inside navy bands.
- **Sand** (`sand`): the alternate band (stats, call topics, steps) and the footer. It alternates with parchment so sections separate without borders.
- **Stone** (`stone`): supporting body copy on light bands, stat labels and footer text.
- **Rule** (`rule`): ruled rows, stat dividers and list borders.
- **Rule Light** (`rule-light`): the quieter footer divider.
- **White** (`white`): hero headline and final CTA text only, so they sit a touch brighter than the parchment body copy around them.

### Named Rules
**The One Brass Button Rule.** Watch Brass fills exactly one kind of element: the primary "Book your free call" button. If something else needs emphasis, use type or a rule, not brass.

**The Bookend Rule.** Navy appears only at the top (header and hero) and the bottom (final CTA). Everything between is parchment or sand, alternating band by band.

## Typography

**Display Font:** Fraunces (with Georgia, Times New Roman, serif), weights 600 and 700, plus italic 600, with optical sizing on.
**Body Font:** Source Sans 3 (with Source Sans Pro, system-ui, sans-serif), weights 400, 600 and 700.

**Character:** Fraunces gives the founder a voice: warm, a little old-school, confident. Source Sans keeps the explanations plain and easy to read, the way he talks.

### Hierarchy
- **Display** (600, 64px / 70px; 38px / 44px on mobile): the hero headline only. The second half of the line switches to italic for emphasis.
- **Headline** (600, 40px / 48px; 30px / 36px on mobile): section titles. The final CTA title runs larger (48px / 56px; 34px / 40px on mobile).
- **Title** (600, 28px / 34px; 22px / 28px on mobile): row and step headings. Topic headings use 24px / 30px; FAQ questions use 22px / 28px.
- **Stat** (700, 56px / 64px, tabular numbers; 44px / 52px on mobile): the credibility figures, which count up once on scroll unless the visitor prefers reduced motion.
- **Signoff** (600 italic, 26px / 34px): the letter's signature in About.
- **Lead** (400, 21px / 34px; 18px / 30px on mobile): the About letter body, set in navy rather than stone because it is his own voice.
- **Body** (400, 18px / 28px; 16px / 26px on mobile): all other running text, max 68ch.
- **Label** (600, 16px / 20px): buttons and step labels ("Step 1").

### Named Rules
**The Serif Speaks Rule.** Fraunces is used for headings, figures and the signature. It is never used for body paragraphs, buttons or labels.

**The Italic Is Earned Rule.** Italic appears in two places: the emphasized half of the hero headline and the sign-off. Don't add more.

## Layout

- **Container:** 1170px max width with 24px gutters (16px on mobile) and a 30px column gap.
- **Bands:** every section is a full-width band. Vertical padding is 128px for the hero and final CTA (72px on mobile), 96px for reading bands (64px on mobile), and 64px for the stats bar.
- **Grid ratios** come from a 1170px, 12-column grid:
  - Hero: 670 / 470 (copy and photo).
  - Split sections, used for "who I help" and the FAQ: 370 / 770, with the heading on the left and ruled rows on the right.
  - Final CTA: 770 / 370, with the button aligned to the end.
  - Topics: 2 equal columns. Stats and steps: 3 equal columns.
- **Text measure:** section titles are capped at 770px, the About letter at 770px, and paragraphs at 68ch.
- **Responsive:** from 768px to 1099px, each stat label sits below its figure. At 767px and below, every grid collapses to one column, the stats stack with horizontal rules between them, and the primary button goes full width.

## Elevation & Depth

Flat by default. Depth comes from color temperature (navy bookends against warm paper bands) and from alternating parchment and sand, never from layered surfaces.

### Shadow Vocabulary
- **Brass lift** (`box-shadow: 0 6px 16px rgba(20, 35, 58, 0.28)`): primary button hover only.

### Named Rules
**The Flat Page Rule.** Nothing on the page casts a shadow at rest. The single permitted shadow is a hover response on the primary button.

## Shapes

Nearly square. Buttons get a barely-there 4px corner, and photos get a softer 16px corner, the only rounded surface on the page. Lines do the structural work: 1px rules (`rule`) between rows and stats, and a heavier 2px navy rule over each call topic. There are no pills, circles or icons.

## Components

### Buttons
Tailored and plain, like a well-cut suit.
- **Shape:** gently squared corners (4px), with a 2px border on every variant so sizes stay consistent.
- **Primary:** Watch Brass fill, navy label text, Source Sans 600 at 16px, 16px × 28px padding. On mobile it is full width and centered.
- **Hover / Focus:** hover brightens the fill to Watch Brass Bright and adds the brass lift shadow; color transitions take 0.15s ease. Focus shows a 3px outline with a 2px offset, Watch Brass on navy bands and Watch Brass Deep elsewhere.
- **Secondary (header only):** a transparent outline button in the surrounding text color (parchment on navy), padded 12px × 22px. On hover it fills with parchment and the text turns navy.

### Ruled Rows (signature)
Used in the "who I help" list and the FAQ, like lines in a ledger. Each row sits between 1px Rule borders, with 32px vertical padding (28px for FAQ rows, 24px on mobile). "Who I help" rows set a 240px serif title column beside the description; FAQ rows stack the question over its answer.

### Topic Blocks
The four call topics sit in a two-column grid. Each opens with a 2px navy rule, then 24px of space, a 24px serif title and a stone-colored description.

### Stats Bar
A sand band with three figures in a row. Each is a large tabular Fraunces numeral, its baseline aligned with a stone label, separated by 1px vertical rules (horizontal rules on mobile).

### Photo
Framed with 16px corners at a 4:5 aspect ratio and cropped with `object-fit: cover`. It shows the hero subject only and should never become a decorative stock image.

### Browser Surfaces
Headings use balanced wrapping and paragraphs use pretty wrapping. Text selection is navy with parchment text on light bands, and the reverse inside navy bands.

### Navigation
There is no navigation menu. The header holds only the wordmark (200px wide, 160px on mobile) linking to the main content, and the secondary "Book a call" button.

### Footer
A sand band in 16px stone text. The wordmark (180px) and links in Watch Brass Deep, underlined, that turn navy on hover. Below a Rule Light divider sit the franchise disclaimer and the copyright.

## Do's and Don'ts

### Do:
- **Do** keep navy for the bookends and alternate parchment and sand for every band between them.
- **Do** use Watch Brass Deep for any brass-colored text on a light surface, because it meets contrast and plain Watch Brass does not.
- **Do** separate content with 1px rules and ruled rows before you reach for any container.
- **Do** set every heading, figure and the signature in Fraunces 600 or 700, and everything else in Source Sans.
- **Do** guard any new motion behind `prefers-reduced-motion`, as the stat count-up does.

### Don't:
- **Don't** put Watch Brass on anything except the primary booking button and focus rings on navy.
- **Don't** add drop shadows, cards with backgrounds, or floating panels. The page is flat and ruled.
- **Don't** round anything beyond 4px for controls or 16px for photos, and don't use pill shapes.
- **Don't** add icons, badges or decorative illustrations; the voice and the photo carry the page.
- **Don't** introduce a third background color for reading bands.
