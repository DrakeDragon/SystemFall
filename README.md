# Systemfall: Day One — Three-Day Chronicles

**Earth has become a game. Monsters claim the streets. You have 72 hours to decide who survives—and the world remembers how you played.**

Systemfall: Day One is a branching, mobile-first survival LitRPG played entirely in the browser. Create a survivor, awaken a class, recruit allies, manage a threatened refuge, and choose what happens to the city of Grayhaven during the first three days of a System apocalypse.

The **Three-Day Chronicles / Chronicles Edition**, version **3.0.0**, expands the original campaign with four connected survival stories, twelve major campaign chapters, equipment crafting, shelter development, faction relationships, and endings shaped by the decisions you carry across all three days.

Built with HTML, CSS, and vanilla JavaScript, the game runs from one `index.html` file and ten local illustrated backgrounds. It requires no installation, account, backend, package manager, or build step.

![Grayhaven after the System arrives](assets/cityfall.webp)

## The story

At 7:14 a.m., the world pauses. Coffee hangs in the air. A bird freezes between wingbeats. Then a blue circle unfolds over Grayhaven, and the rules of human life begin to change.

Monsters enter the streets. People awaken classes. Evacuation routes become quests, and a mysterious System begins deciding which lives count.

You begin in an apartment at Hour Zero. Over the next 72 hours, your choices take you through a collapsing city, shelters, transit tunnels, wild territory, hidden archives, and the machinery behind the apocalypse. Supplies are limited, allies have their own convictions, and survival can demand more than winning a fight.

Will you organize an evacuation, build a community strong enough to remain, pursue the truth behind the System, or accept the power it offers?

## Features

- **285 registered story scenes** in the current build, with conditional choices, encounters, and branching consequences.
- **Four survival chronicles** with one major chapter per chronicle on each of the three days.
- **22 completed endings**, plus a separate fallen-run outcome.
- **Six playable classes**, four starting origins, character levels, and spendable talent points.
- **Six potential allies** with distinct roles, relationships, perks, and route-specific opportunities.
- **Tactical combat** with enemy intent, class abilities, Focus management, guarding, healing, and retreat options.
- **Haven-12 development**, including infrastructure projects and shelter resources.
- **Craftable equipment** for weapon, armor, and charm slots.
- **Three faction relationships**, class-specific missions, side operations, and discoverable lore.
- **New Game+** with persistent memories, Echo Shards, permanent upgrades, and hidden choices unlocked through completed runs.
- **Local autosaves** and JSON save export/import.
- **Responsive presentation** with ten local WebP illustrations, large-text and high-contrast settings, optional interface sound, and optional vibration on supported devices.

These counts describe the complete build. A single playthrough visits only part of the available content.

## The three-day chronicles

Four long-form campaigns unfold alongside the original story:

| Chronicle | Focus |
| --- | --- |
| **The Red Road** | Rescue corridors, railways, and the final convoy. |
| **The Last Ward** | Triage, patients, medicine, and the question of whose lives are counted. |
| **The Dead Frequency** | Counterfeit signals, erased records, and memories inside the System. |
| **The Blackwall** | Barricades, divided loyalties, and a city under siege. |

Commit to the same chronicle across all three days to pursue its dedicated conclusion, or change direction to shape a different future. Mixed-route play and later Echo discoveries offer additional possibilities. The original campaign remains playable.

### Act I: Hours 0–24

Survive the initial collapse, meet potential companions, and begin defining your response to the apocalypse. The major chronicle branches begin at Hour 13.

### Act II: Hours 24–52

Operations deepen across rescue routes, medical crises, lost archives, and contested defenses. Resources, relationships, and earlier decisions affect the choices available.

### Act III: Hours 52–72

Face the final crises and decide the fate of the evacuation zone. Three-day commitments, shelter preparations, accumulated knowledge, and personal loyalties can open different conclusions.

The 72-hour timeline is an in-game story clock, not a requirement to play for 72 real hours.

## Create your survivor

Choose a name, starting origin, and combat difficulty. Your origin provides an initial advantage; your class awakens during the story.

### Origins

| Origin | Starting advantage |
| --- | --- |
| **First Responder** | +1 Resolve and +2 medkits. |
| **Street Courier** | +1 Agility and +2 rations. |
| **Network Technician** | +1 Insight and +2 scrap. |
| **Night-Shift Guard** | +1 Might and +15 maximum Health. |

### Classes

| Class | Style | Class ability |
| --- | --- | --- |
| **Vanguard** | Heavy attacks, defense, and disruption. | Shieldbreak |
| **Channeler** | Focus-powered energy attacks. | Arc Flare |
| **Shade** | Mobility, powerful strikes, and evasion. | Vanishing Cut |
| **Lifekeeper** | Endurance, healing, and protecting others. | Pulse Mend |
| **Architect** | Improvised systems and combat shielding. | Overclock |
| **Beastbound** | Unusual bonds, savage attacks, and recovery. | Echo Fang |

### Difficulty

- **Story:** Gentler combat for players focused on the narrative.
- **Survivor:** Balanced combat.
- **Nightmare:** More unforgiving fights.

## How to play

1. Select **Begin Day One** on the title screen.
2. Create your survivor and select **Start Hour Zero**.
3. Read each scene and choose an available action.
4. Monitor Health, Focus, supplies, relationships, and shelter conditions.
5. Use the in-game panels to review your journal, character, party, equipment, factions, and campaign progress.
6. Reach a conclusion, review the results, and return for a different path or New Game+.

Choices can depend on attributes, class, allies, resources, discoveries, earlier decisions, and memories from completed runs. Some branches exclude others. Seeing every route requires multiple playthroughs.

### Combat and progression

Enemies telegraph their intentions. Attack, spend Focus on a class skill, guard, use a medkit, or retreat when an encounter allows it. Guarding restores Focus, and winning a battle restores additional Focus. Level-ups grant talent points that can improve attributes, survivability, and supplies.

### Haven-12, equipment, and factions

Haven-12 is more than a destination. Invest resources in projects such as a field infirmary, reinforced gates, rooftop food beds, an independent radio network, a convoy garage, and a neighborhood council.

Scrap also supports equipment crafting. Weapons, armor, and charms can improve damage, protection, healing, or Focus efficiency. Some items require discoveries or completed objectives.

Your decisions influence relationships with the People of Haven-12, the Perimeter Wardens, and the Unindexed Network. Preparations and faction choices can change later options and the epilogue.

## New Game+ and replayability

Completed endings become persistent memories. Later runs can reveal violet **ECHO** choices and opportunities unavailable on the first playthrough.

The Echo Archive tracks completed endings and permanent progression. Echo Shards can purchase legacy upgrades that improve future starting conditions. Certain secrets require multiple distinct endings and specific discoveries within a run.

Starting a fresh run replaces the active run while preserving permanent unlocks. A fallen run is tracked separately from a completed ending.

## Saves and privacy

The game stores its active run and permanent progression in your browser using `localStorage`.

- Progress belongs to the browser profile and site origin where you play.
- It does not automatically sync between devices or browsers.
- Clearing site data or using temporary browsing storage can remove progress.
- Moving to a different domain or opening a local copy may show a different save.

To back up or transfer progress, open the menu and select **Export Save File**. On the destination browser, select **Import Save File** and choose the exported JSON file. The export includes both the active run and persistent legacy.

**Delete Active Run** removes the current run while preserving permanent progression. **Reset All Progress** removes both.

The game code uses no login, analytics, external scripts, or network API. Save data stays local unless you export and share it. The website host may maintain its own access logs.

## Accessibility and interface options

- Responsive layouts designed for phone screens and larger displays.
- Touch-friendly buttons and visible keyboard focus indicators.
- **Large Reading Text** and **High Contrast** settings.
- Automatic respect for the device's reduced-motion preference.
- Optional locally synthesized interface sound.
- Optional vibration when the browser and device support it.

Sound and vibration are disabled by default. Browser support for individual features can vary.

## Repository contents

```text
.
├── index.html
├── README.md
└── assets/
    ├── anomaly.webp
    ├── apartment.webp
    ├── city.webp
    ├── cityfall.webp
    ├── fall.webp
    ├── metro.webp
    ├── safezone.webp
    ├── tower.webp
    ├── vault.webp
    └── wilds.webp
```

`index.html` contains the interface, styles, story data, game rules, and save logic. The `assets` folder contains the original illustrated backgrounds. Keep both together and preserve their names and relative paths.

## Publish with GitHub Pages

1. Create a GitHub repository, or open the repository where you want to host the game.
2. Extract the game ZIP on your computer.
3. Upload `index.html`, the complete `assets` folder, and this `README.md` to the repository root. Upload the extracted files rather than the ZIP itself.
4. Commit the files to your publishing branch, commonly `main`.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select the branch containing the game and the **/(root)** folder, then select **Save**.
8. Wait for deployment to finish and open the site link shown in Pages settings.

For a project repository, the address normally follows this pattern:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

The game uses relative artwork paths, so it can run under a repository subdirectory without changing those paths. No custom build command is required.

See [GitHub's publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) for configuration details and account availability.

## Play locally

Extract the complete game folder and open `index.html` in a modern browser. Keep the `assets` folder beside it. All required game code and artwork are local; there are no runtime dependencies to download.

For a consistent local website origin, you can serve the folder with any static web server. If Python is installed, open a terminal in the game folder and run:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Browser behavior for storage on directly opened `file://` pages varies. Use save exports for backups. The project does not include a service worker or automatic offline cache, so offline access to a previously visited hosted page is not guaranteed; keep a complete local copy for offline use.

## Troubleshooting

| Problem | What to check |
| --- | --- |
| GitHub Pages shows a 404 | Confirm deployment finished and the selected branch and folder contain `index.html`. |
| The repository shows the README but no playable game | Open the Pages site URL shown under Settings → Pages. |
| Artwork is missing | Confirm all ten `.webp` files are inside `assets/` beside `index.html`, with matching lowercase filenames. |
| The game is one folder deeper than expected | Move `index.html` and `assets/` into the configured publishing folder. |
| Saved progress seems missing | Check the browser profile and site address; import a backup if you moved browsers or domains. |
| Progress does not persist | Confirm browser storage is allowed and you are not relying on a temporary/private browsing session. |
| A hosted update does not appear | Check deployment status, then refresh the page. Export your save before clearing site data. |
| Sound or vibration does not work | Enable it in settings and check device/browser support. |

## Development notes

This is a static, single-page game implemented with vanilla JavaScript. No compilation or package installation is required.

Story and gameplay definitions live inside `index.html`, including scenes, choices, origins, classes, enemies, endings, equipment, shelter projects, and chronicles. Changes should preserve save compatibility and the relative artwork paths where possible.

The browser console exposes a small diagnostic object:

```js
SYSTEMFALL_DEBUG
SYSTEMFALL_DEBUG.validate()
```

It reports the build version and content counts. `validate()` checks direct scene and ending references; an empty array means that check found no missing destinations. It does not replace testing conditional routes, saves, combat, or complete playthroughs.

## Current build verification

The recovered Chronicles v3.0.0 package was checked for:

- ZIP integrity and an `index.html` file at the archive root.
- Preservation of the original game file and all ten artwork files.
- Successful decoding of every included WebP illustration.
- Existing artwork destinations referenced by scene and ending definitions.
- No missing direct scene or ending destinations reported by the built-in validator.
- Title rendering, starting a new run, advancing the opening choice, and writing a save in a JavaScript smoke test with a minimal simulated document.

These checks do not constitute a full visual, accessibility, cross-browser, or all-routes playthrough audit.

---

**Survive the first day. Shape the next two. Remember what the System wants you to forget.**
