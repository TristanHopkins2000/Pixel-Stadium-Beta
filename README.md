<p align="center"><img src="images/logo.png" alt="Pixel Stadium Soccer" width="320"></p>

# Pixel Stadium Soccer: Public Beta 1.5.90

A retro pixel football game. You play the matches yourself and run the club around them. This public beta gives you **one full season**: pick any club in any of 33 divisions, and every feature is unlocked so you can try everything.

**Install in two steps: the base game first, then the newest patch on top.**

1. **[Base game 1.5.85 (Windows, full download, 1.1 GB)](https://github.com/TristanHopkins2000/Pixel-Stadium-Beta/releases/tag/v1.5.85-beta)**: you only download this once.
2. **[Newest patch (7 MB)](https://github.com/TristanHopkins2000/Pixel-Stadium-Beta/releases/latest)**: currently 1.5.90.

Please read the [beta conditions](BETA_CONDITIONS.md) before you play.

---

## How to install

The game is installed in two steps: the **base version** (a full download) first, then any **patches** on top. A patch only works on top of its base version, so always install the base first.

### Step 1: install the base version (1.5.85)

1. Download `PixelStadiumSoccer_Beta.zip` from the [1.5.85 release](https://github.com/TristanHopkins2000/Pixel-Stadium-Beta/releases/tag/v1.5.85-beta).
2. Unzip it to a folder. Keep `PixelStadiumSoccer_Beta.exe` and `PixelStadiumSoccer_Beta.pck` together.
3. Run `PixelStadiumSoccer_Beta.exe` once to check it starts. Windows may show a SmartScreen warning because the game is not code-signed. Choose **More info → Run anyway**. The main menu shows `v1.5.85`.

### Step 2: add the newest patch on top

1. Download the patch file from the [latest release](https://github.com/TristanHopkins2000/Pixel-Stadium-Beta/releases/latest), for example `PixelStadiumSoccer_Beta_patch_1.5.90_base_1.5.85.pck`.
2. Make a folder called `patches` next to `PixelStadiumSoccer_Beta.exe` and put the patch file in it:

   ```
   PixelStadiumSoccer_Beta/
   ├── PixelStadiumSoccer_Beta.exe
   ├── PixelStadiumSoccer_Beta.pck
   └── patches/
       └── PixelStadiumSoccer_Beta_patch_1.5.90_base_1.5.85.pck
   ```
3. Start the game. The main menu now shows the new version followed by "(patch)", for example `v1.5.90 (patch)`.

Do not unzip or rename the patch, and do not put it next to the `.pck` of the base game: it must be inside `patches`.

**You need:**
- Windows 10 or 11, 64-bit
- A graphics card with Vulkan support (most cards from 2016 onwards)
- About 1.5 GB of free disk space
- A controller (recommended), or keyboard and mouse

## Updating

- **New patch out?** Download it, put it in the `patches` folder and delete the older patch file. Patches are cumulative: the newest one includes every change since the base version, so you only ever need one.
- **Already on 1.5.85?** You have the base. Just add the newest patch (step 2).
- **Still on 1.5.84?** That version cannot load patches. Install the 1.5.85 base once (step 1), then the patch. Your saves are kept, because they live in `%APPDATA%\Poly Football Stadium Edition\`, not in the game folder.
- **Patch not showing?** Check that the menu says "(patch)". If it does not, the file is in the wrong folder, renamed, or meant for a different base version (the `base_1.5.85` part of the name must match your full download). The game then simply runs the base version.
- **A new base version:** now and then a new full download replaces the base. When that happens, this page says so, and older patches stop applying.

## What's new in 1.5.90

**Medical department.** A new Medical page under Squad. Your club has a head physio, a sports scientist and a club doctor, each with a skill and a speciality, and each season there are new candidates to hire (the best a step above your club's level). The physio gets players back sooner, the sports scientist cuts injuries in training and the warm-up and warns you who is at risk, and the doctor makes the return dates accurate and catches problems in pre-match fitness tests. Leave a post empty and you will feel it.

![The Medical page](screenshots/1.5.90/01_medical.png)

**Training and warm-up injuries.** Rare, and they depend on the player: his fitness, his workload, his age and his injury record. A tired, overworked squad breaks down three times as often. Every now and then a starter pulls up in the warm-up: the best man on the bench takes his place, and the team sheet shows the late change.

![A late change on the team sheet](screenshots/1.5.90/02_late_change.png)

![A training injury report](screenshots/1.5.90/03_training_injury.png)

**A new-look line-up page.** The pitch on the Squad page is drawn like the match team sheet, with every starter in his kit, and the squad list shows each player's kit. Players the sports scientist is worried about carry a RISK tag.

![The Squad page](screenshots/1.5.90/04_squad.png)

**Also:** an injured starter in your line-up is replaced in his own position instead of the whole team being re-picked.

## What's new in 1.5.89

**Penalty run-ups.** Every taker has his own run-up, the same every time he steps up: classic, long (from deep and quick), short (two or three steps), a stutter (he checks his stride a pace from the ball and waits for the keeper), angled (a wide curving approach) or a slow walk-up with a quick last couple of steps. Shootouts too. A taker starting a long or wide run-up no longer loses the kick.

![Penalty run-ups: long, stutter, angled and walk-up](screenshots/1.5.89/01_runups.png)

**Keepers face the ball** at free kicks, corners and throw-ins as well as penalties, from when they reach their spot until the kick, and through the taker's run-up. At a penalty the keeper's "big" stance ends when the run-up starts, so he is set to save when the ball is struck.

![Keeper squared up to a free kick](screenshots/1.5.89/02_keeper_free_kick.png)

**Scarves** thrown onto the pitch are in the colours of the club the fan supports, and show the true club colour (a red scarf used to come out pink).

![Scarves in the home club's red and white](screenshots/1.5.89/03_scarves.png)

## What's new in 1.5.88

**Matchday.** Walk-out mascots are real children, holding their player's hand all the way out of the tunnel. At full time the managers actually shake hands. The tunnel is rebuilt in brick with a club-colour portal and an arched, padded canopy. A substitution made at half time happens in the tunnel, and the new man walks out with the team.

![Walk-out mascots](screenshots/1.5.88/01_walkout.png)

![The managers shake hands](screenshots/1.5.88/02_handshake.png)

![The new tunnel](screenshots/1.5.88/03_tunnel.png)

**Club mascots.** Four new characters matched to the club's nickname: a lion, a fox, an owl and a bull, beside the bear, bird and hound.

![Club mascots](screenshots/1.5.88/04_mascots.png)

**Kits and boots.** Numbers on the back, collar lines, the maker's mark, sock tops, seams, cuffs and boot soles.

![Kit detail](screenshots/1.5.88/05_kits.png)

**Ad boards.** The lettering no longer flickers as the camera moves, and LED boards change together. You can upload your own boards on the TIFO screen: choose "Ad board" and use a **1024 × 128 pixel** PNG or JPG (8:1). They go round your home ground.

![Upload your own ad boards](screenshots/1.5.88/06_ad_board_upload.png)

![Your board in the ground](screenshots/1.5.88/07_custom_board.png)

**Weather and nets.** The weather can change during a match, the way the ground's climate goes in that month: rain starts with a few drops and builds, and eases off the same way. Goal nets are chunkier, and the ball settles in the net after a goal instead of freezing in mid-air.

![A front arrives](screenshots/1.5.88/08_weather.png)

![Goal nets](screenshots/1.5.88/09_nets.png)

**Stories with more life.** Match reports tell the story of the game in varied words, with the turning point, the man of the match and a player calling out the referee when a big decision went against his side. League round-ups lead with the round's stories, and results come in tables.

![Match report](screenshots/1.5.88/10_match_report.png)

**Rivalries.** Every club has rivals (derby and local neighbours) and feuds grow out of heated games. Fans wind each other up in Terrace Talk, and away ends at a rival's ground are more likely to kick off.

![Derby banter](screenshots/1.5.88/11_derby_report.png)

**Fans and the board.** The weekly supporter note leads with what the terraces are talking about, with a table of fan figures. When the supporters ask how the season is going, the answers follow your form. Fans leaving early walk out through exit doors, and on a losing run some throw their scarves onto the pitch. Away fans are back in Argentina.

![Supporter note](screenshots/1.5.88/12_supporter_note.png)

![Fans leaving through the exits](screenshots/1.5.88/13_exits.png)

![Scarves on the pitch](screenshots/1.5.88/18_scarves.png)

**On the pitch.** Players surround the referee after big calls, keepers organise at set pieces and make themselves big for penalties, and penalties are rarer (about 0.16 a match in testing, from 0.4).

![Calling out the referee](screenshots/1.5.88/14_referee.png)

![Keeper at a penalty](screenshots/1.5.88/15_keeper_penalty.png)

**Records and awards.** Club stats shows the club's all-time scorers, appearances and assists and its legends. At the end of the season the Golden Boot, Young Player, Goalkeeper and Playmaker of the Year are chosen from every league.

![Club records](screenshots/1.5.88/16_club_records.png)

![World awards](screenshots/1.5.88/17_world_awards.png)

**Scouting.** Scout reports come with a table of the players found and a "View and sign" link for each.

![Scout report](screenshots/1.5.88/19_scout_report.png)

**Also:** you can no longer hijack a deal for your own player; the numbers above players stay white; placeholder captions are gone.

## What's in the beta

- **One season, any club.** Choose from 660 clubs in 33 divisions across 11 countries and play a full season. The beta ends with a *Beta complete* screen showing your season's stats and celebrations.
- **Everything unlocked.** Build a new stand in your first season, redesign your kits, change jobs, get sacked or resign, and try every menu.
- **Friendlies.** Quick-match friendlies use the English top-flight clubs.

## Features

### On the pitch
- Fast arcade football with planted running, close control and a classic pixel run cycle
- Six skill moves (step-over, drag-back, roulette, body feint, knock-on, flick-up) on the right stick
- Team-mates who attack the box when a winger gets forward, patient CPU build-up play and realistic keepers
- Referees with their own personalities, advantage, cards, penalties and VAR where the competition uses it
- Free kicks and penalties with aiming, throw-ins with several options to choose from, and live player ratings
- Fouls you can see: a shirt pull, a push, a trip or a tackle through the back is acted out before the whistle, and defenders who contain stand off with their arms in
- Keepers come out big in one-on-ones and slide in at your feet: chip them, slip it through their legs or hit it early
- Weather that changes the game: rain, puddles, snow, wind, fog and heat haze

### Matchday atmosphere
- 660 grounds, each built for its club, with crowds, ultras with their own banners, flags and coloured pyro that burns white-hot at the source, and smoke haze that drifts with the wind
- Teams walk out with child mascots, line up and shake hands. Every club has a costumed mascot on the touchline
- Stewards, ball kids, groundsmen, photographers with flashes, and police in each country's uniform
- When the ultras kick off, a riot squad comes out from the side of the stand. Toilet rolls and cups end up on the pitch
- Managers celebrate, sprint down the touchline for late winners and shake hands at full time
- Cup finals end on a podium with medals, the trophy lift and confetti cannons, then the fans invade the pitch

### Your club
- Full career: squad, tactics, transfers, contracts, scouting and an academy with trials, youth contracts and promotion to the first team
- Players come to you with problems and good news. Make promises and keep them, or face the consequences
- Player values rise with form and fall when players are not playing
- Board meetings with real requests, negotiated season objectives and job security
- **Stadium builder:** plan a new stand, watch the building crews work through the season, then name it or sell the naming rights
- Design your own home, away, third and goalkeeper kits
- Every country uses its own currency

### Story and media
- A newspaper that reports your actual games, in each writer's own voice
- Press conferences before matches and an optional TV interview after them. Reporters chase headlines and quote your old answers back at you
- Rival managers play mind games, fans talk about every match, and a team of the week runs each round

## Screenshots

| | |
|---|---|
| ![Main menu](screenshots/01_main_menu.png) | ![Matchday](screenshots/02_matchday.png) |
| ![Walk-out with mascots](screenshots/03_walkout_mascots.png) | ![Cup final](screenshots/04_cup_final.png) |
| ![Mascots](screenshots/05_mascots.png) | ![Stadium builder](screenshots/06_stadium_builder.png) |
| ![Ultras and litter](screenshots/07_ultras_litter.png) | ![Outside the ground](screenshots/08_outside_the_ground.png) |
| ![Career hub](screenshots/09_career_hub.png) | ![Squad](screenshots/10_squad.png) |
| ![League table](screenshots/11_league_table.png) | ![Newspaper](screenshots/12_newspaper.png) |

## Known issues

- This is a beta. Expect bugs, and save often. In testing, the game crashed once while closing; no progress was lost.
- Hair shapes show mainly in the outline of the head (ponytails and braids do not hang over the shirt).
- CPU dribblers mostly use step-overs, and only you can use the flick-up.
- Saves from this beta may not work in later versions.

## Feedback

- **Bugs and ideas:** please open an [issue](https://github.com/TristanHopkins2000/Pixel-Stadium-Beta/issues). Say what you were doing, which club you were managing, and attach a screenshot if you can.
- **In the game:** the *Beta complete* screen lets you write a note. It is saved on your PC as `beta_feedback.txt`, next to your saves in `%APPDATA%\Poly Football Stadium Edition\`, and you can attach it to an issue. The game never sends anything over the internet.

## Notes

- Every club, player, ground, competition, sponsor and broadcaster in the game is fictional. The game is not affiliated with or endorsed by any real club, league or organisation.
- Pixel Stadium Soccer is made with the [Godot Engine](https://godotengine.org). Third-party licences are listed in `THIRD_PARTY_NOTICES.txt`, which is included in the download.
- © 2026 the Pixel Stadium Soccer developer. All rights reserved. The source code is not included in this repository.
