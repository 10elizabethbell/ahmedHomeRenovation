---
name: Ahmed Home Renovation (A.H.R)
description: Walls done right in Windsor. Their own painted room under a navy veil, calm paper and navy bands, one gold thing to do.
colors:
  navy: "#1f3f6e"
  deep-navy: "#10233f"
  ink: "#10233f"
  hallway-gold: "#f2b84b"
  hallway-gold-light: "#f6ca72"
  gold-ink: "#8a5a00"
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  body-text: "#2a3a4c"
  soft-text: "#4a5868"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d6e8"
  hairline: "rgba(16,35,63,.12)"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(44px, 13vw, 84px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  headline-phone:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "normal"
  title-row:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.6vw, 24px)"
    fontWeight: 400
    lineHeight: 1.2
  title-card:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  title-link:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(19px, 5.2vw, 21px)"
    fontWeight: 400
    lineHeight: 1.2
  title-step:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  title-step-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.2
  title-message:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.3
  numeral:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.3
  phone-header:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  phone-header-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  input:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.4
  message:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
  note:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
rounded:
  field: "10px"
  panel: "16px"
  link-row: "20px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter-phone: "20px"
  gutter-desktop: "40px"
  section-phone: "64px"
  section-desktop: "96px"
  column-gap: "64px"
  row-column-gap: "48px"
  tight: "8px"
  control-gap: "10px"
  action-gap: "12px"
  stack: "16px"
  field-gap: "20px"
  item-gap: "24px"
  block-gap: "28px"
components:
  button-primary:
    backgroundColor: "{colors.hallway-gold}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.hallway-gold-light}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.title-row}"
    padding: "14px 0"
    height: "72px"
  row-arrow-hover:
    backgroundColor: "{colors.hallway-gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  claim-list:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.title-card}"
    padding: "16px 0"
  link-row:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-dark}"
    typography: "{typography.title-link}"
    rounded: "{rounded.link-row}"
    padding: "14px 16px 14px 22px"
    height: "76px"
  work-photo:
    rounded: "{rounded.card}"
    width: "460px"
  step-marker:
    backgroundColor: "{colors.hallway-gold}"
    textColor: "{colors.ink}"
    typography: "{typography.numeral}"
    rounded: "{rounded.circle}"
    size: "48px"
  form-card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
    width: "600px"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.input}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  message-panel:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.title-message}"
    rounded: "{rounded.panel}"
    padding: "18px"
  message-output:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    typography: "{typography.message}"
    rounded: "{rounded.field}"
    padding: "12px 14px"
  float-circle:
    backgroundColor: "{colors.hallway-gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
  header:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    height: "64px"
---

# Design System: Ahmed Home Renovation (A.H.R)

## Overview

**Creative North Star: "The Clean Room They Leave Behind"**

The site is a painting and drywall crew's first front door: a Windsor business with no web presence until now, shown as calm and orderly as a freshly painted room. It follows Ellie's calm band house style (after lpmr.co.uk, by way of the DPG build): off-white paper bands alternating with painter's-tape navy and a deep navy, soft rounded surfaces, pill buttons, and Cal Sans at its single regular weight. The one image is their own: the taupe room from their Facebook post, with tape on the baseboard and the floor covered, sitting under a deep navy veil behind the hero headline and again, unveiled, beside their promises.

Density is low and the voice is plain. Each band carries one heading, one quieter line and at most two actions. Hallway-light gold is the only warm colour and works as a fill for the thing to do (the estimate button, step numerals, the floating circle); on dark grounds a short closing phrase of a heading turns gold ("Windsor.", "do.", "works."). Their own promises sit in a plain divided list on paper. Bands meet on straight edges; the only texture anywhere is the faint 135° line on the deep navy grounds.

The contact system is built around an unknown: the business has no published phone. Every contact point is wired to one `CONFIG` object, so the page ships Facebook-first and switches to call and text the moment `CONFIG.PHONE` is set, without anyone touching the markup.

**Key Characteristics:**
- Three grounds: paper, navy (plain) and deep navy (faint 135° line texture); the hero is the client's photo under a deep navy veil.
- Gold as a fill (buttons, step numerals, float circle, arrow wells on hover); gold-ink only when gold must be a glyph on light.
- Cal Sans at weight 400 for every heading, button, label and phone line; system sans body at 16px/1.7.
- Generous rounding: 24px cards and photo, 999px pills, 10px fields, circles for markers.
- Near-flat: tone does the layering; the only shadows are the form card's whisper and the floating circle.
- One config switch drives every contact point: Facebook message until there is a phone, call and text after.
- Tap targets 44px minimum, buttons 56px, reading text 16px or larger.

## Colors

A cool, calm palette: off-white paper and two painter's-tape navies, warmed by a single hallway-light gold.

### Primary
- **Painter's-Tape Navy** (`navy`): ground of the services band and the closing band (both plain, no texture); fill of the Facebook link row on paper. Also the form's hover and focus colour (the `--focus` role: field and chip borders, 3px rings, the 2px submit outline), the caret in fields, the Facebook glyph in the header slot, and the page scrollbar thumb.
- **Deep Navy** (`deep-navy`): ground of the How-it-works band and the footer, always with the line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`), and the base under the hero photo and its veil. Same hex as Ink; the two names separate the ground role from the text role.

### Secondary
- **Hallway Gold** (`hallway-gold`): fill of the primary button, the step numerals, the floating circle and the arrow wells on hover or focus; `::selection`; the focus ring on dark grounds. On dark grounds it is also the accent phrase in a heading, the closing phone glyph and link hovers (5.9:1 on navy, 8.8:1 on deep navy).
- **Hallway Gold Light** (`hallway-gold-light`): primary button hover fill only.
- **Gold Ink** (`gold-ink`): gold when it has to be a glyph or text on light (5.5:1 on paper): the claim-list icons, the header phone glyph and the header phone hover colour.

### Neutral
- **Paper** (`paper`): page ground, header ground, `theme-color`.
- **Card** (`card`): the form card, the composed-message box, the line button's fill, selected-chip text.
- **Field** (`field`): fill of text fields, chips and the message panel inside the white card. It reads as a tone (1.19:1 against white), so fields are identified by their labels and fill, not by an edge.
- **Ink** (`ink`): headings, labels and claim titles on light; text on gold; the selected chip fill; the line button's border.
- **Body Text** (`body-text`): running text on light.
- **Soft Text** (`soft-text`): ledes, "(optional)", the note under the submit button, the wordmark subline. Placeholders run a touch darker (`#56657a`, 5.0:1 on the field fill).
- **On-Dark** (`on-dark`): headings, service rows, step titles, the hero promise, ghost-button label and footer links on navy grounds. The hero H1 itself is pure white.
- **On-Dark Soft** (`on-dark-soft`): running text and ledes on navy grounds.
- **Hairline** (`hairline`): dividers between claim rows on paper. On navy the service rows divide with white at 14% instead.
- **Error Red** (`error-red`): field error border and the 16px error sentence, on the white card.

Translucent tints are derived, not tokens: arrow wells at rest are white at 10% (services) or 14% (Facebook row), the ghost border is on-dark at 70%, the ghost hover wash is white at 10%, and the hero veil is deep navy at 74–90%.

### Named Rules
**The Gold Is A Fill Rule.** Hallway gold appears as a filled shape or, on navy grounds, as type and glyphs. On paper or white it is never text; use gold-ink there.

**The Accent On Dark Rule.** An accent phrase in a heading is gold, is the heading's last word or two, and appears only on the hero, navy or deep grounds. Headings on paper stay all ink.

**The Navy Focus Rule.** On light grounds hover and focus use navy: a 3px ring at a 3px offset, fields and chips switching their 2px border to navy, and buttons inside the form card taking a 2px navy outline at 2px. On navy grounds the ring turns gold. A gold-filled control is never outlined in gold on light.

## Typography

**Display Font:** Cal Sans (Google Fonts, preconnected, `display=swap`), falling back to Avenir Next, Segoe UI, system-ui
**Body Font:** system sans stack (-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif)
**Label/Mono Font:** none distinct; phone numbers tighten Cal Sans' wide word space with `word-spacing: -0.15em` and use proportional figures

**Character:** A rounded, geometric display face at its single regular weight, in sentence case with a hair of negative tracking, beside a plain native body face set loose and readable. Friendly and steady, never shouty.

### Hierarchy
- **Display** (`display`): the hero headline only, white, broken into three short lines, its last word in gold.
- **Headline** (`headline`): section headings, balanced wrap. The closing phone number (shown only once a phone is set) runs at `headline-phone`.
- **Title**: service rows on navy (`title-row`), claim labels on paper (`title-card`), the Facebook link row (`title-link`), step titles on deep navy (`title-step`, `title-step-desktop` from 1024px), and the composed-message heading (`title-message`).
- **Button / Label / Phone**: Cal Sans at 18px for buttons, form labels and legends, and the header slot (20px from 760px); 20px for step numerals.
- **Promise / Lede** (system face): the hero promise line (max 28ch on phones), and the line under each heading (max 40ch).
- **Body** (`body`): everything else; `input` sets field text at 16px/1.4 and `message` sets the composed message at 16px/1.5.
- **Note** (`note`, 16px, soft colour): the line under the submit button and field error sentences. The "(optional)" marker is 14px.

### Named Rules
**The One Weight Rule.** Cal Sans is only ever weight 400 and sentence case. Hierarchy comes from size, colour and ground, never from bolding or uppercase. The only bold is 600-weight in body copy ("Where we work:", the post-send status line).

**The Sixteen Floor Rule.** Reading text and form inputs are 16px or larger (no iOS zoom). Only the 14px "(optional)" marker, the 14px eyebrow and the 12px wordmark subline are smaller, and none carries the main message.

**Not part of the system.** The build carries two small pill labels above headings (hero: "Free estimates, no obligation"; form: "Windsor and area"). They are Ellie's deliberate house choice under the calm band style and stay on this page, but they conflict with the Impeccable floor, so their 14px/500 style and tinted fills are kept off the token set: the house style file decides where they go, and this system does not propagate them to new surfaces. The wordmark's sizes (22px, 26px from 760px; 12px uppercase subline) are drawing values for the lockup, not label styles to reuse.

## Layout

A single centred column (max 1160px) with 20px gutters on phones and 40px from 760px. Bands are padded 64px top and bottom on phones and 96px from 760px.

Band order: paper header, photo hero under a deep navy veil, plain navy services, paper care, textured deep How-it-works, paper form, plain navy close, textured deep footer. Bands meet on straight edges with no dividers.

The hero on phones nearly fills the first screen (minimum `min(560px, 100svh - 64px)`, content centred, 56px top and 64px bottom padding) with the tall crop of the photo set at 50% 40% under a vertical veil. From 760px it sizes to its content (112px top, 120px bottom) with the wide crop under a left-to-right veil that clears toward the right so the room shows beside the copy. 20px separates eyebrow, headline, promise and actions; phone buttons stack full width with a 12px gap, and from 760px sit in a row at 240px minimum each.

From 760px the service rows go two columns with a 48px column gap. From 1024px: the care band becomes two columns with a 64px gap (intro, claims and Facebook row on the left; the photo spans the right column at full height); the form band runs 1fr / 1.2fr with a 64px gap; the steps become three columns with a 40px gap; the closing band puts the business name and area beside the phone number, bottom-aligned with a 48px gap. The footer is padded 48px top and 96px plus the bottom safe area below, clearing the floating circle.

Rhythm inside bands: 16px between heading and lede; 28–36px to the list, steps, photo or form; 20px between form fields and 8px from label to field; 24px between steps. Below 380px chip padding tightens from 18px to 14px.

### Named Rules
**The Number Top-Right Rule.** The header's top-right slot is the only contact point on the first screen. Under the hero headline there are at most two buttons (the gold estimate button and a ghost "see what we do"), and neither is a Call button. Once a phone exists it appears in the header, the closing band and the footer, nowhere else.

**The One Circle Rule.** The only fixed element is a single 60px gold circle, bottom-right with 16px plus safe-area insets. It appears after the hero leaves view and hides while the form is on screen. Never a sticky bottom bar.

**The One Photo Behind Text Rule.** The client's own photo under the deep navy veil is the only image behind text, and only in the hero. Everywhere else nothing runs behind copy except the faint 135° lines on the deep navy grounds; bands never join with divider shapes or curves.

## Elevation & Depth

Near-flat. Tone does the layering: the white card sits on paper, fields and the message panel sit back into the card on the field tint, and the deep grounds get a whisper of texture from the 135° lines. Two shadows exist, both soft and ambient, never structural.

### Shadow Vocabulary
- **Card whisper** (`box-shadow: 0 12px 32px rgba(16,35,63,.06)`): the form card on paper only.
- **Float** (`box-shadow: 0 10px 28px rgba(8,24,46,.3)`): the floating circle, because it rides over every ground.

### Named Rules
**The Two Shadows Rule.** The form card and the floating circle are the only shadowed elements. Buttons, chips, fields, rows and the photo get tone, never shadow, and no shadow appears on hover.

## Shapes

Soft and generous. The form card and the work photo take 24px corners; the Facebook row a slightly tighter 20px; the composed-message panel 16px; text fields and the message box 10px. Buttons and chips are full pills (999px). Circles mark three roles: step numerals (48px), arrow wells (44px) and the floating circle (60px). Borders are 2px where they appear (button outlines, field and chip borders, transparent at rest so focus never shifts layout); divider rules are 1px hairlines. Focus rings are 3px at a 3px offset (2px/2px for buttons inside the form card).

Off-system by design: the focus ring's 6px corner, a softening of the browser outline rather than a surface radius.

## Components

### Buttons
Big, round and thumb-sized.
- **Shape:** pill (999px), 56px minimum height, 26px side padding, 2px border, Cal Sans 18px label, optional 20px line icon with a 10px gap.
- **Primary:** gold fill and border, ink label. Full width inside the form.
- **Hover / Focus:** hover (pointer devices only) lightens to gold-light over 0.2s; press scales to 0.98 (0.12s). Focus is the gold ring on navy grounds; inside the form card buttons take a 2px navy outline at 2px offset on hover and focus.
- **Ghost:** transparent with a 2px on-dark border at 70% and an on-dark label; hover turns the border white and adds a 10% white wash. The hero's second action only.
- **Line:** white fill, 2px ink border, ink label. The quiet action in the form: "Copy message", and the submit button once a message is composed ("Update my message").

### Service Rows
Each service is a whole-row link on navy: a Cal Sans title, a 44px circular arrow well pushed right, 72px minimum height, 1px white-at-14% dividers between rows (above every row in the two-column layout).
- **Hover:** only the arrow well changes, to a gold fill with ink arrow. The row never gets an outline, tint or shadow.
- **Focus:** the row's ring is suppressed; the arrow well fills gold and takes a 3px gold ring at 3px.
- **Behaviour:** tapping a row jumps to the form and pre-selects the matching job chip.

### Claim List
Their own promises, plainly: a 40px gold-ink line icon and a Cal Sans title per row, 16px vertical padding, hairline dividers. No card, no fill, so it never reads as tappable next to the Facebook row.

### Work Photo
The client's own job photo at 4:5, `object-fit: cover`, 24px corners, max 460px on phones; from 1024px it fills the care band's right column. Real alt text describing the room.

### Link Row (Facebook)
A navy row on paper with 20px corners, 76px minimum height, a 28px white Facebook glyph, a Cal Sans label and a 44px arrow well (white at 14%) pushed right.
- **Hover:** only the arrow well changes, to gold.
- **Focus:** the row's ring is suppressed; the arrow well fills gold and takes a 3px navy ring at 3px.

### Steps
A numbered list on deep navy. Each item has a 48px gold circle holding a Cal Sans 20px ink numeral, then an on-dark Cal Sans title and an on-dark-soft detail line. Static; no cards, no connectors.

### Inputs / Fields
Inside a white form card (24px corners, 20–32px padding, max 600px, the card whisper shadow).
- **Style:** tinted fields: field fill, ink 16px text, 2px transparent border, 10px corners, 13px/14px padding, 52px minimum height (textarea 120px, vertical resize). Labels sit above in Cal Sans 18px; "(optional)" is a 14px soft note. Every field has a linked label, `autocomplete` where it applies, and `dir="auto"`.
- **Hover / Focus:** the border turns navy (0.15s). No ring on fields; the border is the focus.
- **Error:** border turns error red, including while focused, and a plain 16px red sentence appears below ("Add your name so we know who's asking."). Errors clear as soon as the visitor types; submit focuses the first bad field.

### Chips (form choices)
Radio choices as 48px pills on the field fill, 18px side padding, 16px ink system text, 2px transparent border.
- **Selected:** ink fill, white label.
- **Hover / Focus:** navy border; a selected chip's focus is a 3px navy outline at 3px offset, since a navy border would vanish on the ink fill. Chips exist only as real form controls.

### Navigation (Header)
A paper bar, 64px tall (76px from 760px), respecting the top safe area. Left: the A.H.R wordmark lockup (Cal Sans initials over a small uppercase soft-text company line), linking to the top. Right: the contact slot (see Contact System). No menu. The footer, on textured deep navy, repeats the business name and town, the number once one exists, and a Facebook link (44px targets, gold on hover).

### Contact System
One `CONFIG` object holds every contact detail (`PHONE`, `PHONE_DISPLAY`, `FB`, `GREETING`, `FLOAT`); no number, link or greeting is written anywhere else. Every Facebook link carries `data-fb` and takes its URL from `CONFIG.FB` on load.

- **Without a phone (`CONFIG.PHONE` empty, as shipped):** the header slot is a "Facebook" link with a navy Facebook glyph and normal word spacing. The closing phone and the footer number stay hidden. The floating circle goes to the form ("Get a free estimate", chat glyph). The submit button reads "Write my message", with the note "We'll write it out for you to send on Facebook."
- **Facebook-message fallback:** on submit the form composes the message (greeting, name, job, their description, town) into a field-tinted panel (16px corners, 18px padding) titled in Cal Sans 19px, with the text in a white, select-all box. Below it, a line button "Copy message" and a gold "Open our Facebook post" button side by side from 760px, and the note "Paste it in a private message, not a public comment." The submit button drops to the line style and reads "Update my message"; the panel scrolls into view (instantly under reduced motion). Copy uses the clipboard API with a selection fallback, because Facebook's in-app browser can block it; the button confirms for 2.4s ("Copied. Now open Facebook and paste it.") or says to select the text, and the message stays selectable either way. Without JS, a plain line points to Facebook.
- **With a phone (`CONFIG.PHONE` set):** one switch turns every contact point to call or text. The header slot becomes the tap-to-call number in Cal Sans with a gold-ink phone glyph, hover gold-ink; the closing band shows the big number (`headline-phone`, gold glyph, hover gold); the footer appends the number; the floating circle opens a pre-filled `sms:` ("Text us"). The submit button reads "Text this to us" and opens the visitor's messages with the composed text; if nothing opens within 0.9s, a status line offers the number to call.
- **Number set:** phone numbers carry `word-spacing: -0.15em` and stay on one line; check the rendered number when the real one arrives.

### Floating Circle
A 60px gold circle with a 26px ink chat glyph and the float shadow. It slides up from 120px below the viewport (0.35s, `cubic-bezier(.2,.8,.2,1)`) once the hero is out of view and slides away while the form is visible; when hidden it is `aria-hidden` and out of the tab order. `CONFIG.FLOAT = false` removes it. Focus ring is navy, circular.

### Fade-Up
The single scroll motion: elements that start below the first screen rise 12px and fade in over 400ms ease-out as they enter. Everything above the fold, without JS, and under reduced motion is visible at rest. Smooth scroll is on, off under reduced motion; there is no ambient motion.

### Hero Headline Bounce-In
The hero H1 only (after lpmr.co.uk, Ellie's house choice): on load, JS splits it into letters inside nowrap word wrappers, keeping the gold accent span. Each letter slides in from 50px right and fades in over 1s on `cubic-bezier(.34,1.56,.64,1)` (a slight overshoot), 20ms apart. The H1 carries an `aria-label` with the full text and the letter wrappers are `aria-hidden`. When the last letter lands the plain heading is restored, so kerning and selection come back. Without JS or under reduced motion the plain heading shows at once. Never put it on other headings.

## Do's and Don'ts

### Do:
- **Do** alternate paper with navy and deep navy bands (deep navy carries the faint line texture, navy stays plain) and let them meet on a straight edge.
- **Do** keep the client's own photo in the hero under the deep navy veil, cropped separately for tall and wide screens with `object-fit: cover`.
- **Do** use hallway gold as a fill for the primary action, step numerals, arrow wells and the float circle, and gold-ink (`#8a5a00`) when gold must be a glyph on light.
- **Do** set every heading, button, label and phone line in Cal Sans at weight 400, sentence case.
- **Do** put the form in a white 24px card on paper with field-tinted inputs, and the claims in a plain divided list; keep buttons and chips as full pills.
- **Do** route every contact point through `CONFIG` and keep the Facebook-message path working until `CONFIG.PHONE` is set.
- **Do** show hover and focus in navy on light grounds and in gold on navy grounds, 3px at a 3px offset.
- **Do** put hover styles inside `@media (hover:hover)` so taps don't leave them stuck.
- **Do** keep tap targets at 44px minimum and buttons at 56px, with reading text at 16px or larger.
- **Do** keep motion to the hero H1 bounce-in, the below-the-fold fade-up and the float circle, all off under reduced motion.

### Don't:
- **Don't** set hallway gold (`#f2b84b`) as text on paper or white.
- **Don't** put a gold accent phrase in a heading on a paper band.
- **Don't** bold or uppercase Cal Sans.
- **Don't** add a shadow to buttons, chips, fields, rows or the photo; the form card and the float circle are the only shadowed elements.
- **Don't** hard-code a phone number, Facebook URL or greeting outside `CONFIG`, or show a phone slot that dials nothing.
- **Don't** put a Call button under the hero headline, show a contact point twice on the first screen, or add a sticky bottom bar.
- **Don't** run any image other than the hero photo, or any texture other than the deep navy lines, behind text; don't join bands with divider shapes or curves.
- **Don't** style non-interactive labels or town names as chips.
- **Don't** add decorative motion (ambient animation, sheens, parallax, particles); the hero H1 bounce-in is the one entrance and stays on the H1.
