# Ahmed Home Renovation — handoff at ~60%

**Live:** https://10elizabethbell.github.io/ahmedHomeRenovation/ · **Repo:** https://github.com/10elizabethbell/ahmedHomeRenovation · **Built:** 2026-10-20 from Muse brief of 2026-10-20 (Facebook group "Essex County Contractor Referrals" post) · **Call Sheet:** site set

## The big gap first: there is no phone number
The business has no phone, email, Facebook page or Maps listing that Muse could find. The only channel is a post in a Facebook group, made from a personal profile (ابو رياض) whose link to the business is unconfirmed. So:
- The header's top-right slot is a **Facebook** link (to the group post) instead of a phone number. A "Phone coming soon" placeholder was tried and cut: it made the site look unfinished.
- The estimate form writes the visitor's message out and offers **Copy message** + **Open our Facebook post**, with a line telling them to paste it in a private message, not a public comment. The submit button turns into an outlined "Update my message" so only one gold button shows.
- The floating circle scrolls to the form instead of opening a text.
- **One edit fixes most of it:** in `index.html`, set `CONFIG.PHONE` (e.g. `'+15195551234'`) and `CONFIG.PHONE_DISPLAY` (`'(519) 555-1234'`). Then the header shows the tap-to-call number, the form texts the business, the circle opens a pre-filled text, and the number appears in the closing band and footer. Also hard-code the number into the header `#tel` link for visitors without JS, and update the `<meta name="description">`.
- When a Facebook business page or Messenger (m.me) link exists, set `CONFIG.FB`: every `data-fb` link (header, work link, form, footer) follows it. Also update the `<noscript>` fallback link under the form.
- The group post's page title loads for a logged-out browser (checked 2026-10-20 with curl), so the group looks public, but nobody has opened it logged out in Facebook's in-app browser.

## What's built
- One page, phone first: paper header (A.H.R wordmark, Facebook/phone slot), photo hero, services, "We treat your home like it's ours" with three promises, their photo shown unveiled (4:5, no caption) and "See this job on Facebook", How it works (3 steps), free-estimate form, closing band with the service area, footer.
- Palette mapped onto the calm style: paper #f4f6fb, painter's-tape navy #1f3f6e, deep navy #10233f (line texture), warm hallway-light gold #f2b84b as the only accent (fills; #8a5a00 as text on light). Cal Sans headings, system body.
- Hero: their own photo (freshly painted taupe room through to a hall and stairs) under a navy veil. Phone uses a portrait crop centred on the doorway; desktop a wide crop with the window blinds cut off. White text measured at 5.6:1 or better on phone and 8.5:1 on desktop by pixel sampling; gold "Windsor." about 3.1–3.5:1 on phone (large text, passes 3:1), after darkening the phone veil.
- H1 "Walls done / right in / Windsor." bounces in letter by letter and restores the plain heading after ~1.5s; explicit line breaks keep the same lines during and after. Fade-up on everything below the first screen. Floating circle shows after the hero, hides over the form.
- Service rows pre-select the matching job chip in the form.
- Favicon and home-screen icon: a gold "A" on navy (no logo exists). og image 1200×630 from the hero photo.

## Assumptions I made
- **"We", not "I":** their own captions say "Contact Us"; crew size unknown.
- **Colours are mine:** no logo or brand colours exist. Navy taken from the blue painter's tape in their photo, gold from the warm hallway light in it.
- **"Windsor" in the H1** as the anchor town; LaSalle, Tecumseh and Amherstburg are in the closing band and the form placeholder.
- **"We tape the trim and cover your floors"** (care lede and step 3) is inferred from their photo (blue tape on the baseboard, floor covered), not stated by them. Confirm with the owner.
- **Step 2 "We'll tell you what it takes and what it costs."** describes an estimate; not their words.
- **Services shortened** from their list: "Home Renovations & Improvements" → "Home renovations"; "Interior & Exterior Painting" kept as one row.
- **Canadian spelling**, en-CA.
- The photo's `og:type` was `video.other`: the post may be a video and the image its thumbnail. It is clearly their job site either way.

## Placeholders and gaps
- Phone, text, email: none (above). No email in the footer because none exists.
- Logo: none; wordmark "A.H.R / Ahmed Home Renovation" set in Cal Sans.
- Only one photo: a heavily veiled crop in the hero and an unveiled crop in the care section. There is no work gallery; the Facebook link stands in.
- No reviews, prices, hours, years in business, insurance, owner name: nothing said about any of them.
- The Facebook link points at a **group** post; people outside the group may not be able to see it.

## Questions for the owner
1. What number should customers call or text? Does it take texts?
2. Who is the owner (first name) — is ابو رياض the owner? Would they like their name on the site?
3. More job photos, ideally before/after pairs (drywall patches are perfect for that).
4. A Facebook business page or Messenger link we can point to?
5. Insured? Years in business? Any customer reviews we can quote word for word?
6. Exterior painting season and hours; any towns beyond the four named?
7. Which services bring the most work (to order the list)?

## Ideas not built (yours to pick)
- **Signature motion (opt-in), best world: a paint roller.** A roller that sweeps a fresh coat across the hero's bottom edge, leaving soft nap texture; drag to roll it yourself. Runners-up: drywall mud being skimmed smooth with a knife; a blue tape line peeled to reveal a crisp edge; cut-in brush strokes along a ceiling line.
- **Before/after sliders** under the services once the owner sends pairs (a drywall patch before/after is the strongest proof they could give).
- **Work gallery** of 4:5 photo cards above the Facebook link once there are 3+ photos.
- "Write my message" could also attach a photo hint ("Add photos in Messenger").
- Outlined step numerals so gold is kept for actions (Impeccable colorize).
- On desktop the five service rows leave one empty cell in the two-column grid; a sixth service or a single column would square it off.
- Overdrive idea: a paint-roller pass on first load that lifts the navy veil off their photo in one stroke.

### Impeccable findings kept by your choice
- Eyebrow pills (craft floor bans them outright), the H1 letter bounce-in (animate/quieter: "no bounce"), the floating circle, Cal Sans, and the diagonal band texture (detector "repeating-gradient stripes"; suppressed for `index.html` in `.impeccable/config.json` with that reason).
- Detector "flat type hierarchy" left standing: the close sizes are UI text (12 brand line, 14 eyebrow, 15 helper, 16 body, 18 labels and buttons); the heading scale runs 30–84px.

## Not verified
- Real-device touch, and the iOS/Android `sms:` handoff once a phone number is set (tested only that the link and body are built correctly).
- Copy-to-clipboard inside Facebook's in-app browser (may be blocked; the message stays selectable and the button says so).
- Whether the group post opens for non-members inside the Facebook app.
- Frame rate of the bounce-in on old phones.
