# Injury Watch: 20 Nov 2026

- Generated 2026-11-20 06:56 UTC by `council/injury_watch.py`. This is **a report, not a council verdict**.
- **Injuries:** 108 players in ESPN's injury feed. 37 are out more than 7 days (ESPN est.) with a role of 15+ minutes, on 21 teams.
- **Method:** each team's last 10 finished games, re-scored from ESPN's box scores. Each teammate's minutes and FP are split into games without the absentees against games with them, or against ESPN's projection when they have been out all season.
  - *Best placed* means 3+ minutes gained, ordered by FP/g in the games without the absentees.
  - A pickup is a free agent or waiver player getting 18+ minutes in those games.
- **Checks:** no NBA game was in progress. All 1101 pool players' current, projected, L7, L15, L30 and 2026 averages re-score with `scripts/league_scoring.py` to ESPN's totals (0 mismatches).
- **L7 / L15 / L30:** FP/g over the last 7, 15 and 30 days, games in brackets, from ESPN's rolling splits, re-scored with `scripts/league_scoring.py`. L30 covers every game so far for every player listed, so they equal the season average for now. **A → B** means `council/gamelog.py` dropped an outlier from that window (a bad game 12+ FP under the next worst, or a short game 10+ minutes under the next fewest); B is the average without it.
- **Games** is games left this week (16 Nov–22 Nov) / next week (23 Nov–29 Nov).
- **ESPN est.** is ESPN's estimated return. The skill adds the reported timeline beside it.

## Shortlist

| Player | Opening | Window (reported / ESPN est.) | FP/g without | L7 / L15 / L30 | Min without | Games this wk / next |
|---|---|---|---:|---|---:|---|
| **Ja'Kobe Walter** (TOR) | RJ Barrett (hamstring) and Kawhi Leonard (knee) | Barrett ≥2 weeks, re-evaluated ~3 Dec / 13 Dec; Leonard no timetable reported / 27 Nov | 48.0 (1 game, small sample) | 27.5 (4) / 22.6 (8) / 26.0 (15) | 38.0 | 1 / 3 |
| **Tyrese Proctor** (CLE) | Jaylon Tyson (ankle), Evan Mobley (toe) | Tyson next chance 23 Nov / 23 Nov; Mobley re-evaluated ~23–26 Nov / 29 Nov | 39.5 | 39.5 (4) / 27.7 (9) / 22.6 (15) | 29.0 | 1 / 3 |
| **Isaac Okoro** (CHI) | Caleb Wilson (hand surgery) | 4–6 weeks from 12 Nov / 13 Dec | 30.8 | 30.8 (4) / 22.9 (7) / 16.1 (14) | 32.2 | 2 / 3 |
| **Aday Mara** (OKC) | Holmgren, Jalen Williams, Wallace | Holmgren ~25 Dec–8 Jan / 02 Jan; others late season / 02 Mar | 32.6 | 34.3 (3) / 33.1 (8) / 27.1 (15) | 25.0 | 2 / 3 |
| **Trey Murphy III** (NO, back soon) | his own return; Dejounte Murray out indefinitely | questionable 20 Nov / 20 Nov | — (rate 35.1) | — / 38.5 (2, small sample) / 31.0 (9) | — | 2 / 3 |
| **Ja Morant** (POR, stash) | his own return | re-evaluation ~27 Nov (override 28 Nov) / 01 Dec | — | — / — / 33.8 (4) | — | 1 / 4 |

- **Gains that should last:**
  - **Walter:** Barrett is out for weeks, and Walter started before Barrett got hurt.
  - **Okoro:** Wilson is out 4–6 weeks.
  - **Mara:** OKC's absences run into January or later.
  - Okoro and Mara still sit below our five-lowest floor of 32.0.
- **Proctor's gain** ends when Tyson returns (as early as 23 Nov).
- **Stash:** Murphy (2026 FP/g 41.6) is the best free agent coming back, and he plays twice this week. Morant is next. Our IR slot holds Duren, so a stash costs a bench spot.
- The add/drop call is yours, or the council's.

## Since the last Injury Watch (12 Nov)

- **New teams with long absences:** SA (Dylan Harper, Tobias Harris), CLE (Evan Mobley, Nae'Qwan Tomlin), CHI (Caleb Wilson) and MIL (Ousmane Dieng). Inside teams already listed, the new absences are RJ Barrett (TOR), CJ McCollum (ATL), Stephen Curry (GS) and Lauri Markkanen (UTAH).
- **Pickups:**
  - Joined: Devin Vassell, Tyrese Proctor, Jakob Poeltl, Jamison Battle, Mo Bamba, Duncan Robinson, Brandon Williams, Brayden Burries, Kasparas Jakucionis, Luguentz Dort, Isaac Okoro, Julian Champagnie, Quenton Jackson, Jaylon Tyson, Norchad Omier, John Collins, Tristan da Silva, Brice Sensabaugh, Javon Small, Buddy Hield, Leaky Black, Will Richard, Kenrich Williams, Pete Nance, Kel'el Ware and Allen Graves.
  - Left: Ryan Kalkbrenner, Daniss Jenkins (now ours), Christian Braun, Aaron Wiggins, Derrick Jones Jr., Jared McCain, Royce O'Neale, Collin Murray-Boyles (concussion), Dylan Cardwell and Kobe Sanders.
  - Stayed: Mara, Bassey, Goodwin, Walter, Dunn, Cissoko and Hunter. Huerter is no longer on the pickups list, though he still streams in the matchup report.

## Pickups for us

Free agents and waiver players getting 18+ minutes and 20+ FP/g since an absence opened their role, best first. Waiver players clear in 24 hours. *Also out* names short-term absences in the same games, which inflate the gain until those players return.

Our five lowest current FP/g: Rudy Gobert 25.4 (L7 22.4), Matas Buzelis 25.5 (L7 38.2), Saddiq Bey 30.4 (L7 41.0), Daniss Jenkins 30.5 (L7 36.5), Yves Missi 32.0 (L7 25.7). A pickup at or above **32.0** beats all five.

| Player | NBA | Opening | Games without | Min without | Δ min | FP/g without | Season FP/g | L7 | L15 | L30 | League | Owned | Games |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|---|
| **Ja'Kobe Walter** | TOR | RJ Barrett (13 Dec); also out: Kawhi Leonard (27 Nov) | 1 | 38.0 | +5.3 | **48.0** | 26.0 | 27.5 (4) | 22.6 (8) | 26.0 (15) | Free agent | 12% | 1 / 3 |
| **Devin Vassell** | SA | Dylan Harper (13 Dec), Tobias Harris (03 Dec) | 1 | 32.0 | +3.4 | **42.0** | 27.6 | 25.8 (4) | 28.6 (7) | 27.6 (14) | Free agent | 40% | 1 / 4 |
| **Tyrese Proctor** | CLE | Nae'Qwan Tomlin (29 Nov), Evan Mobley (29 Nov) | 4 | 29.0 | +7.5 | **39.5** | 22.6 | 39.5 (4) | 27.7 (9) | 22.6 (15) | Free agent | 12% | 1 / 3 |
| **Jakob Poeltl** | TOR | RJ Barrett (13 Dec); also out: Kawhi Leonard (27 Nov) | 1 | 29.0 | +4.3 | **37.0** | 25.5 | 24.8 (4) | 31.0 (8) | 25.5 (13) | Free agent | 37% | 1 / 3 |
| **Jamison Battle** | TOR | RJ Barrett (13 Dec); also out: Kawhi Leonard (27 Nov) | 1 | 33.0 | +13.9 | **34.0** | 15.3 | 15.8 (4) | 15.9 (8) | 15.3 (15) | Free agent | 0% | 1 / 3 |
| **Mo Bamba** | UTAH | Lauri Markkanen (04 Jan), Jaren Jackson Jr. (14 Dec); also out: Jusuf Nurkic (27 Nov) | 7 | 23.1 | +6.6 | **33.9** | 31.1 | 42.8 (4) | 33.1 (8) | 31.1 (12) | Waivers | 21% | 2 / 3 |
| **Duncan Robinson** (out, ESPN est. back 27 Nov) | DET | Taurean Prince (13 Dec); also out: Jalen Duren (24 Nov) | 6 | 32.8 | +8.3 | **33.8** | 29.8 | 16.0 (2) | 24.8 (5) | 29.8 (12) | Free agent | 42% | 2 / 3 |
| **Brandon Williams** (out, ESPN est. back 22 Nov) | GS | Stephen Curry (12 Dec), Kristaps Porzingis (02 Jan), Moses Moody (01 Dec), Jimmy Butler III (02 Jan) | 1 | 25.0 | +11.7 | **33.0** | 18.8 | — | 15.0 (3) | 18.8 (10) | Free agent | 1% | 1 / 3 |
| **Brayden Burries** | MIL | Ousmane Dieng (14 Dec) | 5 | 29.2 | +5.4 | **32.8** | 22.8 | 26.5 (4) | 27.2 (9) | 22.8 (16) | Free agent | 11% | 1 / 4 |
| **Aday Mara** | OKC | Cason Wallace (02 Mar), Chet Holmgren (02 Jan), Jalen Williams (02 Mar) | 10 | 25.0 | — | **32.6** | 27.1 | 34.3 (3) | 33.1 (8) | 27.1 (15) | Free agent | 24% | 2 / 3 |
| **Kasparas Jakucionis** | MIL | Ousmane Dieng (14 Dec) | 5 | 21.2 | +9.7 | **31.6** | 20.4 | 44.7 (3) | 22.4 (8) | 20.4 (15) | Free agent | 10% | 1 / 4 |
| **Luguentz Dort** | ATL | CJ McCollum (19 Dec), Mouhamed Gueye (12 Dec); also out: Jock Landale (22 Nov), Kingston Flemings (20 Nov) | 1 | 31.0 | +6.4 | **31.0** | 19.8 | 20.3 (3) | 22.3 (7) | 19.8 (15) | Free agent | 3% | 2 / 2 |
| **Isaac Okoro** | CHI | Caleb Wilson (13 Dec) | 4 | 32.2 | +12.2 | **30.8** | 16.1 | 30.8 (4) | 22.9 (7) | 16.1 (14) | Free agent | 1% | 2 / 3 |
| **Julian Champagnie** | SA | Dylan Harper (13 Dec), Tobias Harris (03 Dec) | 1 | 29.0 | +4.0 | **29.0** | 23.9 | 21.8 (4) | 21.4 (9) | 23.9 (16) | Free agent | 42% | 1 / 4 |
| **Quenton Jackson** | IND | Tyrese Haliburton (28 Nov), Johnny Furphy (02 Jan), Ben Sheppard (02 Jan) | 10 | 24.0 | — | **28.9** | 24.6 | 30.7 (3) | 25.4 (7) | 24.6 (15) | Free agent | 5% | 2 / 3 |
| **Jaylon Tyson** (out, ESPN est. back 23 Nov) | CLE | Nae'Qwan Tomlin (29 Nov), Evan Mobley (29 Nov) | 2 | 32.0 | +9.0 | **28.0** | 19.2 | 28.0 (2) | 20.3 (3) | 19.2 (8) | Free agent | 2% | 1 / 3 |
| **Norchad Omier** | CLE | Nae'Qwan Tomlin (29 Nov), Evan Mobley (29 Nov) | 3 | 18.7 | +11.2 | **27.3** | 18.6 | 27.3 (3) | 18.6 (5) | 18.6 (5) | Free agent | 0% | 1 / 3 |
| **John Collins** | DET | Taurean Prince (13 Dec); also out: Jalen Duren (24 Nov) | 8 | 26.1 | +4.1 | **26.2** | 24.6 | 20.5 (4) | 27.4 (7) | 24.6 (14) | Free agent | 56% | 2 / 3 |
| **Jordan Goodwin** | PHX | Mark Williams (03 Feb) | 6 | 19.3 | — | **25.2** | 26.0 | 25.0 (4) | 27.6 (5) | 26.0 (10) | Free agent | 3% | 1 / 4 |
| **Tristan da Silva** | ORL | Paolo Banchero (29 Nov) | 8 | 31.0 | +9.6 | **24.9** | 25.8 | 25.3 (3) | 25.8 (5) | 25.8 (12) | Free agent | 10% | 2 / 3 |
| **Brice Sensabaugh** | UTAH | Lauri Markkanen (04 Jan), Jaren Jackson Jr. (14 Dec); also out: Jusuf Nurkic (27 Nov) | 7 | 22.3 | +10.3 | **24.9** | 18.4 | 29.8 (4) | 21.0 (9) | 18.4 (16) | Free agent | 6% | 2 / 3 |
| **Charles Bassey** | GS | Stephen Curry (12 Dec), Kristaps Porzingis (02 Jan), Moses Moody (01 Dec), Jimmy Butler III (02 Jan) | 5 | 20.6 | +4.8 | **24.8** | 21.6 | 23.8 (4) | 24.4 (8) | 21.6 (14) | Free agent | 1% | 1 / 3 |
| **Javon Small** | MEM | GG Jackson (18 Jan); also out: Scotty Pippen Jr. (25 Nov) | 4 | 24.0 | +3.0 | **24.2** | 23.4 | 29.2 (5) | 24.6 (8) | 23.4 (9) | Free agent | 4% | 1 / 4 |
| **Buddy Hield** | CHI | Caleb Wilson (13 Dec) | 4 | 20.8 | +9.2 | **24.0** | 16.4 | 24.0 (4) | 22.4 (5) | 16.4 (12) | Free agent | 1% | 2 / 3 |
| **Kris Dunn** | LAC | Bradley Beal (29 Nov), Jordan Miller (02 Mar); also out: Brandon Ingram (21 Nov) | 10 | 25.0 | +3.0 | **23.3** | 26.9 | 17.8 (4) | 19.4 (7) | 26.9 (14) | Free agent | 29% | 1 / 4 |
| **Leaky Black** | SAC | Ben Simmons (01 Oct); also out: Maxime Raynaud (25 Nov) | 8 | 22.9 | — | **23.2** | 19.8 | 21.3 (3) | 21.0 (7) | 19.8 (10) | Free agent | 0% | 2 / 3 |
| **Will Richard** | GS | Stephen Curry (12 Dec), Kristaps Porzingis (02 Jan), Moses Moody (01 Dec), Jimmy Butler III (02 Jan) | 5 | 25.8 | +7.1 | **22.2** | 16.1 | 25.5 (4) | 21.0 (7) | 16.1 (15) | Free agent | 1% | 1 / 3 |
| **Kenrich Williams** | OKC | Cason Wallace (02 Mar), Chet Holmgren (02 Jan), Jalen Williams (02 Mar) | 10 | 24.5 | +9.1 | **22.0** | 17.8 | 31.7 (3) | 21.8 (8) | 17.8 (15) | Free agent | 1% | 2 / 3 |
| **Pete Nance** | MIL | Ousmane Dieng (14 Dec) | 1 | 28.0 | +24.0 | **22.0** | 13.5 | 22.0 (1) | 13.5 (2) → 22.0 (1) | 13.5 (2) → 22.0 (1) | Free agent | 0% | 1 / 4 |
| **De'Andre Hunter** (day to day, ESPN est. back 20 Nov) | SAC | Ben Simmons (01 Oct); also out: Maxime Raynaud (25 Nov) | 8 | 35.6 | +8.0 | **21.4** | 20.8 | 27.5 (2) | 22.0 (5) | 20.8 (12) | Free agent | 6% | 2 / 3 |
| **Sidy Cissoko** | POR | Vit Krejci (12 Jan), Ja Morant (01 Dec), Shaedon Sharpe (02 Mar) | 8 | 27.1 | +5.6 | **20.5** | 19.4 | 20.0 (4) | 21.3 (9) | 19.4 (15) | Free agent | 1% | 1 / 4 |
| **Kel'el Ware** | MIL | Ousmane Dieng (14 Dec) | 5 | 19.6 | +3.2 | **20.2** | 22.9 | 26.8 (4) | 19.3 (9) | 22.9 (16) | Free agent | 53% | 1 / 4 |
| **Allen Graves** | TOR | RJ Barrett (13 Dec); also out: Kawhi Leonard (27 Nov) | 1 | 31.0 | +17.7 | **20.0** | 13.5 | 11.2 (4) | 12.1 (8) | 13.5 (15) | Free agent | 0% | 1 / 3 |

### Notes

- **Ja'Kobe Walter** (TOR): started 18 Nov with 38 minutes and 18/7/6. He is the presumptive starting SG while Barrett (≥2 weeks) and Leonard are out, and he also started on 28 Oct, so the role isn't tied to Barrett alone ([RotoWire](https://www.rotowire.com/basketball/headlines/jakobe-walter-news-fills-stat-sheet-in-defeat-539911); [NBC Sports, 18 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/raptors-start-iq-walter-battle-collin-poeltl)). His "games without" figure rests on 1 game (small sample).
- **Devin Vassell** (SA): already a starter. He has his own groin/adductor problem and is listed questionable for Fri 20 Nov ([Fox Sports](https://www.foxsports.com/nba/devin-vassell-player)). Small sample (1 game without).
- **Tyrese Proctor** (CLE): starting until Tyson returns (next chance 23 Nov). Override: role 27 min until 22 Nov ([NBC Sports, 18 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/cavs-start-harden-mitchell-proctor-mario-allen)). L7 39.5 (4) is 16.9 over his season average on the starting role.
- **Jakob Poeltl** and **Jamison Battle** (TOR): their 18 Nov starts came with Barnes resting. Barnes plays 20 Nov, so both go back to the bench ([RotoWire, 18 Nov](https://www.rotowire.com/basketball/headlines/jakob-poeltl-news-back-in-starting-lineup-539839)).
- **Mo Bamba** (UTAH): his 30-minute role ended when Jaxson Hayes returned on 18 Nov. He played 22 minutes that night ([NBC Sports, 19 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jaxson-hayes-knee-plays-25-minutes-in-return)). L7 42.8 (4) is 11.7 over the season average, from those games.
- **Brayden Burries** (MIL): starting for Dieng (no timetable reported). L7 26.5 is 3.7 over the season average, from the starter's minutes.
- **Kasparas Jakucionis** (MIL): his spike came with Ryan Rollins ill. Rollins was back on 19 Nov and Jakucionis played 22 minutes ([FantasyPros, 19 Nov](https://www.fantasypros.com/nba/news/621206/ryan-rollins-illness-off-injury-report-thursday.php)). L7 44.7 (3) is 24.3 over; that window is over.
- **Isaac Okoro** (CHI): starting for Caleb Wilson (4–6 weeks). He played 25 minutes in the 18 Nov blowout ([NBC Sports, 16 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-16/chi-starts-giddey-powell-okoro-buzelis-smith)). L7 30.8 (4) is 14.7 over the season average, on the start.
- **Luguentz Dort** (ATL): not starting. Aaron Wiggins took McCollum's spot ([ClutchPoints](https://clutchpoints.com/nba/atlanta-hawks/why-hawks-will-turn-lu-dort-aaron-wiggins-losing-cj-mccollum-injury)).
- **Brice Sensabaugh** (UTAH): his L7 29.8 (4) is 11.4 over, and includes a 40-point outlier on 17 Nov. He still comes off the bench, but with more minutes while Markkanen is out (≥4 weeks) ([CBS Sports](https://www.cbssports.com/fantasy/basketball/news/jazzs-brice-sensabaugh-dazzles-with-4011-double-double/)).

## Injured and available, back soon

Free agents and waiver players ESPN expects back within 14 days, worth 25+ FP/g on their current, projected or last-season average.

- **Our IR slot:** taken by Jalen Duren. A stash costs a bench spot until it frees up.

| Player | NBA | Injury | ESPN est. | Days | Current FP/g | L7 | L15 | L30 | Projected | 2026 | League | Owned | Games |
|---|---|---|---|---:|---:|---:|---:|---:|---:|---:|---|---:|---|
| **Trey Murphy III** | NO | Knee Tendinitis | 20 Nov | 0 | 31.0 | — | 38.5 (2) | 31.0 (9) | 36.8 | 41.6 | Free agent | 78% | 2 / 3 |
| **Zach Edey** | MEM | Ankle | 21 Nov | 1 | 25.0 | 36.0 (2) | 26.2 (6) | 25.0 (12) | 33.2 | 39.5 | Free agent | 42% | 1 / 4 |
| **Dejounte Murray** | NO | Ankle | 27 Nov | 7 | 30.6 | — | 20.8 (5) | 30.6 (9) | 39.0 | 36.5 | Free agent | 76% | 2 / 3 |
| **Ja Morant** | POR | Left Hamstring | 01 Dec | 11 | 33.8 | — | — | 33.8 (4) | 37.5 | 36.0 | Free agent | 80% | 1 / 4 |
| **Jusuf Nurkic** | UTAH | Right Foot Strain | 27 Nov | 7 | — | — | — | — | 27.6 | 36.7 | Free agent | 6% | 2 / 3 |
| **Grayson Allen** | CHA | Concussion | 23 Nov | 3 | 26.8 | 27.5 (2) | 31.6 (5) | 26.8 (13) | 26.6 | 31.2 | Free agent | 23% | 1 / 3 |
| **Scotty Pippen Jr.** | MEM | Back Soreness | 25 Nov | 5 | 14.2 | — | — | 14.2 (5) | 30.6 | 27.1 | Free agent | 8% | 1 / 4 |
| **Tobias Harris** | SA | Left Calf Strain | 03 Dec | 13 | — | — | — | — | 30.1 | 28.0 | Free agent | 40% | 1 / 4 |
| **Duncan Robinson** | DET | Left Quadriceps Strain | 27 Nov | 7 | 29.8 | 16.0 (2) | 24.8 (5) | 29.8 (12) | 21.6 | 23.1 | Free agent | 42% | 2 / 3 |
| **Peyton Watson** | CLE | Back Bruise | 20 Nov | 0 | 24.2 | 9.5 (2) | 21.3 (6) | 24.2 (12) | 29.3 | 29.8 | Free agent | 36% | 1 / 3 |
| **Jerami Grant** | MEM | Left Calf | 21 Nov | 1 | 20.3 | 18.2 (4) → 23.7 (3) | 21.4 (8) → 24.1 (7) | 20.3 (15) → 21.6 (14) | 27.0 | 28.8 | Free agent | 10% | 1 / 4 |
| **Myles Turner** | MIL | Left Shoulder Bruise | 21 Nov | 1 | 26.6 | 32.3 (3) | 26.3 (7) | 26.6 (14) | 28.4 | 28.6 | Free agent | 45% | 1 / 4 |
| **Draymond Green** | GS | Rest | 22 Nov | 2 | 24.0 | 20.7 (3) | 26.0 (7) | 24.0 (13) | 28.5 | 26.5 | Free agent | 23% | 1 / 3 |
| **Jaylon Tyson** | CLE | Right Ankle | 23 Nov | 3 | 19.2 | 28.0 (2) | 20.3 (3) | 19.2 (8) | 25.6 | 28.3 | Free agent | 2% | 1 / 3 |
| **Maxime Raynaud** | SAC | Right Knee Dislocated | 25 Nov | 5 | — | — | — | — | — | 28.1 | Free agent | 2% | 2 / 3 |
| **Bennedict Mathurin** | NO | Left Foot Plantar Fasciitis | 27 Nov | 7 | 8.8 | -3.0 (1) | 3.8 (5) | 8.8 (12) | 25.1 | 27.6 | Free agent | 6% | 2 / 3 |
| **Dereck Lively II** | DAL | Right Foot Surgery | 27 Nov | 7 | — | — | — | — | 27.4 | 21.3 | Free agent | 4% | 2 / 2 |
| **Precious Achiuwa** | SAC | Left Lower Leg Bruise | 20 Nov | 0 | 25.4 | -3.0 (1) | 15.8 (5) | 25.4 (12) | 24.1 | 27.0 | Free agent | 14% | 2 / 3 |
| **Robert Williams III** | POR | Rest | 21 Nov | 1 | 24.4 | 19.7 (3) | 25.1 (7) | 24.4 (12) | 26.9 | 26.6 | Free agent | 4% | 1 / 4 |
| **Jock Landale** | ATL | Right Hip Inflammation | 22 Nov | 2 | 16.8 | 19.0 (1) | 18.0 (2) | 16.8 (9) → 18.9 (8) | — | 25.8 | Free agent | 0% | 2 / 2 |
| **Collin Murray-Boyles** | TOR | Concussion | 23 Nov | 3 | 24.0 | 26.5 (4) | 26.9 (7) | 24.0 (14) | 24.8 | 25.6 | Free agent | 13% | 1 / 3 |
| **Bradley Beal** | LAC | Right Knee Inflammation | 29 Nov | 9 | — | — | — | — | 25.6 | 10.5 | Free agent | 1% | 1 / 4 |
| **T.J. McConnell** | IND | Right Hamstring Strain | 20 Nov | 0 | 22.5 | 29.7 (3) | 22.5 (6) | 22.5 (6) | 24.4 | 25.5 | Free agent | 8% | 2 / 3 |

### Notes

- **Trey Murphy III** (ESPN est. 20 Nov): questionable Fri 20 Nov vs OKC after six games out with patellar tendinopathy in both knees; no minutes limit reported. [NBC Sports, 2026-11-19](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/trey-murphy-knee-questionable-friday-vs-thunder). He already missed a 14 Nov target. [RotoWire, 2026-11-13](https://www.rotowire.com/basketball/headlines/trey-murphy-injury-wont-play-friday-538912)
- **Zach Edey** (ESPN est. 21 Nov): sat 19 Nov (2nd night of a back-to-back, ankle injury management) after returning 16 Nov; expect continued back-to-back rest. [NBC Sports, 2026-11-19](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/zach-edey-ankle-ruled-out-thursday-vs-warriors)
- **Peyton Watson** (ESPN est. 20 Nov): lower-back bruise from a 16 Nov fall; questionable Fri 20 Nov vs IND. [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/cavaliers-peyton-watson-iffy-for-friday/)
- **Jerami Grant** (ESPN est. 21 Nov): left after 5 min on 19 Nov (left calf), no timetable reported; calf injuries often outlast a 2-day estimate. [NBC Sports, 2026-11-19](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jerami-grant-calf-wont-return-thursday-vs-gsw)
- **Draymond Green** (ESPN est. 22 Nov): sat 19 Nov at MEM (2nd night of a back-to-back, right elbow management); stays a starter. [CBS Sports, ~2026-11-19](https://www.cbssports.com/fantasy/basketball/news/warriors-draymond-green-confirmed-out-thursday/)
- **Dereck Lively II** (ESPN est. 27 Nov): still out (right foot surgery), not practicing as of 5 Nov, week-to-week; no timetable reported; ESPN's date looks early. [CBS Sports](https://www.cbssports.com/fantasy/basketball/news/mavericks-dereck-lively-still-sidelined/)
- **Collin Murray-Boyles** (ESPN est. 23 Nov): entered concussion protocol 19 Nov after leaving 18 Nov vs WSH; no timetable reported. Barrett out at least two weeks (hamstring). [CP24, 2026-11-19](https://www.cp24.com/news/sports/2026/11/19/rj-barrett-and-collin-murray-boyles-added-to-toronto-raptors-injured-list/)
- **Bradley Beal** (ESPN est. 29 Nov): Lue on 12 Nov: three straight on-court days bring "not good results"; not close, no date; ESPN's date looks early. [BasketNews, 2026-11-13](https://basketnews.com/news-259398-worrisome-injury-update-for-bradley-beal-not-close-to-return-to-the-court.html)
- **De'Andre Hunter** (ESPN est. 20 Nov): questionable Fri 20 Nov vs LAL (left hip soreness), recurring. [CBS Sports, ~2026-11-19](https://www.cbssports.com/fantasy/basketball/news/kings-deandre-hunter-questionable-versus-lakers/)
- **Donte DiVincenzo** (ESPN est. 02 Apr): no timeline; his doctor expects him back this season. [NBC Sports, 2026-09-04](https://www.nbcsports.com/fantasy/basketball/player-news/2026-09-04/gm-divincenzo-achilles-lacks-return-timeline)
- **Brandon Ingram** (ESPN est. 21 Nov): ruled out 19 Nov vs SA; no debut date or minutes limit reported; Lue: "I hope but don't expect." [NBC Sports, 2026-11-18](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/brandon-ingram-achilles-out-thursday-vs-spurs) · [ClutchPoints, 2026-11-15](https://clutchpoints.com/nba/los-angeles-clippers/clippers-brandon-ingram-injury-update-teases-return-coming-very-soon)
- **Dejounte Murray** (ESPN est. 27 Nov): out indefinitely while he waits for a trade ([ESPN, 13 Nov](https://www.espn.com/nba/story/_/id/50473732/sources-dejounte-murray-wants-trade-pelicans)).
- **Ja Morant** (ESPN est. 01 Dec): re-evaluation ~27 Nov; override return 28 Nov ([Trail Blazers, 30 Oct](https://www.nba.com/blazers/news/ja-morant-injury-update)).
- **Jusuf Nurkic** (ESPN est. 27 Nov): week-to-week, out 20 Nov; override return 27 Nov ([CBS Sports, 19 Nov](https://www.cbssports.com/fantasy/basketball/news/jazzs-jusuf-nurkic-not-ready-to-return-friday/)).
- **Grayson Allen** (ESPN est. 23 Nov): concussion protocol, no timetable reported ([CBS Sports, 19 Nov](https://www.cbssports.com/fantasy/basketball/news/hornets-grayson-allen-out-for-friday/)).
- **Scotty Pippen Jr.** (ESPN est. 25 Nov): week-to-week, no timetable reported ([Yahoo, 19 Nov](https://sports.yahoo.com/articles/warriors-vs-grizzlies-injury-report-234754065.html)).
- **Tobias Harris** (ESPN est. 03 Dec): not before December ([Yahoo, ~18 Nov](https://sports.yahoo.com/articles/tobias-harris-potential-return-timeline-180822753.html)).
- **Duncan Robinson** (ESPN est. 27 Nov): re-evaluation ~24 Nov ([NBC Sports, 17 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-17/duncan-robinson-quad-out-at-least-a-week)).
- **Maxime Raynaud** (ESPN est. 25 Nov), **Bennedict Mathurin** (ESPN est. 27 Nov), **Jaylon Tyson** (ESPN est. 23 Nov), **Myles Turner** (ESPN est. 21 Nov), **Precious Achiuwa** (ESPN est. 20 Nov; doubtful 20 Nov), **T.J. McConnell** (ESPN est. 20 Nov; probable), **Robert Williams III** (ESPN est. 21 Nov; rest) and **Jock Landale** (ESPN est. 22 Nov): see the news watch for the reported timelines (`docs/analysis/20261120-news-watch.md`).

## Yet to play this season

Injured players with no game yet this season, worth 25+ FP/g on ESPN's projection or last season, by expected return. None has played this season, so none has an L7, L15 or L30. Their value is last season and the projection. Our five-lowest floor is 32.0.

| Player | NBA | Injury | ESPN est. | Days | Projected FP/g (min) | 2026 FP/g (GP) | League | Owned | Games |
|---|---|---|---|---:|---:|---:|---|---:|---|
| **Brandon Ingram** | LAC | Right Achilles Surgery | 21 Nov | 1 | 38.5 (35.3) | 36.5 (77) | Melbourne poopoo | 66% | 1 / 4 |
| **Maxime Raynaud** | SAC | Right Knee Dislocated | 25 Nov | 5 | — (—) | 28.1 (74) | Free agent | 2% | 2 / 3 |
| **Dereck Lively II** | DAL | Right Foot Surgery | 27 Nov | 7 | 27.4 (23.6) | 21.3 (7) | Free agent | 4% | 2 / 2 |
| **Jusuf Nurkic** | UTAH | Right Foot Strain | 27 Nov | 7 | 27.6 (23.1) | 36.7 (41) | Free agent | 6% | 2 / 3 |
| **Bradley Beal** | LAC | Right Knee Inflammation | 29 Nov | 9 | 25.6 (25.3) | 10.5 (6) | Free agent | 1% | 1 / 4 |
| **Tobias Harris** | SA | Left Calf Strain | 03 Dec | 13 | 30.1 (30.5) | 28.0 (63) | Free agent | 40% | 1 / 4 |
| **Jimmy Butler III** | GS | Right Knee Surgery | 02 Jan | 43 | 38.8 (32.4) | 41.6 (38) | Free agent | 28% | 1 / 3 |
| **Kristaps Porzingis** | GS | Illness | 02 Jan | 43 | 36.9 (27.7) | 32.3 (32) | Free agent | 31% | 1 / 3 |
| **Mark Williams** | PHX | Left Shoulder Surgery | 03 Feb | 75 | 31.0 (24.9) | 31.9 (60) | Free agent | 6% | 1 / 4 |
| **Shaedon Sharpe** | POR | Right Knee Surgery | 02 Mar | 102 | 24.8 (25.4) | 31.2 (50) | Free agent | 6% | 1 / 4 |
| **Donte DiVincenzo** | MIN | Right Achilles Surgery | 02 Apr | 133 | 23.0 (24.1) | 29.4 (82) | Free agent | 2% | 1 / 4 |

### Notes

- **Brandon Ingram** (rostered, Melbourne poopoo): no debut date reported; Lue: "I hope but don't expect" ([ClutchPoints, 15 Nov](https://clutchpoints.com/nba/los-angeles-clippers/clippers-brandon-ingram-injury-update-teases-return-coming-very-soon)).
- **Lively** and **Beal**: ESPN's dates look early (see above). Porzingis has no timetable reported, Moody is out until midseason, and Butler is aiming for early 2027 (see GS below). Mark Williams, Sharpe and DiVincenzo match ESPN's dates.

## Our injured players

- **Cade Cunningham** (DET): Day-To-Day, Right Knee Soreness; ESPN est. back 20 Nov. Reported: expected to play Fri 20 Nov vs TOR ([CBS Sports, 19 Nov](https://www.cbssports.com/fantasy/basketball/news/pistons-cade-cunningham-expected-to-play-friday/)).
- **Jalen Duren** (DET): Out, Right Hamstring Strain; ESPN est. back 24 Nov. Reported: two-week re-evaluation from 8 Nov; "re-evaluated next week" as of 20 Nov; no return date ([Detroit News, 8 Nov](https://www.detroitnews.com/story/sports/nba/pistons/2026/11/08/pistons-all-star-jalen-duren-out-another-two-weeks-with-hamstring-strain/92677147007/); [Heavy, 20 Nov](https://heavy.com/sports/nba/detroit-pistons/injury-report-vs-raptors-november-20/)).
- **Kawhi Leonard** (TOR): Out, Left Knee Inflammation; ESPN est. back 27 Nov. Reported: no structural damage, still "reconditioning", no timetable reported ([Global News, 20 Nov](https://globalnews.ca/news/12158569/barrett-murray-boyles-put-on-raptors-injured-list)).

## Who takes the minutes, team by team

### GS

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Jimmy Butler III | Right Knee Surgery | 02 Jan | 32.4 | 41.6 | Free agent |
| Stephen Curry | Right Abdomen | 12 Dec | 32.0 | 44.4 | Lauri Birds |
| Kristaps Porzingis | Illness | 02 Jan | 27.7 | 32.3 | Free agent |
| Moses Moody | Left Knee Surgery | 01 Dec | 25.7 | 24.8 | Free agent |

- **Reported timeline:** Curry: oblique tear (11 Nov), re-evaluation in two weeks (~26 Nov), close to a month per Charania ([Warriors.com, 12 Nov](https://www.nba.com/warriors/news/stephen-curry-injury-update-11-12-26)). Moody: "not expected back until midseason" after patellar tendon surgery, so ESPN's 01 Dec is too early ([ESPN, Nov](https://espn.com/nba/story/_/id/50503111/steph-curry-warriors-race-injuries)). Porzingis: stepped away (POTS symptoms), no timetable reported (same source). Butler: ACL surgery 9 Feb, early 2027 hoped for ([CBS Sports](https://www.cbssports.com/fantasy/basketball/news/warriors-jimmy-butler-still-months-away-from-returning/)). Brandon Williams (hamstring): re-evaluated Sat 21 Nov, could return Sun 22 Nov ([Warriors.com, 18 Nov](https://www.nba.com/warriors/news/brandon-williams-injury-update-11-18-26)).

Last 10 games: 5 game(s) without them, 5 with them.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Brandon Williams (out, ESPN est. back 22 Nov) | PG/SG | 1 | 25.0 | +11.7 | 0 | **33.0** | 15.0 | — | 15.0 (3) | 18.8 (10) | Free agent | 1% |
| Charles Bassey | C | 5 | 20.6 | +4.8 | 3 | **24.8** | 26.6 | 23.8 (4) | 24.4 (8) | 21.6 (14) | Free agent | 1% |
| Will Richard | SG/SF | 5 | 25.8 | +7.1 | 1 | **22.2** | 14.8 | 25.5 (4) | 21.0 (7) | 16.1 (15) | Free agent | 1% |
| LJ Cryer | PG | 5 | 16.2 | +6.2 | 2 | **14.8** | 8.2 | 18.8 (4) | 15.6 (7) | 10.8 (13) | Free agent | 0% |

### OKC

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Jalen Williams | Left Leg Fracture | 02 Mar | 32.8 | 26.3 | Free agent |
| Chet Holmgren | Right Knee | 02 Jan | 30.0 | 40.0 | Free agent |
| Cason Wallace | Left Shoulder Surgery | 02 Mar | 26.6 | 18.7 | Free agent |

- **Reported timeline:** Holmgren: small patellar tendon tear, 8–10 weeks from 30 Oct (~25 Dec–8 Jan) ([NBA.com](https://www.nba.com/news/chet-holmgren-out-8-10-weeks-with-patellar-tendon-tear)). Jalen Williams and Wallace: both to be re-evaluated before the end of the regular season, so ESPN's 02 Mar looks early ([Yahoo, 28 Oct](https://sports.yahoo.com/nba/breaking-news/article/thunders-jalen-williams-has-surgery-on-ankle-fractured-fibula-will-be-reevaluated-before-end-of-season-011001403.html); [Yahoo, 30 Oct](https://sports.yahoo.com/articles/cason-wallace-shoulder-surgery-evaluated-011900324.html)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Aday Mara | C | 10 | 25.0 | — | 5 | **32.6** | — | 34.3 (3) | 33.1 (8) | 27.1 (15) | Free agent | 24% |
| Kenrich Williams | SF | 10 | 24.5 | +9.1 | 8 | **22.0** | 14.2 | 31.7 (3) | 21.8 (8) | 17.8 (15) | Free agent | 1% |
| Bennett Stirtz | PG | 10 | 20.2 | — | 0 | **18.8** | — | 10.0 (3) | 19.4 (8) | 14.1 (15) | Free agent | 1% |
| Micah Peavy | SF | 8 | 17.9 | — | 0 | **11.4** | — | 14.0 (1) | 12.2 (6) | 10.1 (9) | Free agent | 0% |
| 5105800 |  | 6 | 12.3 | — | 0 | **6.8** | — | — | — | — | — | 0% |

### POR

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Ja Morant | Left Hamstring | 01 Dec | 29.5 | 33.8 | Free agent |
| Shaedon Sharpe | Right Knee Surgery | 02 Mar | 29.4 | 31.2 | Free agent |
| Vit Krejci | Left Ankle | 12 Jan | 25.7 | 7.0 | Free agent |

- **Reported timeline:** Morant: Grade 2 hamstring, re-evaluation four weeks from 30 Oct (~27 Nov); override return 28 Nov ([Trail Blazers, 30 Oct](https://www.nba.com/blazers/news/ja-morant-injury-update)). Krejci: ankle fracture, at least 8 weeks from 11 Nov ([Athlon, 19 Nov](https://athlonsports.com/nba/portland-trail-blazers/final-injury-report-for-trail-blazers-bucks-will-deni-avdija-toumani-camara-play)). Sharpe: meniscus surgery, at least 6 months ([Yahoo](https://sports.yahoo.com/articles/blazers-vs-bucks-3-things-225403965.html)).

Last 10 games: 8 game(s) without them, 2 with them.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Sidy Cissoko | SG | 8 | 27.1 | +5.6 | 6 | **20.5** | 20.5 | 20.0 (4) | 21.3 (9) | 19.4 (15) | Free agent | 1% |
| Chris Youngblood (out, ESPN est. back 21 Nov) | SG | 3 | 18.3 | +8.8 | 0 | **16.7** | 5.5 | — | 12.5 (4) | 10.5 (6) | Free agent | 0% |
| 4703889 |  | 5 | 15.6 | — | 2 | **10.8** | — | — | — | — | — | 0% |

### IND

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Tyrese Haliburton | Left Hamstring Strain | 28 Nov | 33.1 | 53.2 | Lauri Birds |
| Ben Sheppard | Left Knee | 02 Jan | 21.4 | 5.0 | Free agent |
| Johnny Furphy | Right Knee Surgery | 02 Jan | 18.3 | 14.2 | Free agent |

- **Reported timeline:** Haliburton: left hamstring, "progressing" per Carlisle (11 Nov), no timetable reported ([Bleacher Report](https://bleacherreport.com/articles/25532370-tyrese-haliburton-injury-return-timeline-updated-pacers-rick-carlisle-amid-hamstring-issue)). Sheppard (meniscus surgery) and Furphy (torn ACL): no timetable reported. Quenton Jackson's start comes from Andrew Nembhard (hip, questionable 20 Nov), whose return ends it ([NBA.com, 18 Nov](https://www.nba.com/pacers/news/preview-pacers-rockets-261118)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Andrew Nembhard (day to day, ESPN est. back 20 Nov) | PG/SG | 7 | 33.7 | +3.0 | 7 | **33.1** | 28.2 | 12.0 (1) | 31.8 (5) | 33.2 (11) | Matt Wright's Foxies | 68% |
| Quenton Jackson | PG/SG | 10 | 24.0 | — | 3 | **28.9** | — | 30.7 (3) | 25.4 (7) | 24.6 (15) | Free agent | 5% |
| Braden Smith (day to day, ESPN est. back 20 Nov) | PG | 7 | 17.0 | — | 4 | **18.4** | — | 30.0 (1) | 17.5 (4) | 14.6 (9) | Free agent | 0% |
| Jay Huff | C | 9 | 16.9 | — | 3 | **16.1** | — | 18.3 (3) | 13.8 (6) | 16.1 (13) | Free agent | 0% |
| Jalen Slawson | SF | 9 | 15.9 | — | 1 | **15.9** | — | 16.3 (3) | 13.7 (6) | 14.5 (13) | Free agent | 0% |

### MIN

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Anthony Edwards | Right Knee Surgery | 21 Dec | 35.8 | 52.5 | Melbourne poopoo |
| Donte DiVincenzo | Right Achilles Surgery | 02 Apr | 30.5 | 29.4 | Free agent |

- **Reported timeline:** Edwards: knee surgery, out more than two months ([Yahoo, 15 Nov](https://sports.yahoo.com/articles/rudy-gobert-1-point-night-071557236.html)). DiVincenzo: Achilles surgery, his doctor expects him back this season, no date ([NBC Sports, 4 Sep](https://www.nbcsports.com/fantasy/basketball/player-news/2026-09-04/gm-divincenzo-achilles-lacks-return-timeline)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Jaden McDaniels | SF/PF | 10 | 34.7 | +3.0 | 10 | **38.3** | 29.7 | 42.8 (5) | 41.4 (8) | 38.6 (16) | Melbourne poopoo | 91% |
| Ayo Dosunmu | PG/SG | 10 | 33.9 | +4.5 | 10 | **37.8** | 30.4 | 29.4 (5) | 33.2 (8) | 34.8 (16) | Cream Abdul-Yammar | 84% |
| Jonathan Kuminga | SF/PF | 9 | 31.9 | +4.6 | 9 | **28.0** | 26.3 | 28.2 (4) | 26.0 (7) | 28.9 (15) | Dr White Slong | 59% |
| Joan Beringer | C | 10 | 17.4 | — | 1 | **18.8** | — | 19.0 (5) | 16.1 (8) | 19.3 (16) | Free agent | 2% |
| Jaylen Clark (out, ESPN est. back 29 Nov) | SG | 7 | 18.3 | +5.2 | 0 | **14.7** | 9.4 | 12.5 (2) | 14.6 (5) | 11.9 (12) | Free agent | 0% |

### UTAH

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Lauri Markkanen | Right Hand Fracture | 04 Jan | 34.4 | 32.5 | Free agent |
| Jaren Jackson Jr. | Right Knee | 14 Dec | 31.4 | 27.0 | Free agent |

- **Reported timeline:** Markkanen: two nondisplaced hand fractures, at least 4 weeks from 11 Nov (~9 Dec earliest, before ESPN's 04 Jan) ([Salt Lake Tribune, 11 Nov](https://www.sltrib.com/sports/jazz/2026/11/11/lauri-markkanen-injury-jazz/)). Jackson Jr.: MCL tear, not before December ([SI, ~18 Nov](https://si.com/nba/jazz/onsi/jazz-vs-lakers-injury-report-delivers-big-jaxson-hayes-update)). Nurkic: week-to-week, out 20 Nov; override return 27 Nov ([CBS Sports, 19 Nov](https://www.cbssports.com/fantasy/basketball/news/jazzs-jusuf-nurkic-not-ready-to-return-friday/)).

Last 10 games: 7 game(s) without them, 3 with them.

Also out in those games, so part of the gain is theirs: Jusuf Nurkic (right foot strain; ESPN est. 27 Nov).

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Mo Bamba | C | 7 | 23.1 | +6.6 | 3 | **33.9** | 27.0 | 42.8 (4) | 33.1 (8) | 31.1 (12) | Waivers | 21% |
| Brice Sensabaugh | SG/SF | 7 | 22.3 | +10.3 | 0 | **24.9** | 8.0 | 29.8 (4) | 21.0 (9) | 18.4 (16) | Free agent | 6% |
| Isaiah Collier | PG | 5 | 15.6 | +6.3 | 0 | **14.8** | 7.7 | 8.5 (2) | 11.7 (7) | 14.1 (14) | Free agent | 2% |
| Svi Mykhailiuk | SG | 7 | 20.3 | +5.3 | 0 | **13.7** | 3.7 | 18.8 (4) | 11.8 (9) | 10.8 (16) | Free agent | 0% |

### SA

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Dylan Harper | Hip Soreness | 13 Dec | 31.7 | 36.4 | Melbourne poopoo |
| Tobias Harris | Left Calf Strain | 03 Dec | 30.5 | 28.0 | Free agent |

- **Reported timeline:** Harper: hip external rotator strain, 2–3 weeks (team) or 1–3 (ESPN sources), so ~3–10 Dec, before ESPN's 13 Dec ([ESPN, ~19 Nov](https://www.espn.com/nba/story/_/id/50533303/sources-spurs-dylan-harper-1-3-weeks-hip-strain)). Harris: calf, unlikely before December ([Yahoo, ~18 Nov](https://sports.yahoo.com/articles/tobias-harris-potential-return-timeline-180822753.html)).

Last 10 games: 1 game(s) without them, 9 with them.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Victor Wembanyama | C | 1 | 33.0 | +4.7 | 1 | **59.0** | 72.0 | 60.0 (4) | 74.0 (9) | 69.1 (16) | Cream Abdul-Yammar | 100% |
| Stephon Castle | PG/SG | 1 | 33.0 | +3.8 | 1 | **59.0** | 33.9 | 48.0 (4) | 36.7 (9) | 34.8 (16) | Melbourne poopoo | 96% |
| Devin Vassell | SG/SF | 1 | 32.0 | +3.4 | 1 | **42.0** | 24.9 | 25.8 (4) | 28.6 (7) | 27.6 (14) | Free agent | 40% |
| Julian Champagnie | SF/PF | 1 | 29.0 | +4.0 | 1 | **29.0** | 19.7 | 21.8 (4) | 21.4 (9) | 23.9 (16) | Free agent | 42% |
| De'Aaron Fox | PG/SG | 1 | 32.0 | +5.2 | 1 | **17.0** | 24.9 | 12.7 (3) | 24.0 (8) | 30.1 (15) | Matt Wright's Foxies | 94% |

### CLE

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Evan Mobley | Left Toe Sprain | 29 Nov | 33.3 | 39.9 | Matt Wright's Foxies |
| Nae'Qwan Tomlin | Back | 29 Nov | 15.7 | -2.0 | Free agent |

- **Reported timeline:** Mobley: toe sprain, 7–10 days from 16 Nov then re-evaluation (~23–26 Nov) ([ClutchPoints](https://clutchpoints.com/nba/cleveland-cavaliers/cavs-news-evan-mobley-miss-7-10-days-sprained-toe)). Tomlin: back stress reaction, now week-to-week with no updated timetable reported ([CBS Sports, ~17 Nov](https://cbssports.com/fantasy/basketball/news/cavaliers-naeqwan-tomlin-still-out-wednesday)). Tyson (ankle): out 20 Nov, next chance 23 Nov ([CBS Sports, 19 Nov](https://www.cbssports.com/fantasy/basketball/news/cavaliers-jaylon-tyson-out-for-friday/)).

Last 10 games: 4 game(s) without them, 6 with them.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| James Harden | PG/SG | 3 | 35.0 | +3.3 | 3 | **40.3** | 31.8 | 40.3 (3) | 34.8 (8) | 33.1 (15) | Team Nic Kerr | 99% |
| Tyrese Proctor | SG | 4 | 29.0 | +7.5 | 3 | **39.5** | 18.5 | 39.5 (4) | 27.7 (9) | 22.6 (15) | Free agent | 12% |
| Jarrett Allen | C | 3 | 30.7 | +9.2 | 3 | **36.3** | 26.5 | 36.3 (3) | 30.7 (6) → 36.8 (5) | 35.1 (13) → 38.0 (12) | Dr White Slong | 89% |
| Jaylon Tyson (out, ESPN est. back 23 Nov) | SG/SF | 2 | 32.0 | +9.0 | 2 | **28.0** | 5.0 | 28.0 (2) | 20.3 (3) | 19.2 (8) | Free agent | 2% |
| Norchad Omier | PF | 3 | 18.7 | +11.2 | 0 | **27.3** | 5.5 | 27.3 (3) | 18.6 (5) | 18.6 (5) | Free agent | 0% |

### LAC

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Bradley Beal | Right Knee Inflammation | 29 Nov | 25.3 | 10.5 | Free agent |
| Jordan Miller | Left Shoulder Surgery | 02 Mar | 22.0 | 20.4 | Free agent |

- **Reported timeline:** Beal: not close and no date; ESPN's 29 Nov looks early ([BasketNews, 13 Nov](https://basketnews.com/news-259398-worrisome-injury-update-for-bradley-beal-not-close-to-return-to-the-court.html)). Jordan Miller: rotator-cuff surgery 26 Aug, re-evaluation in about six months ([NBC Sports, 26 Aug](https://www.nbcsports.com/fantasy/basketball/player-news/2026-08-26/jordan-miller-undergoes-shoulder-surgery)). Ingram: no debut date reported ([NBC Sports, 18 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/brandon-ingram-achilles-out-thursday-vs-spurs)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

Also out in those games, so part of the gain is theirs: Brandon Ingram (right achilles surgery; ESPN est. 21 Nov).

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Kris Dunn | PG/SG | 10 | 25.0 | +3.0 | 9 | **23.3** | 20.0 | 17.8 (4) | 19.4 (7) | 26.9 (14) | Free agent | 29% |
| Kobe Sanders | SG | 10 | 22.5 | — | 1 | **16.8** | — | 11.2 (4) | 11.4 (7) | 17.5 (14) | Free agent | 1% |

### ATL

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| CJ McCollum | Left Calf Strain | 19 Dec | 30.2 | 28.9 | Waivers |
| Mouhamed Gueye | Left Foot Fracture | 12 Dec | 15.4 | 15.3 | Free agent |

- **Reported timeline:** McCollum: left calf strain, out at least 4 weeks from 17 Nov ([ESPN, 17 Nov](https://www.espn.com/nba/story/_/id/50513506/hawks-lose-cj-mccollum-least-4-weeks-calf-strain)). Gueye: foot, re-evaluation ~4 weeks; Flemings and Landale day-to-day for 20 Nov ([iHeart, 20 Nov](https://1049foxsports.iheart.com/content/2026-11-20-hornets-vs-hawks-injury-report-nov-20/)). Aaron Wiggins, not Dort, took McCollum's start ([ClutchPoints](https://clutchpoints.com/nba/atlanta-hawks/why-hawks-will-turn-lu-dort-aaron-wiggins-losing-cj-mccollum-injury)).

Last 10 games: 1 game(s) without them, 9 with them.

Also out in those games, so part of the gain is theirs: Jock Landale (right hip inflammation; ESPN est. 22 Nov), Kingston Flemings (back strain; ESPN est. 20 Nov).

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Dyson Daniels | PG/SG | 1 | 37.0 | +5.4 | 1 | **42.0** | 40.3 | 35.7 (3) | 45.6 (7) | 40.8 (15) | Snow Time Lakers | 96% |
| Onyeka Okongwu | C | 1 | 36.0 | +3.9 | 1 | **41.0** | 43.2 | 41.0 (3) | 44.3 (7) | 37.2 (15) | Cream Abdul-Yammar | 86% |
| Luguentz Dort | SG/SF | 1 | 31.0 | +6.4 | 0 | **31.0** | 19.9 | 20.3 (3) | 22.3 (7) | 19.8 (15) | Free agent | 3% |
| Corey Kispert | SG/SF | 1 | 17.0 | +4.4 | 0 | **22.0** | 14.4 | 24.5 (2) | 18.2 (4) | 15.2 (8) | Free agent | 0% |

### WSH

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Jamir Watkins | Left Knee Surgery | 02 Apr | 20.6 | 19.4 | Free agent |
| Justin Champagnie | Right Foot | 25 Feb | 20.0 | 25.0 | Free agent |

- **Reported timeline:** Jamir Watkins and Justin Champagnie: no timetable reported (no current update found).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Kyshawn George | SG/SF | 10 | 34.9 | +5.5 | 10 | **38.3** | 30.2 | 34.0 (4) | 37.2 (9) | 34.8 (16) | Snow Time Lakers | 79% |

### ORL

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Paolo Banchero | Right Ankle Sprain | 29 Nov | 35.2 | 47.0 | Dr White Slong |

- **Reported timeline:** Banchero: high-ankle sprain; 19 Nov, "hopefully within the next couple of weeks" (~3 Dec), and Sweeney gives no timetable ([Basketnews, 19 Nov](https://basketnews.com/news-259854-paolo-banchero-shares-major-update-on-his-recovery-from-ankle-injury.html)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Franz Wagner | SF/PF | 10 | 38.2 | +4.2 | 10 | **55.2** | 38.6 | 66.3 (3) | 61.0 (7) | 48.6 (14) | Cream Abdul-Yammar | 95% |
| Anthony Black | PG/SG | 9 | 34.7 | +5.8 | 9 | **40.7** | 28.2 | 29.7 (3) | 39.4 (7) | 38.3 (11) | **us** | 68% |
| Wendell Carter Jr. | C | 10 | 33.3 | +7.9 | 10 | **31.6** | 23.0 | 26.3 (3) | 34.6 (7) | 32.6 (14) | Dr White Slong | 56% |
| Tristan da Silva | SF/PF | 8 | 31.0 | +9.6 | 2 | **24.9** | 17.2 | 25.3 (3) | 25.8 (5) | 25.8 (12) | Free agent | 10% |
| Jase Richardson | SG | 7 | 25.6 | +14.7 | 5 | **17.1** | 8.6 | — | 16.2 (4) | 15.3 (11) | Free agent | 0% |

### CHA

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Kon Knueppel | Left Hamstring Strain | 12 Dec | 34.2 | -2.0 | Free agent |

- **Reported timeline:** Knueppel: hamstring, at least 4 more weeks as of ~7 Nov ([Heavy](https://heavy.com/sports/nba/charlotte-hornets/hornets-brandon-miller-injury-scare-kon-knueppel/)). Grayson Allen: concussion protocol, out 20 Nov, no timetable reported ([CBS Sports, 19 Nov](https://www.cbssports.com/fantasy/basketball/news/hornets-grayson-allen-out-for-friday/)).

Last 10 games: 9 game(s) without them, 1 with them.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Brandon Miller | SG/SF | 7 | 29.9 | +3.9 | 7 | **31.1** | 2.0 | 24.5 (2) | 15.8 (4) | 29.5 (12) | Matt Wright's Foxies | 86% |
| Dennis Schroder (out, ESPN est. back 25 Nov) | PG | 4 | 30.2 | +10.2 | 3 | **16.5** | 17.0 | — | 17.0 (1) | 19.1 (9) | Free agent | 3% |
| Royce O'Neale | SF/PF | 9 | 24.0 | +6.0 | 0 | **15.2** | 9.0 | 13.0 (3) | 15.5 (6) | 12.9 (14) | Free agent | 1% |
| Christian Anderson | PG | 9 | 14.6 | — | 0 | **12.7** | — | 22.0 (3) | 16.8 (5) | 10.2 (13) | Free agent | 0% |
| Tidjane Salaun | PF | 9 | 13.2 | +3.2 | 0 | **10.0** | 13.0 | 3.3 (3) | 10.3 (6) | 12.0 (13) | Free agent | 0% |

### TOR

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| RJ Barrett | Right Hamstring Strain | 13 Dec | 34.1 | 36.4 | Dr White Slong |

- **Reported timeline:** Barrett: mild hamstring strain, out at least two weeks, re-evaluation ~3 Dec ([Hoops Rumors, Nov](https://www.hoopsrumors.com/2026/11/raptors-rj-barrett-hamstring-out-at-least-two-weeks.html)). Leonard (ours): still "reconditioning", no timetable reported ([Global News, 20 Nov](https://globalnews.ca/news/12158569/barrett-murray-boyles-put-on-raptors-injured-list)). Murray-Boyles: concussion protocol since 19 Nov, no timetable reported ([CP24, 19 Nov](https://www.cp24.com/news/sports/2026/11/19/rj-barrett-and-collin-murray-boyles-added-to-toronto-raptors-injured-list/)). Barnes plays 20 Nov, which sends Battle back to the bench ([NBC Sports, 19 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/scottie-barnes-groin-removed-from-injury-report)).

Last 10 games: 1 game(s) without them, 9 with them.

Also out in those games, so part of the gain is theirs: Kawhi Leonard (left knee inflammation; ESPN est. 27 Nov).

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Ja'Kobe Walter | SG | 1 | 38.0 | +5.3 | 1 | **48.0** | 20.4 | 27.5 (4) | 22.6 (8) | 26.0 (15) | Free agent | 12% |
| Jakob Poeltl | C | 1 | 29.0 | +4.3 | 1 | **37.0** | 30.1 | 24.8 (4) | 31.0 (8) | 25.5 (13) | Free agent | 37% |
| Jamison Battle | SF | 1 | 33.0 | +13.9 | 1 | **34.0** | 15.4 | 15.8 (4) | 15.9 (8) | 15.3 (15) | Free agent | 0% |
| Allen Graves | SF | 1 | 31.0 | +17.7 | 0 | **20.0** | 9.3 | 11.2 (4) | 12.1 (8) | 13.5 (15) | Free agent | 0% |
| Trayce Jackson-Davis | PF | 1 | 17.0 | +9.8 | 0 | **18.0** | 14.5 | 18.0 (1) | 18.3 (3) | 12.7 (10) | Free agent | 0% |

### CHI

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Caleb Wilson | Right Hand | 13 Dec | 32.1 | 34.9 | Free agent |

- **Reported timeline:** Caleb Wilson: hand surgery ~12 Nov, 4–6 weeks (~10–24 Dec) ([Chicago Sun-Times, 12 Nov](https://chicago.suntimes.com/bulls/2026/11/12/bulls-losing-demoralizing-understanding-process)).

Last 10 games: 4 game(s) without them, 6 with them.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Isaac Okoro | SG/SF | 4 | 32.2 | +12.2 | 4 | **30.8** | 10.3 | 30.8 (4) | 22.9 (7) | 16.1 (14) | Free agent | 1% |
| Buddy Hield | SG/SF | 4 | 20.8 | +9.2 | 0 | **24.0** | 13.2 | 24.0 (4) | 22.4 (5) | 16.4 (12) | Free agent | 1% |
| Nic Claxton | C | 3 | 20.3 | +3.3 | 0 | **19.7** | 29.0 | 19.7 (3) | 23.4 (5) | 23.4 (5) | Free agent | 40% |
| Zach Collins | C | 2 | 19.5 | +12.2 | 1 | **14.0** | 6.0 | 14.0 (2) | 11.2 (4) | 7.3 (9) | Free agent | 0% |

### PHX

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Mark Williams | Left Shoulder Surgery | 03 Feb | 24.9 | 31.9 | Free agent |

- **Reported timeline:** Mark Williams: labrum surgery 10 Sep, at least 5 months ([BVM Sports, 11 Sep](https://bvmsports.com/2026/09/11/suns-mark-williams-likely-to-miss-five-months-after-shoulder-surgery/)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Jordan Goodwin | PG/SG | 6 | 19.3 | — | 0 | **25.2** | — | 25.0 (4) | 27.6 (5) | 26.0 (10) | Free agent | 3% |

### DET

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Taurean Prince | Right Knee Surgery | 13 Dec | 23.6 | 5.3 | Free agent |

- **Reported timeline:** Duren (ours): "re-evaluated next week", no return date ([Heavy, 20 Nov](https://heavy.com/sports/nba/detroit-pistons/injury-report-vs-raptors-november-20/)). Prince: knee surgery reported, no timetable reported ([NBC Sports, 19 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/taurean-prince-knee-remains-out-friday-vs-tor)). Robinson: quad, out at least a week from 17 Nov, re-evaluation ~24 Nov ([NBC Sports, 17 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-17/duncan-robinson-quad-out-at-least-a-week)).

Last 10 games: 8 game(s) without them, 2 with them.

Also out in those games, so part of the gain is theirs: Jalen Duren (right hamstring strain; ESPN est. 24 Nov).

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Ausar Thompson | SF/PF | 8 | 30.5 | +7.0 | 8 | **42.2** | 38.0 | 56.8 (4) | 44.4 (7) | 37.9 (13) | Lauri Birds | 82% |
| Duncan Robinson (out, ESPN est. back 27 Nov) | SG/SF | 6 | 32.8 | +8.3 | 6 | **33.8** | 23.0 | 16.0 (2) | 24.8 (5) | 29.8 (12) | Free agent | 42% |
| John Collins | PF/C | 8 | 26.1 | +4.1 | 8 | **26.2** | 5.5 | 20.5 (4) | 27.4 (7) | 24.6 (14) | Free agent | 56% |
| Javonte Green | SF | 8 | 19.8 | +3.2 | 1 | **17.5** | 11.0 | 18.2 (4) | 16.0 (7) | 15.6 (14) | Free agent | 0% |

### MEM

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| GG Jackson | Left Foot Surgery | 18 Jan | 23.0 | 12.4 | Free agent |

- **Reported timeline:** GG Jackson: no current timetable reported. Pippen: lumbar disc herniation, week-to-week ([Yahoo, 16 Nov](https://sports.yahoo.com/articles/grizzlies-gg-jackson-ii-needs-172020038.html)). Grant: left calf, left 19 Nov, no timetable reported ([NBC Sports, 19 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jerami-grant-calf-wont-return-thursday-vs-gsw)).

Last 10 games: 4 game(s) without them, 6 with them.

Also out in those games, so part of the gain is theirs: Scotty Pippen Jr. (back soreness; ESPN est. 25 Nov).

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Cam Spencer | PG/SG | 4 | 26.8 | +3.8 | 3 | **33.2** | 29.8 | 37.6 (5) | 31.9 (9) | 29.9 (16) | Lauri Birds | 36% |
| Javon Small | PG | 4 | 24.0 | +3.0 | 0 | **24.2** | 25.0 | 29.2 (5) | 24.6 (8) | 23.4 (9) | Free agent | 4% |
| Olivier-Maxence Prosper | PF | 4 | 16.8 | +9.2 | 0 | **13.2** | 10.0 | 16.0 (5) | 11.6 (8) | 10.4 (10) | Free agent | 0% |

### SAC

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Ben Simmons | Right Achilles Surgery | 01 Oct | 21.2 | — | Free agent |

- **Reported timeline:** Simmons: no timetable reported. Raynaud: patellar subluxation, week-to-week, "still not close" ([RotoWire, 18 Nov](https://www.rotowire.com/basketball/headlines/maxime-raynaud-injury-still-out-wednesday-539684)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

Also out in those games, so part of the gain is theirs: Maxime Raynaud (right knee dislocated; ESPN est. 25 Nov).

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Darius Acuff Jr. | PG | 10 | 37.2 | +6.6 | 10 | **45.8** | 30.4 | 35.7 (3) | 43.4 (7) | 40.1 (14) | Team Nic Kerr | 91% |
| Leaky Black | SF | 8 | 22.9 | — | 1 | **23.2** | — | 21.3 (3) | 21.0 (7) | 19.8 (10) | Free agent | 0% |
| De'Andre Hunter (day to day, ESPN est. back 20 Nov) | SF/PF | 8 | 35.6 | +8.0 | 8 | **21.4** | 23.9 | 27.5 (2) | 22.0 (5) | 20.8 (12) | Free agent | 6% |
| Dylan Cardwell | C | 7 | 17.0 | — | 2 | **19.7** | — | 17.0 (3) | 19.7 (7) | 19.7 (7) | Free agent | 0% |
| Emanuel Sharp | SG | 10 | 17.6 | — | 0 | **12.2** | — | 14.7 (3) | 12.4 (7) | 11.1 (14) | Free agent | 0% |

### MIL

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Ousmane Dieng | Left Finger Surgery | 14 Dec | 19.4 | 7.7 | Free agent |

- **Reported timeline:** Dieng: finger surgery 16 Nov, no timetable reported ([NBC Sports, 15 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-15/ousmane-dieng-finger-to-undergo-surgery-monday)). Burries has started in his place ([Yahoo](https://sports.yahoo.com/articles/bucks-vs-hawks-injury-report-164515198.html)).

Last 10 games: 5 game(s) without them, 5 with them.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Brayden Burries | SG | 5 | 29.2 | +5.4 | 5 | **32.8** | 19.4 | 26.5 (4) | 27.2 (9) | 22.8 (16) | Free agent | 11% |
| Kasparas Jakucionis | PG | 5 | 21.2 | +9.7 | 0 | **31.6** | 9.0 | 44.7 (3) | 22.4 (8) | 20.4 (15) | Free agent | 10% |
| Pete Nance | PF | 1 | 28.0 | +24.0 | 1 | **22.0** | 5.0 | 22.0 (1) | 13.5 (2) → 22.0 (1) | 13.5 (2) → 22.0 (1) | Free agent | 0% |
| Kel'el Ware | C | 5 | 19.6 | +3.2 | 1 | **20.2** | 17.8 | 26.8 (4) | 19.3 (9) | 22.9 (16) | Free agent | 53% |
| AJ Green | SG | 4 | 17.0 | +4.6 | 0 | **14.2** | 6.8 | 5.7 (3) | 8.0 (8) | 11.0 (15) | Free agent | 1% |

### DEN

| Out | Injury | ESPN est. | Min left | Season FP/g | League |
|---|---|---|---:|---:|---|
| Julian Strawther | Left Knee Sprain | 29 Nov | 16.0 | 12.9 | Free agent |

- **Reported timeline:** Strawther: knee sprain 14 Oct, re-evaluation in six weeks (~25 Nov) ([Denver Gazette, 16 Oct](https://www.denvergazette.com/2026/10/16/nuggets-provide-update-on-julian-strawthers-knee-injury-5/)).

Last 10 games: 10 game(s) this season, all without them; compared with ESPN's projection.

| Replacement | Pos | Games | Min without | Δ min | Starts | FP/g without | Baseline FP/g | L7 | L15 | L30 | League | Owned |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|
| Christian Braun | SG/SF | 10 | 33.2 | +5.7 | 10 | **32.5** | 23.1 | 35.7 (3) | 28.4 (7) | 30.9 (13) | Team Nic Kerr | 45% |
| Trevon Brazile | SF/PF | 10 | 18.3 | — | 1 | **15.7** | — | 9.0 (3) | 12.4 (7) | 16.8 (13) | Free agent | 2% |
| Spencer Jones | SF/PF | 6 | 17.8 | — | 0 | **10.8** | — | 8.3 (3) | 10.8 (6) | 10.8 (6) | Free agent | 0% |

## Every injury

All 108 players in ESPN's injury feed, longest expected absence first.

| Player | NBA | Status | Injury | ESPN est. | Days | League |
|---|---|---|---|---|---:|---|
| Ben Simmons | SAC | Out | Right Achilles Surgery | 01 Oct | 315 | Free agent |
| Ariel Hukporti | PHI | Out | Right Achilles Surgery | 01 Oct | 315 | Free agent |
| Henri Veesaar | ATL | Out | Right Knee | 01 Jul | 223 | Free agent |
| Jamir Watkins | WSH | Out | Left Knee Surgery | 02 Apr | 133 | Free agent |
| Donte DiVincenzo | MIN | Out | Right Achilles Surgery | 02 Apr | 133 | Free agent |
| Asa Newell | ATL | Out | Left Toe | 17 Mar | 117 | Free agent |
| Shaedon Sharpe | POR | Out | Right Knee Surgery | 02 Mar | 102 | Free agent |
| Jordan Miller | LAC | Out | Left Shoulder Surgery | 02 Mar | 102 | Free agent |
| Jalen Williams | OKC | Out | Left Leg Fracture | 02 Mar | 102 | Free agent |
| Cason Wallace | OKC | Out | Left Shoulder Surgery | 02 Mar | 102 | Free agent |
| Justin Champagnie | WSH | Out | Right Foot | 25 Feb | 97 | Free agent |
| Mark Williams | PHX | Out | Left Shoulder Surgery | 03 Feb | 75 | Free agent |
| Thomas Sorber | OKC | Out | Knee | 31 Jan | 72 | Free agent |
| GG Jackson | MEM | Out | Left Foot Surgery | 18 Jan | 59 | Free agent |
| Vit Krejci | POR | Out | Left Ankle | 12 Jan | 53 | Free agent |
| Lauri Markkanen | UTAH | Out | Right Hand Fracture | 04 Jan | 45 | Free agent |
| Kristaps Porzingis | GS | Out | Illness | 02 Jan | 43 | Free agent |
| Johnny Furphy | IND | Out | Right Knee Surgery | 02 Jan | 43 | Free agent |
| Jimmy Butler III | GS | Out | Right Knee Surgery | 02 Jan | 43 | Free agent |
| Chet Holmgren | OKC | Out | Right Knee | 02 Jan | 43 | Free agent |
| Ben Sheppard | IND | Out | Left Knee | 02 Jan | 43 | Free agent |
| Anthony Edwards | MIN | Out | Right Knee Surgery | 21 Dec | 31 | Melbourne poopoo |
| CJ McCollum | ATL | Out | Left Calf Strain | 19 Dec | 29 | Waivers |
| Ousmane Dieng | MIL | Out | Left Finger Surgery | 14 Dec | 24 | Free agent |
| Jaren Jackson Jr. | UTAH | Out | Right Knee | 14 Dec | 24 | Free agent |
| Taurean Prince | DET | Out | Right Knee Surgery | 13 Dec | 23 | Free agent |
| RJ Barrett | TOR | Out | Right Hamstring Strain | 13 Dec | 23 | Dr White Slong |
| Dylan Harper | SA | Out | Hip Soreness | 13 Dec | 23 | Melbourne poopoo |
| Caleb Wilson | CHI | Out | Right Hand | 13 Dec | 23 | Free agent |
| Stephen Curry | GS | Out | Right Abdomen | 12 Dec | 22 | Lauri Birds |
| Mouhamed Gueye | ATL | Out | Left Foot Fracture | 12 Dec | 22 | Free agent |
| Kon Knueppel | CHA | Out | Left Hamstring Strain | 12 Dec | 22 | Free agent |
| Tobias Harris | SA | Out | Left Calf Strain | 03 Dec | 13 | Free agent |
| Reece Beekman | WSH | Out | Shoulder | 03 Dec | 13 | Free agent |
| Jayden Quaintance | SA | Out | Right Knee Surgery | 03 Dec | 13 | Free agent |
| Richie Saunders | MEM | Out | Right Knee Surgery | 01 Dec | 11 | Free agent |
| Moses Moody | GS | Out | Left Knee Surgery | 01 Dec | 11 | Free agent |
| Ja Morant | POR | Out | Left Hamstring | 01 Dec | 11 | Free agent |
| Paolo Banchero | ORL | Out | Right Ankle Sprain | 29 Nov | 9 | Dr White Slong |
| Nae'Qwan Tomlin | CLE | Out | Back | 29 Nov | 9 | Free agent |
| Julian Strawther | DEN | Out | Left Knee Sprain | 29 Nov | 9 | Free agent |
| Jaylen Clark | MIN | Out | Right Hamstring | 29 Nov | 9 | Free agent |
| Izaiyah Nelson | ORL | Out | Left Ankle Surgery | 29 Nov | 9 | Free agent |
| Evan Mobley | CLE | Out | Left Toe Sprain | 29 Nov | 9 | Matt Wright's Foxies |
| Bradley Beal | LAC | Out | Right Knee Inflammation | 29 Nov | 9 | Free agent |
| Tyrese Haliburton | IND | Out | Left Hamstring Strain | 28 Nov | 8 | Lauri Birds |
| Trendon Watford | NO | Out | Right Ankle Sprain | 27 Nov | 7 | Free agent |
| Tarik Biberovic | DAL | Out | Right Heel Inflammation | 27 Nov | 7 | Free agent |
| Sergio de Larrea | DAL | Out | Right Knee Strain | 27 Nov | 7 | Free agent |
| Kawhi Leonard | TOR | Out | Left Knee Inflammation | 27 Nov | 7 | **us** |
| Jusuf Nurkic | UTAH | Out | Right Foot Strain | 27 Nov | 7 | Free agent |
| Duncan Robinson | DET | Out | Left Quadriceps Strain | 27 Nov | 7 | Free agent |
| Dereck Lively II | DAL | Out | Right Foot Surgery | 27 Nov | 7 | Free agent |
| Dejounte Murray | NO | Out | Ankle | 27 Nov | 7 | Free agent |
| Bryce McGowens | NO | Out | Left Elbow Infection | 27 Nov | 7 | Free agent |
| Bennedict Mathurin | NO | Out | Left Foot Plantar Fasciitis | 27 Nov | 7 | Free agent |
| Tobe Awaka | CHI | Out | Back | 25 Nov | 5 | Free agent |
| Scotty Pippen Jr. | MEM | Out | Back Soreness | 25 Nov | 5 | Free agent |
| Maxime Raynaud | SAC | Out | Right Knee Dislocated | 25 Nov | 5 | Free agent |
| Dennis Schroder | CHA | Out | Left Hamstring Strain | 25 Nov | 5 | Free agent |
| Tristan Vukcevic | WSH | Out | Left Hip Pinched Nerve | 24 Nov | 4 | Free agent |
| Jalen Duren | DET | Out | Right Hamstring Strain | 24 Nov | 4 | **us** |
| Nate Bittle | TOR | Out | Right Foot Fracture | 23 Nov | 3 | — |
| Jaylon Tyson | CLE | Out | Right Ankle | 23 Nov | 3 | Free agent |
| Jaylen Brown | PHI | Out | Left Hamstring | 23 Nov | 3 | Snow Time Lakers |
| Grayson Allen | CHA | Out | Concussion | 23 Nov | 3 | Free agent |
| Grant Williams | CHA | Out | Right Hamstring | 23 Nov | 3 | Free agent |
| Grant Nelson | BKN | Out | Right Ankle Sprain | 23 Nov | 3 | — |
| Collin Murray-Boyles | TOR | Out | Concussion | 23 Nov | 3 | Free agent |
| Clint Capela | HOU | Out | Right Ankle Sprain | 23 Nov | 3 | Free agent |
| Austin Reaves | LAL | Out | Left Heel Bruise | 23 Nov | 3 | Cream Abdul-Yammar |
| Ronald Holland II | DET | Out | Left Knee Bruise | 22 Nov | 2 | Free agent |
| Noah Penda | ORL | Out | Right Hamstring Strain | 22 Nov | 2 | Free agent |
| Myron Gardner | MIA | Day-To-Day | Hamstring | 22 Nov | 2 | Free agent |
| Jonathan Isaac | ORL | Out | Left Knee | 22 Nov | 2 | Free agent |
| Jock Landale | ATL | Out | Right Hip Inflammation | 22 Nov | 2 | Free agent |
| Ebuka Okorie | DET | Out | Left Oblique Strain | 22 Nov | 2 | Free agent |
| Draymond Green | GS | Day-To-Day | Rest | 22 Nov | 2 | Free agent |
| Brandon Williams | GS | Out | Left Hamstring Strain | 22 Nov | 2 | Free agent |
| Zach Edey | MEM | Day-To-Day | Ankle | 21 Nov | 1 | Free agent |
| Ugonna Onyenso | DET | Day-To-Day | Left Foot | 21 Nov | 1 | Free agent |
| Tyrese Maxey | PHI | Day-To-Day | Right Foot Soreness | 21 Nov | 1 | Team Nic Kerr |
| Ty Jerome | MEM | Out | Right Hip | 21 Nov | 1 | Melbourne poopoo |
| Tobi Lawal | DAL | Day-To-Day | Right Groin | 21 Nov | 1 | Free agent |
| Robert Williams III | POR | Day-To-Day | Rest | 21 Nov | 1 | Free agent |
| Myles Turner | MIL | Day-To-Day | Left Shoulder Bruise | 21 Nov | 1 | Free agent |
| Kyle Kuzma | MIL | Day-To-Day | Right Shoulder Bruise | 21 Nov | 1 | Team Nic Kerr |
| Jerami Grant | MEM | Day-To-Day | Left Calf | 21 Nov | 1 | Free agent |
| Dominick Barlow | PHI | Out | Back Fracture | 21 Nov | 1 | Free agent |
| Deni Avdija | POR | Day-To-Day | Foot | 21 Nov | 1 | Snow Time Lakers |
| Dean Wade | PHI | Day-To-Day | Left Hamstring Soreness | 21 Nov | 1 | Free agent |
| Chris Youngblood | POR | Out | Right Heel Bruise | 21 Nov | 1 | Free agent |
| Brandon Ingram | LAC | Out | Right Achilles Surgery | 21 Nov | 1 | Melbourne poopoo |
| Adem Bona | PHI | Out | Back Sprain | 21 Nov | 1 | Free agent |
| Trey Murphy III | NO | Out | Knee Tendinitis | 20 Nov | 0 | Free agent |
| T.J. McConnell | IND | Day-To-Day | Right Hamstring Strain | 20 Nov | 0 | Free agent |
| Steven Adams | HOU | Day-To-Day | Right Quadriceps Bruise | 20 Nov | 0 | Free agent |
| Precious Achiuwa | SAC | Day-To-Day | Left Lower Leg Bruise | 20 Nov | 0 | Free agent |
| Peyton Watson | CLE | Day-To-Day | Back Bruise | 20 Nov | 0 | Free agent |
| Noa Essengue | CHI | Day-To-Day | Wrist Soreness | 20 Nov | 0 | Free agent |
| Kingston Flemings | ATL | Day-To-Day | Back Strain | 20 Nov | 0 | Free agent |
| Felix Okpara | WSH | Day-To-Day | Back Strain | 20 Nov | 0 | Free agent |
| De'Andre Hunter | SAC | Day-To-Day | Left Hip Soreness | 20 Nov | 0 | Free agent |
| Cade Cunningham | DET | Day-To-Day | Right Knee Soreness | 20 Nov | 0 | **us** |
| Braden Smith | IND | Day-To-Day | Right Ankle Sprain | 20 Nov | 0 | Free agent |
| Andrew Nembhard | IND | Day-To-Day | Left Hip Soreness | 20 Nov | 0 | Matt Wright's Foxies |
| Alperen Sengun | HOU | Day-To-Day | Eye | 20 Nov | 0 | Cream Abdul-Yammar |
| Alex Caruso | OKC | Day-To-Day | Right Hip Soreness | 20 Nov | 0 | Free agent |

## Sources

- ESPN NBA injury feed and box scores (`site.api.espn.com`); ESPN fantasy API, league 423671879 (`kona_player_info`, `mTeam`, `mRoster`, `proTeamSchedules_wl`), read 2026-11-20 06:56 UTC.
- <https://1049foxsports.iheart.com/content/2026-11-20-hornets-vs-hawks-injury-report-nov-20/>
- <https://athlonsports.com/nba/portland-trail-blazers/final-injury-report-for-trail-blazers-bucks-will-deni-avdija-toumani-camara-play>
- <https://basketnews.com/news-259398-worrisome-injury-update-for-bradley-beal-not-close-to-return-to-the-court.html>
- <https://basketnews.com/news-259854-paolo-banchero-shares-major-update-on-his-recovery-from-ankle-injury.html>
- <https://bleacherreport.com/articles/25532370-tyrese-haliburton-injury-return-timeline-updated-pacers-rick-carlisle-amid-hamstring-issue>
- <https://bvmsports.com/2026/09/11/suns-mark-williams-likely-to-miss-five-months-after-shoulder-surgery/>
- <https://cbssports.com/fantasy/basketball/news/cavaliers-naeqwan-tomlin-still-out-wednesday>
- <https://chicago.suntimes.com/bulls/2026/11/12/bulls-losing-demoralizing-understanding-process>
- <https://clutchpoints.com/nba/atlanta-hawks/why-hawks-will-turn-lu-dort-aaron-wiggins-losing-cj-mccollum-injury>
- <https://clutchpoints.com/nba/cleveland-cavaliers/cavs-news-evan-mobley-miss-7-10-days-sprained-toe>
- <https://clutchpoints.com/nba/los-angeles-clippers/clippers-brandon-ingram-injury-update-teases-return-coming-very-soon>
- <https://espn.com/nba/story/_/id/50503111/steph-curry-warriors-race-injuries>
- <https://globalnews.ca/news/12158569/barrett-murray-boyles-put-on-raptors-injured-list>
- <https://heavy.com/sports/nba/charlotte-hornets/hornets-brandon-miller-injury-scare-kon-knueppel/>
- <https://heavy.com/sports/nba/detroit-pistons/injury-report-vs-raptors-november-20/>
- <https://si.com/nba/jazz/onsi/jazz-vs-lakers-injury-report-delivers-big-jaxson-hayes-update>
- <https://sports.yahoo.com/articles/blazers-vs-bucks-3-things-225403965.html>
- <https://sports.yahoo.com/articles/bucks-vs-hawks-injury-report-164515198.html>
- <https://sports.yahoo.com/articles/cason-wallace-shoulder-surgery-evaluated-011900324.html>
- <https://sports.yahoo.com/articles/grizzlies-gg-jackson-ii-needs-172020038.html>
- <https://sports.yahoo.com/articles/rudy-gobert-1-point-night-071557236.html>
- <https://sports.yahoo.com/articles/tobias-harris-potential-return-timeline-180822753.html>
- <https://sports.yahoo.com/articles/warriors-vs-grizzlies-injury-report-234754065.html>
- <https://sports.yahoo.com/nba/breaking-news/article/thunders-jalen-williams-has-surgery-on-ankle-fractured-fibula-will-be-reevaluated-before-end-of-season-011001403.html>
- <https://www.cbssports.com/fantasy/basketball/news/cavaliers-jaylon-tyson-out-for-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/cavaliers-peyton-watson-iffy-for-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/hornets-grayson-allen-out-for-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/jazzs-brice-sensabaugh-dazzles-with-4011-double-double/>
- <https://www.cbssports.com/fantasy/basketball/news/jazzs-jusuf-nurkic-not-ready-to-return-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/kings-deandre-hunter-questionable-versus-lakers/>
- <https://www.cbssports.com/fantasy/basketball/news/mavericks-dereck-lively-still-sidelined/>
- <https://www.cbssports.com/fantasy/basketball/news/pistons-cade-cunningham-expected-to-play-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/warriors-draymond-green-confirmed-out-thursday/>
- <https://www.cbssports.com/fantasy/basketball/news/warriors-jimmy-butler-still-months-away-from-returning/>
- <https://www.cp24.com/news/sports/2026/11/19/rj-barrett-and-collin-murray-boyles-added-to-toronto-raptors-injured-list/>
- <https://www.denvergazette.com/2026/10/16/nuggets-provide-update-on-julian-strawthers-knee-injury-5/>
- <https://www.detroitnews.com/story/sports/nba/pistons/2026/11/08/pistons-all-star-jalen-duren-out-another-two-weeks-with-hamstring-strain/92677147007/>
- <https://www.espn.com/nba/story/_/id/50473732/sources-dejounte-murray-wants-trade-pelicans>
- <https://www.espn.com/nba/story/_/id/50513506/hawks-lose-cj-mccollum-least-4-weeks-calf-strain>
- <https://www.espn.com/nba/story/_/id/50533303/sources-spurs-dylan-harper-1-3-weeks-hip-strain>
- <https://www.fantasypros.com/nba/news/621206/ryan-rollins-illness-off-injury-report-thursday.php>
- <https://www.foxsports.com/nba/devin-vassell-player>
- <https://www.hoopsrumors.com/2026/11/raptors-rj-barrett-hamstring-out-at-least-two-weeks.html>
- <https://www.nba.com/blazers/news/ja-morant-injury-update>
- <https://www.nba.com/news/chet-holmgren-out-8-10-weeks-with-patellar-tendon-tear>
- <https://www.nba.com/pacers/news/preview-pacers-rockets-261118>
- <https://www.nba.com/warriors/news/brandon-williams-injury-update-11-18-26>
- <https://www.nba.com/warriors/news/stephen-curry-injury-update-11-12-26>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-08-26/jordan-miller-undergoes-shoulder-surgery>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-09-04/gm-divincenzo-achilles-lacks-return-timeline>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-15/ousmane-dieng-finger-to-undergo-surgery-monday>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-16/chi-starts-giddey-powell-okoro-buzelis-smith>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-17/duncan-robinson-quad-out-at-least-a-week>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/brandon-ingram-achilles-out-thursday-vs-spurs>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/cavs-start-harden-mitchell-proctor-mario-allen>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/raptors-start-iq-walter-battle-collin-poeltl>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jaxson-hayes-knee-plays-25-minutes-in-return>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jerami-grant-calf-wont-return-thursday-vs-gsw>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/scottie-barnes-groin-removed-from-injury-report>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/taurean-prince-knee-remains-out-friday-vs-tor>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/trey-murphy-knee-questionable-friday-vs-thunder>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/zach-edey-ankle-ruled-out-thursday-vs-warriors>
- <https://www.rotowire.com/basketball/headlines/jakob-poeltl-news-back-in-starting-lineup-539839>
- <https://www.rotowire.com/basketball/headlines/jakobe-walter-news-fills-stat-sheet-in-defeat-539911>
- <https://www.rotowire.com/basketball/headlines/maxime-raynaud-injury-still-out-wednesday-539684>
- <https://www.rotowire.com/basketball/headlines/trey-murphy-injury-wont-play-friday-538912>
- <https://www.sltrib.com/sports/jazz/2026/11/11/lauri-markkanen-injury-jazz/>
