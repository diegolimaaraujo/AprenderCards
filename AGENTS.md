<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Game architecture
- Use shared illustrated subjects, not emoji art.
- Retain legacy storage keys — preserves sessions and progress.
- Scope panel colors to menus, never scenes or fauna — preserves educational art.
- Thin mazes with explicit early-level counts and separate invisible bounds — open stages stay contained.
- Freeze maze timers during duels; resolve once with pure blocking rules and notebook/backpack sprites — preserves care and PRO retention.
- Keep gameplay in `MiteGame.tsx`, Three.js in `components/game/three`, and pure rules in `lib/game` — separates logic and presentation.
- Native card geometry uses fauna identity and CSS glow after mount, never nested HTML roots — keeps art aligned.
- Relocate overlapping actors before walls solidify — prevents traps.
- Use shared `CardEmblem` for educational art and native 3D collectibles — keeps DOM out of scenes.
- Share pure card descriptions between digital and print; never reveal math answers — preserves challenges.
- Share examples and cursive through the learning catalogue — consistent educational content without math answers.
- Share indexed card appearances and preprocessed art between digital and print — preserves phase identity.
- Use fitted orthographic desktop view and smoothed mobile follow above controls — preserves readability and movement axes.
- Rankings are per player only; the deprecated group_name column is never written or read — groups were removed from the game.
- Mount the Three.js scene only after play starts and isolate it with a local error boundary — unsupported WebGL must not take down the whole game.
- Build challenges from example sentences; deferred cards return to their position with pickup cooldown — avoids recollection loops.
- Assemble sentence challenges by appending selected pieces with undo and stable sentence-keyed state — avoids drag ambiguity and incidental resets.
- Use instanced port obstacles, PBR stone and four-direction bicycle sprites matching walking facing; isolate the 30-second race — preserves headings and maze timers.
- Share port themes with subject permutations and native landmarks — varies scenery without duplicating gameplay.
- Share deterministic fauna portraits and matched frame palettes — preserves card identity.
- Use shared active dimensions for games, catalogues and BNCC; retain legacy content indexes and stored collections — changes counts without losing cards.
- Show static illustrated heron rewards and phase cards; retain legacy progression fields only for data compatibility — removes armor without losing progress.
- Store leaderboard results by local calendar day and clear the retained daily history every Monday at 00:00 America/Sao_Paulo — supports day-by-day rankings within a weekly competition.
- Persist solved cards by subject/level with daily rankings — powers BNCC summaries.
- Map down/right/left/up to front/right/left/back in the heron walk atlas — prevents reverse walking.
- Share illustrated storm atlases by level across city/duel; classify projectiles by allegiance — preserves art and collisions.
- Merge exterior balustrades; leave exit and tunnel openings — preserves playable bounds.
- Play the CDN opening with MP4/WebM sources and skip/playback/sound controls, isolated from game timers — preserves codec support and film quality.
- Keep A2/C1 progress separate — prevents curricula overwriting each other.
- Keep fauna and legacy ODS state in the round; attach energy to the player and share native jewel geometry — preserves rewards and timers.

- Require two stationary gameplay seconds at a tunnel entrance and leaving the destination before reuse; reset dwell on movement or overlays — prevents involuntary crossings.
- Render care collectibles as generated transparent native Three.js sprites and keep collected-card inspection inside the cards panel — preserves scene lifecycle and the existing pause behavior.
- LogPRO/ProfPRO use fixed `pro_accounts`, bcrypt and opaque tokens checked in every `pro.functions.ts` handler via the service client — email-free accounts require separate auth; no client policies.
- Store phase cards separately in `pro_phase_cards`; combine sources for summaries — scans never overwrite unlocks.
- Share album and PRO card presentation via the catalogue — preserves identity.
- Resolve aura tokens to RGB for Three.js.
- Remove only connected exterior white matte from battle atlases; preserve interior feather highlights and transparent member gaps — avoids silhouettes being filled or erased.
- Serve explanation films with WebM/MP4 sources outside game timers — broad browser compatibility.

- Care collection pauses gameplay in a reward phase and clears held input — prevents popup collisions.
