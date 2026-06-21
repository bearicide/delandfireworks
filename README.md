# Deland Rd Fireworks

Static GitHub Pages site for `/delandfireworks`.

Theme update:

- Newspaper-style front page
- Deland Rd Fireworks 25th Anniversary
- America’s 250th Birthday / America 250
- More patriotic, explanatory event wording for public sharing
- Fresh MATTBEAR PNG sidebar ad linking to `https://bearicide.github.io`
- Announcement player tries to autoplay on launch page load
- Fireworks SFX are wired from the `sfx/` folder

## Pages

- `index.html` - newspaper-style event info / landing page
- `launch.html` - separate interactive fireworks theater with mini-player, announcement audio, and fireworks SFX

## Live URLs

Main page:

`https://bearicide.github.io/delandfireworks/`

Launch page:

`https://bearicide.github.io/delandfireworks/launch.html`

## Public message

This build frames the event as both a local milestone and a national celebration:

- 25 years of the Deland Rd Fireworks tradition
- America’s 250th Birthday
- Fourth of July community pride
- family, friends, neighbors, food, bracelets, and larger finales

## Newspaper styling

The landing page uses a newspaper-inspired layout:

- masthead: `The Deland Rd Gazette`
- special edition line
- front-page headline
- two-column article copy
- countdown sidebar
- event-detail cards
- classifieds / public notice section
- launch-page advertisement block
- clickable MATTBEAR sidebar ad
- footer link rail back to MATTBEAR and event pages
- newspaper-style share card

## Audio

Announcement audio path:

`audio/announcement.mp3`

Launch page behavior:

- the announcement tries to play automatically when the launch page opens
- the same visible player stays in the same place
- if the browser blocks autoplay, the Play button pulses
- first tap/click/keypress can unlock the announcement
- the player still supports pause, progress, seeking, volume, and visualizer bars

Browser note: autoplay with sound may be blocked by Chrome, Safari, Android, or other joyless committees unless the visitor has already interacted with the page.

## Fireworks SFX

Firework sound folder:

`sfx/`

Expected files:

- `sfx/fw-launch-short.wav`
- `sfx/fw-launch-long.wav`
- `sfx/fw-pop-small.wav`
- `sfx/fw-boom-medium.wav`
- `sfx/fw-boom-big.wav`
- `sfx/fw-distant-boom.wav`
- `sfx/fw-crackle.wav`
- `sfx/fw-sparkle.wav`
- `sfx/fw-whistle-pop.wav`
- `sfx/fw-finale-barrage.wav`

The launch page uses these SFX for rocket launches, bursts, sparkle mode, willow mode, crackles, and the finale.

## MATTBEAR sidebar ad

Current asset path:

`assets/mattbear-ad.png`

Current hookup improvements:

- scales to fit the sidebar container
- explicit `width` and `height` attributes to reduce layout shift
- `loading="lazy"` and `decoding="async"`
- linked to `https://bearicide.github.io`
- wrapped in semantic `figure` / `figcaption`

## Maintenance notes

Recent cleanup / bughunt:

- confirmed top navigation links
- confirmed sidebar launch link
- confirmed Facebook post link
- added footer links back to `https://bearicide.github.io`
- ensured the MATTBEAR ad scales correctly on mobile and desktop
- hooked fireworks SFX to the launch theater
- added announcement autoplay attempt with graceful fallback
- kept countdown timer and sharing helpers intact

## GitHub Pages

Use:

**Settings → Pages → Deploy from branch → main / root**
