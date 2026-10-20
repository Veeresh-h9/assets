# RECRIORA — VIDEO 03 · "Digitalising Campuses" · Complete Production Guide

Vertical 1080×1920 · 30 fps · about 45 s (final length = your voice-over) · English or Hinglish voice-over · fast UI-metaphor motion graphics.

**What this pack is:** the dialogue, the scene-by-scene shooting plan, the asset map (what to use from *every* folder you gave me), the audio plan, the checklist of what is still missing, and the render source. Nothing here promises views; it is built from the patterns in your three reference videos.

> Folder map of this zip
> `01_Script` dialogue · `02_Brand` logos + website mockup (reference only) · `03_References` frames + transcripts of your 3 reference videos · `04_Audio_SFX` ready-to-use sounds + music candidate · `05_Fonts` Poppins + licence notes · `06_Repo_Assets_Manifest` what is in your GitHub repo · `07_Engine_Source` the Python renderer · `08_DROP_MISSING_ASSETS_HERE` where to put everything that is not available yet.

---

## 1. Goal and positioning
- **Message (positive, mission-led):** Recriora is a team taking on a big challenge — digitalising school and college management across the world.
- **Tone:** confident, optimistic, "we're building something big". No "we have nothing" lines (the reference said "zero clients"; ours replaces that with mission and momentum).
- **Audience:** school and college owners, principals, administrators, education entrepreneurs.
- **Action wanted:** DM / WhatsApp / mail / visit the site. Contact facts (from you):
  - WhatsApp: **89703 40172**
  - Email: **connect@recriora.co**
  - Website: **recriora.com**
  - Instagram handle: **not supplied yet** → put it in `08_DROP_MISSING_ASSETS_HERE/instagram/handle_and_contacts.txt`.
- **Brand line:** "Your Vision. Our Innovation."

## 2. What your reference videos teach us (copy the method, not the content)
| Reference | Structure | Visual method |
|---|---|---|
| Ref 1 — "challenge intro" (37.7 s) | Who we are → the challenge → why us → where we'll post → "we keep going" → "that's what makes it exciting" | Every phrase = one familiar app control: counter stepper "−1000$+", AI prompt box with chips, iMessage bubbles, carousel with arrows, date-picker calendar, glowing logo. New visual every 1–2 s. |
| Refs 2 & 3 (identical file, 18.9 s) | Pain hook → "Not anymore" → offer → "Want it? Comment Pack" | Search bar + hand cursor, Drive-style list, big sticker, dark end card with handle. |
Pattern we use: **instant hook (≤3 s) → one UI metaphor per phrase → proof of scale → clear contact CTA → brand line**. Frames and transcripts are in `03_References`.

## 3. Look and motion bible
- **Canvas:** off-white `#F7F7F4` with a faint 90 px grid. Dark moments allowed only for the end card glow.
- **Colours:** ink `#0B0D14`, electric blue `#2F5BFF` (emphasis), violet `#6C4DFF`, red `#F03E56` (only for "No paperwork / No confusion" strike-through). Green only inside a WhatsApp-style bubble.
- **Type:** Poppins Bold/Medium (bundled). Headlines 96–120 px, left-aligned at x=90 or centred; max 2–3 lines; auto-fit to 900 px width. One blue emphasis word per line.
- **Safe zone:** keep text 90 px from sides, 250 px from top, 380 px from bottom (Reels UI).
- **Cut rhythm:** **a new visual every 1.0–2.0 s**; no hold longer than 2.5 s except the phone number (hold ≥ 2.0 s) and the end card.
- **Easing:** entrances 10–14 frames, ease-out-expo; small overshoot (back-out ≈ 1.6) on pops; exits 8 frames ease-in-out. Text enters by sliding up out of a mask, staggered 3–4 frames per line.
- **Camera:** flat 2D; slow 3–5 % push-in on holds; whip-slide (6 frames) between scenes; circle/vertical wipes in brand blue. No hand-held shake except the "paperwork" crumple.
- **Motion blur:** 3 sub-frames, shutter 0.35 (final render only).
- **Never use:** the website mockup image inside the frame (you asked to remove it), real Instagram/WhatsApp/Google logos redrawn as exact copies — use simple generic glyphs or the official brand icons only if you accept their brand rules; made-up statistics.

## 4. FINAL DIALOGUE (line IDs used by the scene plan)
Estimated times assume ~2.7 words/second. **They are placeholders: send the real voice-over and every time below is re-measured to the frame.**

| ID | ≈ time | English | Hinglish |
|---|---|---|---|
| L1 | 0.0–1.3 | Hey, we're Recriora. | Hey, hum hain Recriora. |
| L2 | 1.5–4.0 | A team of designers, developers and dreamers. | Designers, developers aur dreamers ki ek team. |
| L3 | 4.2–9.5 | And we've taken on a challenge: to digitalise school and college management across the world. | Aur humne ek challenge uthaya hai: duniya bhar ke schools aur colleges ke management ko digital karna. |
| L4 | 9.8–12.8 | Attendance, fees, timetables, results, all in one place. | Attendance, fees, timetable, results, sab ek hi jagah. |
| L5 | 13.0–16.0 | No paperwork. No confusion. Just smooth, smart campuses. | Na paperwork, na confusion. Bas smooth, smart campus. |
| L6 | 16.3–20.8 | We're building websites, apps, cloud systems and AI automation, made for education. | Hum websites, apps, cloud systems aur AI automation bana rahe hain, education ke liye. |
| L7 | 21.0–24.5 | Our mission is big, and we're excited for every step. | Mission bada hai, aur hum har step ke liye excited hain. |
| L8 | 24.8–30.0 | We'll keep building, keep sharing, and keep improving, from one campus to the next. | Hum banate rahenge, share karte rahenge, aur behtar hote rahenge, ek campus se doosre campus tak. |
| L9 | 30.5–33.2 | Want your school or college to go digital? | Chahte ho aapka school ya college digital ho? |
| L10 | 33.5–38.5 | DM us now, or message us on WhatsApp at 89703 40172. | Abhi DM karo, ya WhatsApp karo 89703 40172 par. |
| L11 | 38.8–43.0 | You can also mail us at connect@recriora.co, or visit recriora.com. | Mail bhi kar sakte ho: connect@recriora.co, ya visit karo recriora.com. |
| L12 | 43.3–46.0 | Recriora. Your Vision. Our Innovation. | Recriora. Your Vision. Our Innovation. |

Voice direction is in `01_Script/elevenlabs_voice_direction.txt` (keep pauses ≤ 0.4 s — the last voice-over's long pauses made the video feel slow).

## 5. Hook options (first 3 seconds)
Use the main opening (L1–L2) or swap in one of these. Hook text appears on screen **within 0.2 s** and the first motion starts on frame 1.
| Hook | Voice | Visual for the hook |
|---|---|---|
| H1 | "What if every school and college in the world ran on one smart system?" | A paper attendance register fills the frame, flips (Paper Flip SFX), and becomes a clean dashboard; "one smart system" in blue. |
| H2 | "We're a team on a mission: digitalise schools and colleges across the world." | World dots light up one by one as a counter stepper taps "+". |
| H3 | "Stop managing your college on paper. We'll show you how." | A stack of papers gets a red "swipe to delete" gesture; blue "Show me" button pulses. |
| H4 | "Attendance on paper. Fees in registers. Results in files. There is a better way." | Three messy cards (register, ledger, file) get replaced one by one by tidy app cards. |
Recommendation: **H2 for the main cut** (it states the mission and promises scale), **H3 as the A/B test** (pain-led).

## 6. SCENE-BY-SCENE SHOOTING PLAN
Each scene lists: time · voice · on-screen text · the UI metaphor · motion · **assets and where they come from** · sound.
Source key — **[U]** = you uploaded it (in this pack) · **[R]** = your GitHub repo (add via section 10) · **[E]** = built by the render engine · **[S]** = SFX in `04_Audio_SFX`.

**S01 · 0.0–1.3 · L1 "Hey, we're Recriora."**
- Text: "Hey, we're" (ink) + brand icon pop. Small floating pixel stickers drift around the text (hand wave, laptop, books) — like the emoji accents in Ref 1's first frame.
- Motion: text slides up out of mask (10 f); icon scales 0→1.1→1 (12 f); stickers float with ±8 px sine drift.
- Assets: logo icon mask [U `02_Brand`], Poppins [U `05_Fonts`], pixel emoji [R `16x16-Emoji-Pack`], white/grid background [E].
- Sound: Pop [S] on the icon; BGM starts at −20 dB.

**S02 · 1.5–4.0 · L2 "A team of designers, developers and dreamers."**
- UI metaphor: a **segmented control** (iOS-style) that switches "designers → developers → dreamers", each tap highlighting in blue; three avatar chips pop beside it.
- Motion: each switch 6 f slide of the blue pill; words kinetic-type in time with the voice (tap on the stressed syllable).
- Assets: segmented control / buttons from [R `kenney_ui-pack`] (or [E] vector fallback), avatars generic [E], Pop ×3 [S].

**S03 · 4.2–6.6 · L3a "…taken on a challenge…"**
- UI metaphor: the **counter stepper** from Ref 1 — a card titled "Campuses digitalised" with "− 0 +"; a cursor taps "+" quickly (1 → 10 → 100 → ∞ style jump). A blue "CHALLENGE ACCEPTED" button gets pressed.
- Rule: show a **goal**, never an invented result. Use "GOAL" tag and "∞"/your confirmed number.
- Motion: number rolls (odometer, 8 f per step); button press = 4 f squash.
- Assets: stepper/button sprites [R `kenney_ui-pack`], trophy/star badge [R `Game-Icon-Pack`], tap/cursor [E]; Pop [S] per tap, Magic Wand [S] on "CHALLENGE ACCEPTED".

**S04 · 6.6–9.5 · L3b "…digitalise school and college management across the world."**
- UI metaphor: the **AI prompt box with chips** from Ref 1: the box types "Digitalise every campus." Chips below: "Schools" "Colleges" "Worldwide" get ticked one by one; then the box zooms into a **dotted world map** where pins drop.
- Motion: typing 2 chars/frame; chips pop with overshoot; pins fall 10 f with a 3 f bounce.
- Assets: prompt box + chips [E] (or Kenney panel [R]), world dot map [E], pins [E]/pixel icons [R]. SFX: Zoom [S] into the map, Pop [S] per pin.

**S05 · 9.8–12.8 · L4 "Attendance, fees, timetables, results, all in one place."**
- UI metaphor: four **app cards** flipping in, one per word (0.7 s each): attendance = checkbox list ticking; fees = payment toggle + "Paid" chip; timetable = **date-picker calendar** (Ref 1's calendar) with a highlighted range; results = grade card "A+".
- Motion: card flip 8 f; tick draw 6 f; calendar range sweep 10 f. Finish with the four cards snapping into one dashboard ("all in one place").
- Assets: checkbox/toggle/panel [R `kenney_ui-pack`], icons [R `Game-Icon-Pack`] or [E]; Notification Ding [S] on "Paid", Pop [S] on each card, Whoosh Snap [S] on the snap-together.

**S06 · 13.0–16.0 · L5 "No paperwork. No confusion. Just smooth, smart campuses."**
- UI metaphor: a **paper stack** (Paper Flip) is swiped away like a deleted message; "No paperwork." and "No confusion." appear with red strike-through; "Just smooth, smart campuses." lands in blue over a clean campus dashboard.
- Motion: crumple/flip 10 f, red strike draws 6 f, final line slide-up 12 f + 4 % push-in.
- Assets: paper/cards [E], red strike [E]; Paper Flip [S], Glitch [S] on "confusion", Whoosh Cinematic [S] on "smooth".

**S07 · 16.3–20.8 · L6 "…websites, apps, cloud systems and AI automation, made for education."**
- UI metaphor: the **carousel with arrows** from Ref 1 — four service cards (Websites, Apps, Cloud, AI) cycled by a tapped ">" arrow, then all four connect with lines to a school-building icon in the centre.
- Motion: carousel slide 8 f per card (0.6 s hold each); connecting lines draw 12 f with a travelling dot.
- Assets: arrows/buttons [R `kenney_ui-pack`], service badges [R `Game-Icon-Pack`] or [E] icons (browser, phone, cloud, sparkle), school icon [E]; Pop [S] per card, Riser [S] under the last two seconds.

**S08 · 21.0–24.5 · L7 "Our mission is big, and we're excited for every step."**
- UI metaphor: a **progress/level bar** with step markers "Step 1 … Step ∞" and a star filling; confetti dots burst on "excited".
- Motion: bar fill eased 20 f, star pop with overshoot, 14 confetti dots radiate 18 f.
- Assets: star/trophy [R `Game-Icon-Pack`], progress bar [R `kenney_ui-pack`]/[E]; Pop [S], Magic Wand [S].

**S09 · 24.8–30.0 · L8 "We'll keep building, keep sharing, and keep improving, from one campus to the next."**
- UI metaphor: **iMessage bubbles** (Ref 1) typing "Building…", "Sharing…", "Improving…" — each bubble then drags into a **calendar** (Day 1 · Day 2 · Day 3 … ticking) — consistency, positively framed. A row of platform buttons (Instagram · YouTube · X · LinkedIn) pops in at "sharing".
- Motion: bubble pop 8 f; calendar day tick every 4 f; platform buttons stagger 3 f.
- Assets: bubbles/calendar [E]; platform icons: official icons only if you accept brand rules, otherwise simple rounded-square glyphs [E]; Notification Ding [S] per bubble.

**S10 · 30.5–33.2 · L9 "Want your school or college to go digital?"**
- UI metaphor: a big **toggle switch** labelled "Go Digital" flips OFF→ON; the whole UI turns brand blue and a light sweep crosses the screen.
- Motion: question kinetic type 12 f; toggle flip 8 f with spring; colour flood 10 f.
- Assets: toggle [R `kenney_ui-pack`]/[E]; Whoosh Snap [S] + Pop [S] on flip; Riser [S] ends here.

**S11 · 33.5–38.5 · L10 "DM us now, or message us on WhatsApp at 89703 40172."**
- UI metaphor: a **DM compose bubble** ("Hi Recriora…") sliding in, then a **chat screen** with the number **89703 40172** large (≥ 110 px) and a "Tap to chat" button.
- Rule: the number stays on screen **≥ 2.0 s**, centred, high contrast.
- Assets: chat bubbles [E]; WhatsApp-style green only on the chat bubble [E]; Notification Ding [S] on bubble arrival.

**S12 · 38.8–43.0 · L11 "You can also mail us at connect@recriora.co, or visit recriora.com."**
- UI metaphor: an **email compose card** ("To: connect@recriora.co" typing) → send arrow → morph into a **browser address bar** typing "recriora.com" with a cursor click.
- Motion: typing 2 chars/frame; send arrow flies 10 f; bar expands 10 f.
- Assets: compose card + address bar [E]; Notification Ding [S] (send), Pop [S].

**S13 · 43.3–46.0 · L12 "Recriora. Your Vision. Our Innovation."**
- Visual: wipe to the end card. Stacked logo scales in with a glow ring, then "YOUR VISION. OUR INNOVATION." Below: a row of four contact icons (DM · WhatsApp · Mail · Web) and the handle (once supplied).
- Motion: logo 14 f ease-out + ring pulse; tagline stagger; final hold 0.6 s.
- Assets: stacked logo mask [U `02_Brand`], contact icons [E]; Core Bass Hit [S] on the logo, BGM outro swell, Magic Wand [S] optional.

## 7. How to "take" every scene (rules for the render)
1. **One idea per scene, one control per idea.** If a scene needs two UI elements, the second must be the *result* of the first (a tap → a state change).
2. **Show the action first, the label second.** The cursor/tap enters 3–4 frames before the word is spoken, so the picture leads the voice.
3. **Cut on the stressed word.** Scene changes land within ±2 frames of the first syllable of the next line (measured from the voice-over).
4. **Fill pauses with motion**, never with a still frame: any gap > 0.3 s gets a secondary animation (float, glow, count-up).
5. **Scale up for numbers**: phone and email text ≥ 110 px and ≥ 2 s on screen; everything else ≥ 64 px.
6. **Consistent spatial logic:** new things enter from the bottom/right; things that leave go up/left; wipes use brand blue.
7. **Last 0.6 s** of the video is a clean hold of the end card (no motion) so viewers can screenshot the contacts.

## 8. Asset usage map — everything you gave me
| Source | Status | Used? | Where / why |
|---|---|---|---|
| Recriora logos (stacked, horizontal, icon) [U] | in `02_Brand` | **Yes** | S01 icon, S13 stacked logo; recoloured black/white/blue at draw time, geometry untouched |
| Website mockup screenshot [U] | in `02_Brand` | **Style reference only** | Not placed in frames (you asked to remove it); colours/type match the site |
| Reference video 1, 2, 3 [U] | frames + transcripts in `03_References` | **Yes (method)** | UI-metaphor structure; ref 2 and 3 are the same file |
| Instagram Reels SFX pack (50 sounds) [U] | 12 picked in `04_Audio_SFX` | **Yes** | Pop, Notification Ding, Whoosh Transition/Snap/Cinematic, Zoom, Riser, Paper Flip, Glitch, Core Bass Hit, Magic Wand, PC Shutdown Chime. Licence: royalty-free incl. commercial, no attribution. Meme/comedy sounds are **left out** (wrong tone for a brand ad). |
| `MEMES.zip` (8 files) [U] | 1 picked | **Partly** | `spring-in-my-step` kept as the BGM candidate (verify its licence). The other 7 are meme clips/loops — not used. |
| `fonts.zip` (40 files) [U] | not copied | **No** | All are Demo/Trial/Personal-Use. Poppins (OFL) is used instead. |
| Kenney UI pack [R] | **missing** | Planned | S02, S03, S05, S07, S10 controls (CC0) |
| 16×16 emoji pack [R] | **missing** | Planned | S01 sticker accents |
| Game icon pack [R] | **missing** | Planned | S03/S07/S08 badges, stars, trophies |
| Moji Graphics (After Effects) [R] | **missing** | Optional | Only if a person finishes the video in After Effects |
| Toko presets (Premiere) [R] | **missing** | Optional | Only if a person finishes the video in Premiere |
| Spoikofo [R] | **missing** | Check | Likely a font; licence first |
| Engine source [E] | in `07_Engine_Source` | **Yes** | Python/Skia renderer, easing, kinetic type, icons, transitions, FFmpeg mux |

## 9. Audio plan
- **Voice-over:** ElevenLabs (see direction file). −3 dB peak.
- **Music:** `BGM_candidate_spring-in-my-step.mp3` at **−20 dB**, ducked a further **−8 dB** under the voice, +2 dB swell in the last 2.5 s.
- **SFX levels:** −14 dB (UI pops) to −8 dB (impacts). Cue list: Pop on every UI entry; Notification Ding on message/mail/paid events; Whoosh Snap on cuts; Riser under S07 end → S10; Core Bass Hit on the logo.
- Do **not** put SFX on every frame: maximum one SFX per 0.5 s.

## 10. What is still missing and where to put it
| Needed | Why | Drop it in |
|---|---|---|
| ElevenLabs voice-over (English and/or Hinglish) | exact timing of all 13 scenes | `08_DROP_MISSING_ASSETS_HERE/voiceover` |
| Instagram handle | end card | `…/instagram/handle_and_contacts.txt` |
| Confirmed goal number or "∞" for the stepper | S03 | same txt file |
| `kenney_ui-pack.zip`, `Game-Icon-Pack-v1.4-PNG.zip`, `16x16-Emoji-Pack_v1.1.zip` | S01–S10 sprites | their named folders |
| Moji / Toko packs (only for human editing) | optional | `moji_after_effects`, `toko_premiere` |
The GitHub repo files are Git LFS and the build environment could not download them. Fix by either (a) `git lfs pull` and upload the zips, or (b) allowing `github-cloud.githubusercontent.com` and `media.githubusercontent.com` in the network settings.

## 11. Render instructions
```
pip install skia-python pillow numpy   # + ffmpeg
cd 07_Engine_Source
# scenes_v3.py is the previous video; a new scenes_v4.py for this guide is built once the voice-over arrives
SCENE_MODULE=scenes_v4 python3 render.py --final --audio ../08_DROP_MISSING_ASSETS_HERE/voiceover/<voice>.mp3
```
Preview first: `python3 render.py --preview` (540×960, silent). Final: 1080×1920, 30 fps, 3-sample motion blur, audio muxed, length = voice-over.

## 12. Posting pack (to help retention and enquiries)
- **Cover frame:** S10 "Go Digital" toggle, or S03 stepper.
- **Caption (English):** "We're taking on a challenge: digitalising school & college management across the world 🎓 DM us or WhatsApp 89703 40172 to take your campus digital. connect@recriora.co · recriora.com"
- **Caption (Hinglish):** "Hum ek challenge pe hain: duniya bhar ke schools aur colleges ko digital karna 🎓 DM karo ya WhatsApp 89703 40172. connect@recriora.co · recriora.com"
- **Pinned comment:** "Which feature does your campus need first — attendance, fees, timetable or results? 👇" (invites replies).
- **Hashtags (6–8):** #edtech #schoolmanagement #collegemanagement #digitalcampus #webdevelopment #recriora #education #startupindia
- **Test plan:** post H2 version, then H3 version a week later; compare 3-second hold rate and shares.

## 13. Quality checklist before you publish
- [ ] Voice and captions match word for word (including the phone number and email).
- [ ] Phone number on screen ≥ 2.0 s, ≥ 110 px, correct digits: **89703 40172**.
- [ ] Email correct: **connect@recriora.co** (note: `.co`, not `.com`).
- [ ] No invented statistics; the stepper shows a goal.
- [ ] Every font and sound used has a commercial licence (Poppins OFL, sfxreels licence, Kenney CC0).
- [ ] Text inside safe zones; no overlap at scene transitions.
- [ ] Handle added to the end card.
