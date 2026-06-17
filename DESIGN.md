---
version: alpha
name: PaceArena
description: A sharp, minimal, high-tech visual identity for a virtual racing platform where real-world runners compete in digital race environments.
colors:
  primary: "#E5FE52"
  secondary: "#717AD9"
  tertiary: "#FE8952"

  background: "#000000"
  surface: "#101010"
  surface-raised: "#181818"
  surface-subtle: "#242424"

  text-primary: "#FFFFFF"
  text-secondary: "#C8C8C8"
  text-muted: "#7A7A7A"
  text-inverse: "#000000"

  border: "#2A2A2A"
  border-strong: "#404040"

  success: "#E5FE52"
  info: "#717AD9"
  warning: "#FE8952"
  error: "#FF4D5E"
  live: "#FF3B5F"

  route-default: "#FFFFFF"
  route-active: "#E5FE52"
  route-secondary: "#717AD9"
  route-tertiary: "#FE8952"

typography:
  headline-display:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: -0.045em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: 800
    lineHeight: 1
    letterSpacing: -0.04em
  headline-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: 750
    lineHeight: 1.1
    letterSpacing: -0.03em
  headline-sm:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -0.02em

  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0em

  label-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: 800
    lineHeight: 1
    letterSpacing: 0.04em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: 800
    lineHeight: 1
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: 800
    lineHeight: 1
    letterSpacing: 0.08em

  telemetry-lg:
    fontFamily: JetBrains Mono
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: -0.04em
  telemetry-md:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.02em
  telemetry-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: -0.01em

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 12px
  xl: 20px
  full: 9999px

spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  gutter-mobile: 16px
  gutter-desktop: 32px
  page-max-width: 1200px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: 14px 18px
    height: 48px
  button-primary-hover:
    backgroundColor: "#F0FF8A"

  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.text-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: 14px 18px
    height: 48px

  button-tertiary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: 14px 18px
    height: 48px

  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.text-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: 12px 14px
    borderColor: "{colors.border}"

  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
    borderColor: "{colors.border}"

  card-highlight:
    backgroundColor: "{colors.surface-raised}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
    borderColor: "{colors.primary}"

  chip:
    backgroundColor: "{colors.surface-raised}"
    textColor: "{colors.text-secondary}"
    typography: "{typography.label-sm}"
    rounded: "{rounded.full}"
    padding: 8px 12px

  chip-active:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-inverse}"

  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 12px 14px
    borderColor: "{colors.border}"

  leaderboard-row:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 12px 16px

  leaderboard-row-current-user:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-inverse}"

  telemetry-panel:
    backgroundColor: "{colors.surface-raised}"
    textColor: "{colors.primary}"
    typography: "{typography.telemetry-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.md}"
    borderColor: "{colors.border}"

  race-map:
    backgroundColor: "{colors.background}"
    routeColor: "{colors.route-default}"
    activeRouteColor: "{colors.route-active}"
    secondaryRouteColor: "{colors.route-secondary}"
    tertiaryRouteColor: "{colors.route-tertiary}"
---

# PaceArena DESIGN.md

## Overview

PaceArena is a collaborative virtual racing platform where real-world runners compete through digital race formats. The brand identity should feel fast, technical, competitive, and trustworthy.

The final logo system is built around a modular, slanted mark composed of simple geometric blocks. The symbol suggests speed, racing lanes, GPS fragments, checkpoints, and a stylized “P” without becoming illustrative or overly detailed.

The visual identity is defined by:

- **Black background:** premium, focused, race-night atmosphere.
- **White geometry:** clarity, precision, trustworthy data.
- **Signal Lime:** primary energy, active race state, progress, verification.
- **Periwinkle Blue:** secondary race state, opponents, digital multiplayer presence.
- **Velocity Orange:** tertiary energy, heat, challenge, warnings, momentum.

The product should feel like a bridge between a real road race and a digital multiplayer competition: athletic, social, verified, and slightly futuristic.

Primary tagline:

> Real runs. Real competition.

Alternative taglines:

- Run anywhere. Race together.
- Your road. Our arena.
- Verified racing for real runners.
- Real roads. Digital races.

## Colors

The palette is minimal and high-contrast, built for speed, readability, and brand recognition.

- **Primary / Signal Lime (`#E5FE52`):** The main brand accent. Use it for active states, progress, verification, current user highlights, primary buttons, race wins, and podium moments.
- **Secondary / Arena Blue (`#717AD9`):** Used for secondary race states, multiplayer presence, opponent routes, informational states, and alternate logo variants.
- **Tertiary / Velocity Orange (`#FE8952`):** Used for challenge states, heat, effort, warnings, streaks, race intensity, and tertiary logo variants.
- **Background / Pure Black (`#000000`):** The main brand background. It creates strong contrast and gives the product a premium, focused, high-tech feeling.
- **White (`#FFFFFF`):** Used for the logo mark, main text, neutral UI, route lines, and structural clarity.

The brand should mostly appear as **black + white + one accent**. Avoid using all three accents at equal intensity on the same screen unless showing categories, teams, or multiple competitors.

Recommended semantic use:

- Lime: active user, verified, winning, primary CTA.
- Blue: opponents, multiplayer, information, secondary route.
- Orange: challenge, heat, effort, warning, competitive tension.
- White: neutral route, text, iconography, logo structure.
- Black: primary environment.

## Typography

The typography should be bold, compact, and functional. The logo uses a heavy italic wordmark, so the interface should support that with confident modern typography.

Use:

- **Inter** for UI, navigation, headings, labels, and body text.
- **JetBrains Mono** for telemetry, timing, pace, rankings, GPS confidence, and performance data.

Headlines should feel like race graphics: bold, tight, and direct.

Labels should often be uppercase and compact, especially for:

- race status
- ranking filters
- validation state
- challenge category
- distance
- split type
- live status

Telemetry should be precise and technical. Use mono typography for:

- elapsed time
- pace
- distance
- heart rate
- split
- rank delta
- GPS confidence

Avoid decorative typefaces and excessive font variety. The identity should feel stripped back, fast, and engineered.

## Layout

The layout should feel like a race control interface: direct, modular, and easy to scan.

Use a mobile-first layout for active race participation and a wider dashboard layout for discovery, rankings, and post-race analysis.

Layout principles:

- Prioritize race-critical data.
- Keep live metrics large and glanceable.
- Use modular cards and panels.
- Use strong alignment and clear visual grouping.
- Keep social features contextual and secondary.
- Use accent colors as signals, not decoration.
- Preserve negative space around the logo and primary race states.

Recommended structure:

- Top race status/navigation bar.
- Main race progress or event context.
- Telemetry cluster.
- Ranking/progress module.
- Validation state.
- Social reactions/comments.
- Persistent primary action when needed.

Spacing follows an 8px system with 4px micro-adjustments. Active race screens may be denser, but core metrics must remain readable while the user is running or fatigued.

## Elevation & Depth

Depth should be subtle and mostly flat. The logo is geometric and minimal, so the interface should avoid heavy visual effects.

Use:

- black surfaces
- dark gray panels
- thin borders
- accent outlines
- active color blocks
- subtle overlays
- crisp separation

Avoid:

- heavy shadows
- glossy 3D effects
- complex gradients
- excessive glow
- glassmorphism as a default style
- noisy backgrounds behind text

Hierarchy should come from contrast, scale, spacing, and accent color. The design should feel high-tech without becoming visually loud.

## Shapes

The core shape language comes from the logo: **slanted modular blocks**.

These blocks suggest:

- speed
- acceleration
- GPS fragments
- race segments
- checkpoints
- digital lanes
- competition flow

Use this shape logic throughout the brand system, especially in:

- progress indicators
- route segments
- loading states
- race category marks
- achievement badges
- section dividers
- motion graphics
- app icon treatments

Shape rules:

- Keep forms geometric and simple.
- Prefer solid shapes over complex outlines.
- Use forward-leaning slants consistently.
- Avoid rounded, playful, or bubbly shapes.
- Avoid tiny internal details.
- Ensure icons work at small sizes.

Corners in the UI should be mostly sharp with slight rounding. Buttons and cards can use small radii for usability, but the overall feeling should remain athletic and technical.

## Components

### Buttons

Primary buttons use Signal Lime with black text. They are reserved for the most important action on the screen.

Use primary buttons for:

- Create race
- Join race
- Start race
- Confirm result
- Challenge runner
- View podium

Secondary buttons use Arena Blue when an action is important but not primary.

Use secondary buttons for:

- View ranking
- Compare runners
- Open race room
- View opponent
- Invite friends

Tertiary buttons use Velocity Orange only when the action relates to challenge, heat, effort, or urgency.

Use tertiary buttons for:

- Join challenge
- Start rematch
- Report issue
- Review suspicious result
- Push final effort

Ghost buttons are used for low-emphasis actions and should rely on white text, thin borders, or subtle surfaces.

### Race Cards

Race cards should be compact, structured, and easy to compare.

They should include:

- race name
- distance or time goal
- race type
- participant count
- start/end time
- validation requirements
- live/upcoming/completed state

Use a single accent color per card. Do not use all accent colors unless the card specifically compares multiple runners, teams, or race categories.

### Live Race Room

The live race room is the most important experience. It should feel focused, urgent, and readable.

Prioritize:

- elapsed time
- distance completed
- current pace
- race position
- opponent progress
- GPS validation state
- route progress
- final stretch indicators
- reactions and race narration

Use Lime for the current user and active progress. Use Blue for opponents or multiplayer presence. Use Orange for challenge intensity, effort spikes, or warning states.

### Leaderboards

Leaderboards should feel competitive and trustworthy.

Rows should include:

- rank
- runner name
- avatar or initials
- finish time
- pace
- validation status
- delta from nearby runners

Highlight the current user with Lime. Use Blue for selected comparison rows or followed runners. Use Orange for warnings, disputed efforts, or challenge highlights.

### Telemetry Panels

Telemetry panels should feel like timing hardware.

Use JetBrains Mono for:

- pace
- time
- distance
- heart rate
- splits
- GPS confidence
- ranking delta

Telemetry panels should use dark surfaces, white labels, and one accent value. Avoid showing too many metrics with equal emphasis.

### GPS Route UI

Routes should be minimal and high contrast.

Use:

- White for base route.
- Lime for active user progress.
- Blue for opponents.
- Orange for challenge segments, effort zones, or warning areas.

Route visuals should feel like simplified GPS data, not fantasy maps. Keep road context grounded and readable.

### Avatars

Avatars should be simple and sporty. They may use initials, abstract runner silhouettes, or geometric badges.

Avatar accent color can indicate:

- user status
- team
- category
- active race state
- ranking group

Avoid cartoon-heavy avatar systems unless used only in playful secondary contexts.

### Comments and Reactions

Social components should be lightweight and contextual. They should support the race, not compete with it.

Use reactions for:

- strong finish
- new PR
- close race
- comeback
- podium
- respect
- challenge accepted

Use comments mostly after races, in group challenges, or around results.

### Generative Race Narration

Race narration should feel like a compact sports broadcast feed.

Tone:

- short
- energetic
- supportive
- grounded in real data
- never exaggerated beyond the performance evidence

Example narration style:

- “You moved into 3rd with 800m left.”
- “New fastest split in the final kilometer.”
- “Verified finish. Strong negative split.”
- “Alex closes the gap by 12 seconds.”

Use Lime for positive verified milestones, Blue for opponent updates, and Orange for challenge or pressure moments.

### AR Podium

The AR podium should be sharp, minimal, and celebratory.

Use:

- black base
- white geometry
- lime winner highlights
- blue/orange placement accents
- verified badge
- finish time
- race name

Avoid overly playful celebration graphics. The podium should feel premium, earned, and shareable.

## Do's and Don'ts

- Do keep the brand mostly black, white, and one accent at a time.
- Do use Lime for the strongest active or verified state.
- Do use Blue for multiplayer, opponents, and secondary information.
- Do use Orange for challenge, heat, effort, and urgency.
- Do preserve strong contrast.
- Do make race-critical metrics large and readable.
- Do use slanted modular blocks as the main graphic language.
- Do keep icons simple enough to work at small sizes.
- Do make validation states visible and trustworthy.

- Don't overuse all three accent colors on one screen.
- Don't use complex gradients in the core identity.
- Don't add thin speed lines to the logo.
- Don't make the product feel like a generic fitness tracker.
- Don't make the UI too playful or cartoonish.
- Don't hide verification or anti-fraud states.
- Don't use tiny text for live race data.
- Don't use heavy shadows or glossy 3D effects.
- Don't distort the logo mark or change its slant logic.
- Don't place the logo over noisy imagery without enough contrast.

## Logo Guidance

The PaceArena logo system includes horizontal and vertical lockups. The mark is composed of slanted modular blocks that create a fast, technical, and scalable symbol.

Logo variants:

- **Primary:** White mark with Lime accent; “PACE” in white and “ARENA” in Lime.
- **Secondary:** White mark with Blue accent; “PACE” in white and “ARENA” in Blue.
- **Tertiary:** White mark with Orange accent; “PACE” in white and “ARENA” in Orange.
- **Monochrome:** All white or all black when color is not available.
- **Symbol-only:** Use for app icons, favicons, smartwatch UI, map markers, and badges.

Logo rules:

- Use the primary logo as the default brand expression.
- Use the secondary logo for multiplayer, community, or opponent-focused contexts.
- Use the tertiary logo for challenge, heat, effort, or campaign contexts.
- Keep the symbol flat and geometric.
- Preserve clear space around the logo.
- Use the horizontal lockup for headers and wide placements.
- Use the vertical lockup for posters, splash screens, and centered layouts.
- Use the symbol-only mark for small sizes.

Avoid:

- gradients inside the logo
- drop shadows behind the logo
- outlines around the wordmark
- changing the accent block position
- adding extra blocks to the symbol
- using multiple accent colors in the same logo
- placing the logo on low-contrast backgrounds
- stretching or rotating the lockup

## Imagery

Imagery should show real runners in real environments. The brand should feel connected to roads, effort, GPS, sweat, and everyday competition.

Preferred imagery:

- road running
- city streets
- night or early morning runs
- runners from behind or side profile
- smartwatch interactions
- small group runs
- finish-line moments
- urban routes
- real asphalt and lighting

Image treatment:

- black overlay
- high contrast
- minimal color
- white GPS route lines
- one accent color per composition
- modular slanted graphic overlays

Avoid overly polished stock photography, elite-only race imagery, or fantasy esports visuals. PaceArena should feel competitive, but still grounded in real recreational running.

## Motion

Motion should be angular, fast, and modular.

Recommended motion patterns:

- logo blocks sliding into place
- accent block snapping into position
- progress segments filling left to right
- route lines drawing over a map
- leaderboard rows shifting position
- telemetry count-up
- checkpoint flash
- finish-state pulse
- podium reveal

Motion should support state changes and race understanding. Avoid decorative animation that distracts during active race moments.

## Accessibility

PaceArena must remain readable outdoors, in motion, and under fatigue.

Requirements:

- Maintain strong contrast between text and background.
- Use large typography for race-critical metrics.
- Do not rely on color alone for state.
- Pair color states with labels or icons.
- Keep tap targets large on mobile.
- Provide reduced-motion alternatives.
- Avoid tiny labels in live race contexts.
- Keep the symbol recognizable without accent color.
- Use clear validation labels for verified, pending, warning, and failed states.

Race-critical information should be readable in one quick glance.
