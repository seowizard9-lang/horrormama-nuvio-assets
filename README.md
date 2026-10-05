# horrormama-nuvio-assets

This repo contains the visual assets for the Nuvio collection **"horror Mama 2"**.

- Assets are publicly hosted through GitHub.
- Nuvio references them through **jsDelivr CDN** URLs.

## Rules

- **Do not rename folders** once their URLs are being used in Nuvio. Renaming breaks every link that points at them.
- **Prefer versioned filenames** when replacing finalized artwork if CDN caching becomes an issue (for example `cover-v2.png`), then update the URL in Nuvio.
- **Main portrait covers use PNG.**
- **Widescreen backdrops should be high-quality JPG**, unless transparency is needed.
- **Keep filenames lowercase with hyphens.**
- **No spaces in filenames.**
- Original artwork only. Do not use copyrighted movie poster images.

## Recommended artwork sizes

| Asset | Size | Aspect ratio | Format |
|---|---|---|---|
| Portrait cover | 1000 x 1500 px | 2:3 | PNG |
| Backdrop | 1920 x 1080 px | 16:9 | JPG |
| Logo | ~1200 px wide | — | Transparent PNG |

## Repository layout

```
horrormama-nuvio-assets/
├── collection/          Main collection cover + backdrop
├── folders/<folder>/    cover.png for each of the 11 folders
├── backdrops/<folder>/  backdrop.jpg for each of the 11 folders
├── logos/collection/    horrormama-logo.png
├── logos/folders/       Optional per-folder logos (<folder>.png)
├── source-art/          Working / source files (PSD, layered files, etc.)
├── archive/             Retired artwork versions
└── ASSET_PLAN.md        Production checklist
```

## Final filenames

**Collection**

```
collection/horrormama-cover.png
collection/horrormama-backdrop.jpg
logos/collection/horrormama-logo.png
```

**Folders** (`<folder>` is one of the slugs below)

```
folders/<folder>/cover.png
backdrops/<folder>/backdrop.jpg
logos/folders/<folder>.png        (optional)
```

| Nuvio folder | Slug |
|---|---|
| Featured | `featured` |
| By Subgenre | `by-subgenre` |
| By Year | `by-year` |
| By Studio | `by-studio` |
| By Franchise | `by-franchise` |
| Around the World | `around-the-world` |
| By Theme | `by-theme` |
| Horror TV | `horror-tv` |
| Cult & Classics | `cult-and-classics` |
| Horror Mama Picks | `horror-mama-picks` |
| Extreme & Weird | `extreme-and-weird` |

## jsDelivr URL format

Replace `GITHUB_USERNAME` with your GitHub username:

```
https://cdn.jsdelivr.net/gh/GITHUB_USERNAME/horrormama-nuvio-assets@main/collection/horrormama-cover.png

https://cdn.jsdelivr.net/gh/GITHUB_USERNAME/horrormama-nuvio-assets@main/folders/featured/cover.png

https://cdn.jsdelivr.net/gh/GITHUB_USERNAME/horrormama-nuvio-assets@main/backdrops/featured/backdrop.jpg
```

General pattern:

```
https://cdn.jsdelivr.net/gh/GITHUB_USERNAME/horrormama-nuvio-assets@main/<path-to-file>
```

## CURRENT NUVIO COLLECTION STRUCTURE

### Featured
- Popular Horror
- New & Upcoming Horror
- Top Rated Horror
- Modern Horror Essentials
- Trakt Horror Movies

### By Subgenre
- Slashers
- Supernatural Horror
- Psychological Horror
- Found Footage
- Zombies
- Vampires
- Body Horror
- Cosmic Horror
- Exorcism
- Gore & Splatter
- Alien Horror
- Post-Apocalyptic Horror
- Sci-Fi Horror
- Horror Comedy

### By Year
- 2020s Horror
- 2010s Horror
- 2000s Horror
- 1990s Horror
- 1980s Horror
- 1970s Horror
- 1960s Horror
- 1950s Horror

### By Studio
- Blumhouse Horror
- A24 Horror
- NEON Horror
- New Line Cinema Horror
- Universal Pictures Horror
- Paramount Pictures Horror
- Sony Pictures Horror
- Warner Bros. Horror
- Lionsgate Horror
- Atomic Monster Horror
- Screen Gems Horror
- Ghost House Pictures Horror

### By Franchise
- Halloween
- Friday the 13th
- A Nightmare on Elm Street
- Scream
- Saw
- The Conjuring
- Insidious
- Paranormal Activity
- The Exorcist
- Child's Play
- Evil Dead
- Hellraiser
- Final Destination
- The Ring
- Texas Chainsaw Massacre
- Alien
- Resident Evil
- V/H/S
- Jaws
- IT

### Around the World
- Japanese Horror
- Korean Horror
- Italian Horror
- British Horror
- French Horror
- Spanish Horror
- Mexican Horror
- Argentinian Horror
- Canadian Horror
- Australian Horror
- Indonesian Horror
- Thai Horror

### By Theme
- Haunted Houses
- Serial Killers
- Supernatural
- Exorcism & Possession
- Found Footage
- Psychological Nightmares
- Alien Terror
- Apocalypse Horror

### Horror TV
- Popular Horror Series
- Slasher Series
- Vampire Series
- Zombie Series
- Supernatural Series
- Psychological Horror Series
- Found Footage Series
- Cosmic Horror Series
- Trakt Horror Series

### Cult & Classics
- Classic Horror: 1950s
- Classic Horror: 1960s
- Classic Horror: 1970s
- 80s Cult Horror

### Horror Mama Picks
- Horror Mama Essentials
- Modern Must-Watch
- Recent Standouts
- Deep Cuts

### Extreme & Weird
- Body Horror
- Gore & Splatter
- Cosmic Horror
- Psychological Horror
