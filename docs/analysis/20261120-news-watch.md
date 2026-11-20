# News watch: 20 Nov 2026

- Generated 2026-11-20 06:55 UTC by `council/news_watch.py`. This is **data, not a verdict**: each flag is a question for the research step.
- **Scope:** 14 on our roster, 53 free agents and waiver players (the top 40 by rate, and injured ones worth 25+ FP/g last season or on projection), and 97 on other teams' rosters (injury flags only, except this week's and next week's opponents: Snow Time Lakers, Matt Wright's Foxies). News is ESPN's fantasy feed (RotoWire's notes); role, minutes and rest read the last 4 days.
- **Flags:** 40 players. *injury*: ESPN's label or date disagrees with the news; *role*: into or out of the starting lineup; *minutes*: last 3 games 5+ min off the season, or a minutes limit; *rest*: a back-to-back in the next 7 days with a rest signal; *gap*: out with no date, or no news in 5 days.
- **Rate** is the weighted, outlier-adjusted rate (`council/gamelog.py`). **Role rate** is FP per minute this season (outliers out) times his minutes in the new role. The plans use it only once the research confirms the role and records it in `council/news_overrides.csv`.

## What changed for us

**Our players**
- **Cade Cunningham** (DET, day-to-day, right knee soreness; ESPN est. 20 Nov): sat the second night of the 17–18 Nov back-to-back and is expected to play Fri 20 Nov vs TOR ([CBS Sports, 19 Nov](https://www.cbssports.com/fantasy/basketball/news/pistons-cade-cunningham-expected-to-play-friday/)). Rate 57.2; L7 66.7 (3), L15 54.5 (6), L30 50.7 (13); projected 50.4.
- **Scottie Barnes** (TOR): his 18 Nov absence was one night of groin injury management. He is off the report for Fri 20 Nov ([NBC Sports, 19 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/scottie-barnes-groin-removed-from-injury-report)). L7 49.0 (2, small sample).
- **Jalen Duren** (DET, IR, right hamstring strain; ESPN est. 24 Nov): the Pistons set a two-week re-evaluation on 8 Nov ([Detroit News, 8 Nov](https://www.detroitnews.com/story/sports/nba/pistons/2026/11/08/pistons-all-star-jalen-duren-out-another-two-weeks-with-hamstring-strain/92677147007/)), and the 20 Nov report says he will be "re-evaluated next week" ([Heavy, 20 Nov](https://heavy.com/sports/nba/detroit-pistons/injury-report-vs-raptors-november-20/)). No return date has been reported; ESPN's 24 Nov is the earliest plausible date.
- **Kawhi Leonard** (TOR, left knee inflammation; ESPN est. 27 Nov): still "reconditioning", with no return date ([Global News, 20 Nov](https://globalnews.ca/news/12158569/barrett-murray-boyles-put-on-raptors-injured-list)). No timetable reported.
- **Saddiq Bey** (NO): he starts only while Trey Murphy III sits. Murphy is questionable for Fri 20 Nov, and NBC says Bey "will likely head back to the bench with Murphy available" ([NBC Sports, 19 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/trey-murphy-knee-questionable-friday-vs-thunder)). No role row was added. Rate 34.8, role rate 36.0; L7 41.0 (4), L15 33.0 (9), L30 30.4 (16): L7 is 10.6 over his season average on 35+ starter's minutes.
- **Daniss Jenkins** (DET): starting while Duncan Robinson (left quad; out at least a week from 17 Nov, ESPN est. 27 Nov) is out. Expect 33–35 minutes. No row.
- **Paul George** (BOS): Boston rests him on the second night of road back-to-backs ([HoopsHype, 2 Nov](https://www.hoopshype.com/story/sports/nba/rumors/2026/11/02/paul-george-rest-out/92568567007/)). Sun 22 Nov at GS follows Sat at SAC, so that night is a real sit risk, though nothing has been announced.
- **Jalen Smith** (CHI): the rest flag was a false positive. His 14 Nov absence was a hand-sprain precaution.

**Targets whose value moved**
- **Trey Murphy III** (NO, free agent, patellar tendinopathy in both knees; ESPN est. 20 Nov) is questionable for Fri 20 Nov after missing six games ([NBC Sports, 19 Nov](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/trey-murphy-knee-questionable-friday-vs-thunder)).
- **Dejounte Murray** (NO, ankle; ESPN est. 27 Nov) is out indefinitely until he is traded ([ESPN, 13 Nov](https://www.espn.com/nba/story/_/id/50473732/sources-dejounte-murray-wants-trade-pelicans)). ESPN's date is a placeholder.
- **Mo Bamba**'s 30-minute role ended when Jaxson Hayes returned. Ignore his 44.6 role rate.
- **Quentin Grimes** and **Tyrese Proctor** start only until Austin Reaves and Jaylon Tyson return.
- **Ja Morant** (POR, Grade 2 hamstring) is re-evaluated about 27 Nov, so ESPN's 01 Dec moves to 28 Nov as a floor.

**Overrides**
- Added:
  - Ja Morant: return 28 Nov.
  - Tyrese Proctor: role 27 min until 22 Nov.
  - Quentin Grimes: role 35 min until 22 Nov.
- Replaced: Jusuf Nurkic's return moves from 21 Nov to 27 Nov (week-to-week, out 20 Nov).
- Removed:
  - the four expired rows: Yves Missi, Fred VanVleet, Maxime Raynaud and Nic Claxton;
  - CJ McCollum's bench role, because he is now out at least four weeks with a calf strain ([ESPN, 17 Nov](https://www.espn.com/nba/story/_/id/50513506/hawks-lose-cj-mccollum-least-4-weeks-calf-strain)).
- None of the overrides touches our roster or Snow Time Lakers' roster. They change only the streamer projections (Grimes and Proctor this week; Morant and Nurkic next week).

## Overrides (`council/news_overrides.csv`)

| Player | Kind | Value | Until | Source | State |
|---|---|---|---|---|---|
| CJ McCollum | role | 23 | 2026-11-22 | [link](https://www.rotowire.com/basketball/headlines/cj-mccollum-news-leads-hawks-bench-with-21-points-538466) | in force |
| Jusuf Nurkic | return | 2026-11-21 | — | [link](https://www.nba.com/jazz/news/jusuf-nurkic-injury-update-2) | in force |
| Yves Missi | return | 2026-11-18 | — | [link](https://www.nba.com/pelicans/news/pelicans-shootaround-update-nets-tip-off-important-five-game-new-orleans-homestand) | expired: remove it |
| Fred VanVleet | sit | 2026-11-16 | — | [link](https://www.cbssports.com/fantasy/basketball/news/rockets-fred-vanvleet-to-miss-back-to-backs/) | expired: remove it |
| Maxime Raynaud | return | 2026-11-16 | — | [link](https://www.cbssports.com/fantasy/basketball/news/kings-maxime-raynaud-still-out-for-tuesday/) | expired: remove it |
| Nic Claxton | role | 18 | 2026-11-16 | [link](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-11/nic-claxton-scores-17-points-in-16-minutes) | expired: remove it |

## Summary

| Player | NBA | League | Flags | Rate | Role rate | ESPN status |
|---|---|---|---|---:|---:|---|
| **Scottie Barnes** | TOR | us | injury | 48.0 | — | active |
| **Jalen Duren** | DET | us | injury, gap | 44.1 † | — | out, ESPN est. 24 Nov |
| **Saddiq Bey** | NO | us | role, minutes | 34.8 | 36.0 | active |
| **Cade Cunningham** | DET | us | minutes | 57.2 | 58.9 | day-to-day, ESPN est. 20 Nov |
| **Daniss Jenkins** | DET | us | minutes | 33.8 | 37.8 | active |
| **Jalen Smith** | CHI | us | rest | 42.2 | — | active |
| **Paul George** | BOS | us | rest | 36.3 | — | active |
| **Jusuf Nurkic** | UTAH | free agent | injury | 36.7 | — | out, ESPN est. 27 Nov |
| **Maxime Raynaud** | SAC | free agent | injury | 28.1 | — | out, ESPN est. 25 Nov |
| **Dejounte Murray** | NO | free agent | injury, minutes, gap | 27.2 | 24.0 | out, ESPN est. 27 Nov |
| **Robert Williams III** | POR | free agent | injury | 23.2 | — | day-to-day, ESPN est. 21 Nov |
| **Scotty Pippen Jr.** | MEM | free agent | injury | 16.3 | — | out, ESPN est. 25 Nov |
| **Bennedict Mathurin** | NO | free agent | injury | 4.8 | — | out, ESPN est. 27 Nov |
| **Quentin Grimes** | LAL | free agent | role, minutes | 35.2 | 30.8 | active |
| **Mo Bamba** | UTAH | waivers | role, minutes | 34.3 | 44.6 | active |
| **Aday Mara** | OKC | free agent | role | 31.4 | — | active |
| **Tyrese Proctor** | CLE | free agent | role, minutes | 28.8 | 30.8 | active |
| **Grayson Allen** | CHA | free agent | role | 28.6 | 29.7 | out, ESPN est. 23 Nov |
| **Jakob Poeltl** | TOR | free agent | role | 27.1 | — | active |
| **Jaylon Tyson** | CLE | free agent | role, minutes | 23.1 | 25.8 | out, ESPN est. 23 Nov |
| **Kasparas Jakucionis** | MIL | free agent | minutes | 28.7 | 26.3 | active |
| **Caleb Wilson** | CHI | free agent | minutes | 28.0 | 26.1 | out, ESPN est. 13 Dec |
| **P.J. Washington** | DAL | free agent | minutes | 27.6 | 23.3 | active |
| **T.J. McConnell** | IND | free agent | minutes | 25.1 | — | day-to-day, ESPN est. 20 Nov |
| **Precious Achiuwa** | SAC | free agent | minutes | 13.5 | 19.8 | day-to-day, ESPN est. 20 Nov |
| **Neemias Queta** | BOS | free agent | rest | 32.1 | — | active |
| **Myles Turner** | MIL | free agent | rest | 28.6 | — | day-to-day, ESPN est. 21 Nov |
| **Ryan Rollins** | MIL | free agent | rest | 27.1 | — | active |
| **Ja Morant** | POR | free agent | gap | 34.1 | — | out, ESPN est. 01 Dec |
| **Jaylen Brown** | PHI | Snow Time Lakers | injury | 42.4 | — | out, ESPN est. 23 Nov |
| **Brandin Podziemski** | GS | Matt Wright's Foxies | minutes | 28.0 | — | active |
| **Brandon Miller** | CHA | Matt Wright's Foxies | minutes | 24.6 | 22.6 | active |
| **Cooper Flagg** | DAL | Matt Wright's Foxies | rest | 46.8 | — | active |
| **Kyrie Irving** | DAL | Snow Time Lakers | rest | 43.0 | — | active |
| **Pascal Siakam** | IND | Matt Wright's Foxies | rest | 40.4 | — | active |
| **Tyler Herro** | MIL | Snow Time Lakers | rest | 30.4 | — | active |
| **Andrew Nembhard** | IND | Matt Wright's Foxies | rest | 25.9 | — | day-to-day, ESPN est. 20 Nov |
| **Jalen Brunson** | NY | Melbourne poopoo | injury | 46.2 | — | active |
| **Brandon Ingram** | LAC | Melbourne poopoo | injury | 36.5 | — | out, ESPN est. 21 Nov |
| **Paolo Banchero** | ORL | Dr White Slong | gap | 60.9 † | — | out, ESPN est. 29 Nov |

† Small sample: the rate rests on 2 games or fewer this season (after any dropped outlier).

## Our roster

### Scottie Barnes (TOR, SG/SF, us)

- Rate **48.0** · season 46.5 (10) → 50.3 (9) · L7 49.0 (2) · L15 44.0 (3) · L30 46.5 (10) → 50.3 (9) · projected 43.7
- ESPN: active
- **Injury:** not in ESPN's injury feed, but the news said on 18 Nov: "Barnes (injury management) has been ruled out for Wednesday's game against Washington, Esfandiar Baraheni of The Athletic reports."
- News (19 Nov): Barnes (groin) will play in Friday's game against the Pistons, Blake Murphy of Sportsnet.ca reports.
- News (18 Nov): Barnes (injury management) has been ruled out for Wednesday's game against Washington, Esfandiar Baraheni of The Athletic reports.
- **Research:**
  - Sat Wed 18 Nov vs WSH (2nd night of a back-to-back, groin injury management); off the injury report and playing Fri 20 Nov at DET. [NBC Sports, 2026-11-19](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/scottie-barnes-groin-removed-from-injury-report) · [RotoWire, 2026-11-19](https://www.rotowire.com/basketball/headlines/scottie-barnes-news-removed-from-injury-report-540046)
  - 36 and 34 min since returning, so no limit; rest on future back-to-backs possible but not announced.
  - Verdict: ESPN confirmed (active).

### Jalen Duren (DET, C, us)

- Rate **44.1** (small sample) · season 33.5 (2) → 44.0 (1) · L7 — · L15 — · L30 33.5 (2) → 44.0 (1) · projected 42.2
- ESPN: out, ESPN est. 24 Nov (Right Hamstring Strain, updated 2026-11-08)
- **Injury:** ESPN est. 24 Nov (Out, Right Hamstring Strain, updated 08 Nov), but the news said on 08 Nov: "Duren (hamstring) has begun on-court activity and will be re-evaluated in two weeks, Hunter Patterson of The Athletic reports."
- **Gap:** listed out, and no news in 5 days (ESPN est. 24 Nov)
- News (08 Nov): Duren (hamstring) has begun on-court activity and will be re-evaluated in two weeks, Hunter Patterson of The Athletic reports.
- News (25 Oct): Duren will be re-evaluated in two weeks due to a right hamstring strain, Eric Vincent of ClutchPoints.com reports.
- **Research:**
  - Pistons said 8 Nov he would be re-evaluated in two weeks (~22 Nov). [Detroit News, 2026-11-08](https://www.detroitnews.com/story/sports/nba/pistons/2026/11/08/pistons-all-star-jalen-duren-out-another-two-weeks-with-hamstring-strain/92677147007/)
  - Out Fri 20 Nov vs TOR (right hamstring), "re-evaluated next week"; no return date reported. [Heavy, 2026-11-20](https://heavy.com/sports/nba/detroit-pistons/injury-report-vs-raptors-november-20/)
  - Verdict: ESPN confirmed (24 Nov is consistent; a re-evaluation is not a return). No row: the 20 Nov report says "re-evaluated next week", which does not support a date before ESPN's.

### Saddiq Bey (NO, SF/PF, us)

- Rate **34.8** · role rate 36.0 · season 30.4 (16) · L7 41.0 (4) · L15 33.0 (9) · L30 30.4 (16) · projected 25.9
- ESPN: active
- **Role:** started 2 of his last 2 games after 3 of 14 before; 35.0 min in his starts, against 29.6 for the season
- **Minutes:** 38.7 min over his last 3 games against 29.6 for the season (+9.1)
- News (19 Nov): Bey logged 10 points (3-13 FG, 2-7 3Pt, 2-2 FT), eight rebounds, six assists and one steal across 42 minutes during Wednesday's 122-109 loss to the Pistons.
- News (17 Nov): Bey finished with 23 points (8-15 FG, 5-8 3Pt, 2-2 FT), six rebounds, three assists, one steal and one block across 33 minutes in Monday's 115-94 win over Golden State.
- **Research:**
  - Starting for Dejounte Murray (ankle; trade request, reportedly not playing for NO again) with Trey Murphy III out. [NBC Sports, 2026-11-13](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-13/pelicans-start-fears-jones-bey-zion-jordan) · [NBA.com injury report, 2026-11-17](https://www.nba.com/pelicans/news/pelicans-vs-pistons-injury-report-game-preview-11-18-2026)
  - Started 13, 16, 18 Nov at 35, 33, 42 min.
  - Trey Murphy III upgraded to questionable for Fri 20 Nov at OKC; NBC: Bey "will likely head back to the bench with Murphy available" and starts only "if Murphy remains out", so the role is tied to Murphy's absence and gets no row. [NBC Sports, 2026-11-19](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/trey-murphy-knee-questionable-friday-vs-thunder) · [NBC Sports, 2026-11-16](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-16/saddiq-bey-finishes-rout-with-team-high-23-points)
  - Verdict: nothing new found for a row: the starter's role is real but lasts only while Murphy sits; check NO's status before each game.

### Cade Cunningham (DET, PG, us)

- Rate **57.2** · role rate 58.9 · season 50.7 (13) · L7 66.7 (3) · L15 54.5 (6) · L30 50.7 (13) · projected 50.4
- ESPN: day-to-day, ESPN est. 20 Nov (Right Knee Soreness, updated 2026-11-19)
- **Minutes:** 40.7 min over his last 3 games against 35.0 for the season (+5.7)
- News (19 Nov): Cunningham (knee) is expected to play in Friday's game against the Raptors, Blake Murphy of Sportsnet.ca reports.
- News (18 Nov): Cunningham (knee) won't play in Wednesday's game against New Orleans.
- **Research:**
  - Sat 18 Nov at NO (right knee soreness, 2nd night of a back-to-back); expected to play Fri 20 Nov vs TOR. [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/pistons-cade-cunningham-expected-to-play-friday/) · [HoopsHype, 2026-11-19](https://www.hoopshype.com/story/sports/nba/rumors/2026/11/19/pistons-list-cade-cunningham-right-knee-soreness-as/92867630007/)
  - The 40.7-min 3-game figure includes a 48-min double-overtime game on 12 Nov; regulation games 36–38 min. No limit.
  - Verdict: ESPN confirmed.

### Daniss Jenkins (DET, PG, us)

- Rate **33.8** · role rate 37.8 · season 30.5 (14) · L7 36.5 (4) · L15 38.0 (7) · L30 30.5 (14)
- ESPN: active
- **Minutes:** 36.3 min over his last 3 games against 29.3 for the season (+7.0)
- News (19 Nov): Jenkins amassed 17 points (7-16 FG, 3-5 3Pt), four rebounds and nine assists over 36 minutes during Wednesday's 122-109 win over New Orleans.
- News (18 Nov): Jenkins closed Tuesday's 105-93 win over the Spurs with 25 points (11-21 FG, 3-7 3Pt), five rebounds, five assists and one steal over 38 minutes.
- **Research:**
  - Five straight starts at 36+ min, with Duncan Robinson (left quad, at least a week, no date) out. [Heavy, 2026-11-20](https://heavy.com/sports/nba/detroit-pistons/injury-report-vs-raptors-november-20/)
  - 18 Nov came with Cunningham out, 12 Nov was double overtime; expect ~33–35 min as a starter while Robinson is out.
  - Verdict: nothing new found (no source calls the role ongoing, so no row).

### Jalen Smith (CHI, PF/C, us)

- Rate **42.2** · season 36.1 (13) → 38.3 (12) · L7 45.7 (3) · L15 40.7 (6) → 46.8 (5) · L30 36.1 (13) → 38.3 (12) · projected 22.4
- ESPN: active
- **Rest:** back-to-back Sun 22–Mon 23 Nov; sat the second night of the 13–14 Nov back-to-back, playing the games either side
- News (19 Nov): Smith recorded 14 points (6-11 FG, 2-5 3Pt), six rebounds, three assists and one steal in 21 minutes during Wednesday's 137-107 win over the Nets.
- News (17 Nov): Smith (head) isn't listed on the injury report for Wednesday's game against Brooklyn.
- **Research:**
  - His 14 Nov absence was a precaution after a left hand/finger sprain on 13 Nov, not rest. [Bleacher Nation, 2026-11-14](https://www.bleachernation.com/bulls/2026/11/14/bulls-bullets-jalen-smith/)
  - Off the injury report for 18 Nov after a head knock ([CBS Sports, 2026-11-17](https://www.cbssports.com/fantasy/basketball/news/bulls-jalen-smith-fades-injury-report/)); the 21 min came in a 137-107 blowout. No planned rest reported for 22–23 Nov.
  - Verdict: nothing new found (false positive).

### Paul George (BOS, SF/PF, us)

- Rate **36.3** · season 40.2 (13) · L7 32.0 (3) · L15 36.7 (7) · L30 40.2 (13) · projected 38.5
- ESPN: active
- **Rest:** back-to-back Sat 21–Sun 22 Nov; sat the second night of the 01–02 Nov back-to-back, playing the games either side; sat the second night of the 10–11 Nov back-to-back, playing the games either side
- News (19 Nov): George supplied 10 points (3-12 FG, 1-7 3Pt, 3-3 FT), four rebounds, one assist, one block and three steals across 23 minutes before fouling out of Wednesday's 105-101 loss to Denver.
- News (14 Nov): George (illness) isn't listed on the injury report for Sunday's game against Dallas, Jack Simone of BostonSportsJournal.com reports.
- **Research:**
  - Sat the second night at Houston on 2 Nov for rest; per Keith Smith, Boston rests him on the second night of back-to-backs with travel. [HoopsHype, 2026-11-02](https://www.hoopshype.com/story/sports/nba/rumors/2026/11/02/paul-george-rest-out/92568567007/) · [HotTakes, updated 2026-11-19](https://hottakes.com/articles/paul-george-sits-out-celtics-rockets-clash-because-back-to-backs-remain-809d9de3-287d-456b-ab9b-c5b8da459c54)
  - Played both nights of 15–16 Nov (25 and 36 min). Nothing announced for 21–22 Nov.
  - Verdict: nothing new found; the road back-to-back rest pattern is confirmed, so he is a sit risk on Sun 22 Nov. No sit row (not announced).

## Free agents and waivers

### Jusuf Nurkic (UTAH, C, free agent)

- Rate **36.7** · season — · L7 — · L15 — · L30 — · projected 27.6
- ESPN: out, ESPN est. 27 Nov (Right Foot Strain, updated 2026-11-20)
- **Injury:** ESPN est. 27 Nov (Out, Right Foot Strain, updated 20 Nov), but the news said on 19 Nov: "It's unclear where he is in the recovery process, though he should be considered week-to-week until the team provides an update."
- News (19 Nov): Nurkic (toe) is listed as out for Friday's game against Phoenix.
- News (06 Nov): Nurkic (toe) has begun participating in on-court activities as he continues recovering from a right foot injury sustained during an Oct. 4 preseason game against Denver. He will be re-evaluated in two weeks, the Jazz announced Friday.
- **Research:**
  - Partial plantar plate tear (right second toe); Jazz said 6 Nov he would be re-evaluated in two weeks (~20 Nov). [Hoops Rumors, 2026-11](https://www.hoopsrumors.com/2026/11/jazz-center-jusuf-nurkic-out-at-least-two-more-weeks.html)
  - Ruled out Fri 20 Nov vs PHX, week-to-week; re-evaluation result pending; ramp-up likely, having not played this season. [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/jazzs-jusuf-nurkic-not-ready-to-return-friday/)
  - Verdict: ESPN confirmed (27 Nov = week-to-week floor). The existing 21 Nov override is superseded. Override: return 2026-11-27 (floor)

### Maxime Raynaud (SAC, C, free agent)

- Rate **28.1** · season — · L7 — · L15 — · L30 —
- ESPN: out, ESPN est. 25 Nov (Right Knee Dislocated, updated 2026-11-18)
- **Injury:** ESPN est. 25 Nov (Out, Right Knee Dislocated, updated 18 Nov), but the news said on 18 Nov: "He should be considered week-to-week moving forward."
- News (18 Nov): Raynaud (knee) will remain on the inactive list for Wednesday's game against the Suns.
- News (14 Nov): Raynaud (knee) has been ruled out for Sunday's game against the Thunder.
- **Research:**
  - Right patellar subluxation; "progressing, no official timeline". [NBC Sports, 2026-11-12](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-12/maxime-raynaud-knee-progressing-no-timeline)
  - Ruled out 18 Nov vs PHX, "still not close", week-to-week. [RotoWire, 2026-11-18](https://www.rotowire.com/basketball/headlines/maxime-raynaud-injury-still-out-wednesday-539684)
  - Verdict: ESPN confirmed (25 Nov = week-to-week floor); no timetable reported.

### Dejounte Murray (NO, PG/SG, free agent)

- Rate **27.2** · role rate 24.0 · season 30.6 (9) · L7 — · L15 20.8 (5) · L30 30.6 (9) · projected 39.0
- ESPN: out, ESPN est. 27 Nov (Ankle, updated 2026-11-13)
- **Injury:** ESPN est. 27 Nov (Out, Ankle, updated 13 Nov), but the news said on 13 Nov: "Shams Charania of ESPN noted Friday that the star guard won't be available for New Orleans for the time being, so Murray can be considered out indefinitely while the team tries to find him another home."
- **Minutes:** 24.7 min over his last 3 games against 31.4 for the season (−6.8)
- **Gap:** listed out, and no news in 5 days (ESPN est. 27 Nov)
- News (13 Nov): Murray (ankle) is out for Friday's game against Memphis.
- News (13 Nov): Murray (ankle) requested a trade from the Pelicans on Friday, per Shams Charania of ESPN.
- **Research:**
  - Still out (left ankle sprain) on NO's initial report for Fri 20 Nov vs OKC; the same report upgrades Trey Murphy III. [Roundtable, 2026-11-20](https://roundtable.io/sports/nba/pelicans/news/pelicans-star-trey-murphy-finally-upgraded-on-initial-injury-report-vs-thunder)
  - Requested a trade 13 Nov; Shams Charania reports he won't be available to New Orleans for the time being. [ESPN, 2026-11-13](https://www.espn.com/nba/story/_/id/50473732/sources-dejounte-murray-wants-trade-pelicans)
  - Weak market ("negative-value contract"; no active Suns talks). [Bleacher Report](https://bleacherreport.com/articles/25535329-new-dejounte-murray-trade-rumors-negative-value-contract-potential-deal-structure)
  - Verdict: ESPN corrected in substance: 27 Nov is a placeholder; he is out indefinitely until a trade.

### Robert Williams III (POR, C, free agent)

- Rate **23.2** · season 24.4 (12) · L7 19.7 (3) · L15 25.1 (7) · L30 24.4 (12) · projected 26.9
- ESPN: day-to-day, ESPN est. 21 Nov (Rest, updated 2026-11-20)
- **Injury:** ESPN est. 21 Nov (Day-To-Day, Rest, updated 20 Nov), but the news said on 17 Nov: "For the season, Williams has averaged 6.5 points, 6.5 rebounds and 1.1 blocks per contest in 11 games while shooting 63.3 percent from the floor."
- News (18 Nov): Williams (rest) is listed as out for Thursday's game versus the Bucks.
- News (18 Nov): Williams chipped in six points (2-2 FG, 2-2 FT), eight rebounds and four assists across 16 minutes during Tuesday's 106-105 loss to Minnesota.
- **Research:**
  - Rested Thu 19 Nov at MIL after playing both nights of the 16–17 Nov back-to-back; expected back Sat 21 Nov vs NY. Second rest day this month (also sat 7 Nov at SA). [FantasyPros, 2026-11-19](https://www.fantasypros.com/nba/news/621124/robert-williams-iii-rest-ruled-out-thursday.php) · [NBC Sports, 2026-11-18](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/robert-williams-rest-out-thursday-vs-milwaukee)
  - Verdict: ESPN confirmed (21 Nov). Expect rest days around back-to-backs.

### Scotty Pippen Jr. (MEM, PG/SG, free agent)

- Rate **16.3** · season 14.2 (5) · L7 — · L15 — · L30 14.2 (5) · projected 30.6
- ESPN: out, ESPN est. 25 Nov (Back Soreness, updated 2026-11-16)
- **Injury:** ESPN est. 25 Nov (Out, Back Soreness, updated 16 Nov), but the news said on 16 Nov: "Pippen (back) is progressing in his recovery but is still considered week-to-week."
- News (16 Nov): Pippen (back) is progressing in his recovery but is still considered week-to-week.
- News (10 Nov): Pippen (back) remains out for Wednesday's game against Denver, Michael Wallace of the Grizzlies' official site reports.
- **Research:**
  - Lumbar disc herniation, "week-to-week" on 16 Nov; out 19 Nov vs GS (11th straight absence), no timetable. [Yahoo Sports, 2026-11-16](https://sports.yahoo.com/articles/grizzlies-gg-jackson-ii-needs-172020038.html) · [Yahoo Sports, 2026-11-19](https://sports.yahoo.com/articles/warriors-vs-grizzlies-injury-report-234754065.html)
  - Verdict: no timetable reported; ESPN est. 25 Nov plausible. No row: the week-to-week floor (23 Nov) would only move ESPN's date earlier against "weeks" reporting.

### Bennedict Mathurin (NO, SG/SF, free agent)

- Rate **4.8** · season 8.8 (12) · L7 -3.0 (1) · L15 3.8 (5) · L30 8.8 (12) · projected 25.1
- ESPN: out, ESPN est. 27 Nov (Left Foot Plantar Fasciitis, updated 2026-11-19)
- **Injury:** ESPN est. 27 Nov (Out, Left Foot Plantar Fasciitis, updated 19 Nov), but the news said on 19 Nov: "Jordan Poole should remain in the backcourt rotation for the undermanned Pelicans moving forward, while Mathurin can be deemed week-to-week."
- News (19 Nov): Mathurin (foot) has been ruled out for Friday's game against the Thunder.
- News (17 Nov): Mathurin (foot) has been ruled out for Wednesday's game against Detroit.
- **Research:**
  - Out Fri 20 Nov vs OKC (left plantar fasciitis), fourth straight absence, "week-to-week". [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/pelicans-bennedict-mathurin-another-absence-coming/)
  - Verdict: no timetable reported; ESPN est. 27 Nov. No row.. No fantasy value either way.

### Quentin Grimes (LAL, SG/SF, free agent)

- Rate **35.2** · role rate 30.8 · season 24.0 (14) · L7 51.0 (3) · L15 31.8 (6) · L30 24.0 (14) · projected 28.1
- ESPN: active
- **Role:** started 2 of his last 2 games after 3 of 12 before; 36.8 min in his starts, against 28.6 for the season
- **Minutes:** 38.0 min over his last 3 games against 28.6 for the season (+9.4)
- News (19 Nov): Grimes ended with 20 points (8-20 FG, 4-10 3Pt), seven rebounds and four assists over 35 minutes during Wednesday's 109-97 loss to Utah.
- News (18 Nov): Grimes closed with 47 points (16-24 FG, 10-14 3Pt, 5-6 FT), six rebounds, three assists and one steal across 42 minutes during Tuesday's 118-114 overtime win over the Hornets.
- **Research:**
  - Austin Reaves (left heel bruise) out Fri 20 Nov, fourth straight; Grimes stays in the starting lineup while Reaves is out. [CBS Sports, 2026-11-19](https://cbssports.com/fantasy/basketball/news/lakers-austin-reaves-still-out-friday-540088)
  - Reaves improving, no structural damage, day-to-day. [NBA.com](https://www.nba.com/news/lakers-austin-reaves-heel-injury)
  - Verdict: role confirmed, short-term. Override: role 35 until 2026-11-22

### Mo Bamba (UTAH, C, waivers)

- Rate **34.3** · role rate 44.6 · season 31.1 (12) · L7 42.8 (4) · L15 33.1 (8) · L30 31.1 (12)
- ESPN: active
- **Role:** started 2 of his last 2 games after 1 of 10 before; 30.0 min in his starts, against 20.9 for the season
- **Minutes:** 30.0 min over his last 3 games against 20.9 for the season (+9.1)
- News (18 Nov): Bamba had 15 points (6-7 FG, 1-2 3Pt, 2-2 FT), 10 rebounds, three assists and one block across 31 minutes during Tuesday's 132-107 victory over the Clippers.
- News (15 Nov): Bamba recorded 26 points (10-13 FG, 6-6 3Pt, 0-3 FT), five rebounds, four assists, two steals and a block in 35 minutes during Sunday's 110-102 loss to the Spurs.
- **Research:**
  - Jaxson Hayes returned 18 Nov (25 min off the bench); Bamba started but played 22 min; Hayes may reclaim the start soon. [NBC Sports, 2026-11-19](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jaxson-hayes-knee-plays-25-minutes-in-return)
  - Nurkic trending toward a debut. [SI, 2026-11-17](https://www.si.com/nba/jazz/onsi/utah-jazz-vs-la-clippers-injury-report-who-s-trending-to-miss-game)
  - Verdict: the 30-minute role is over; the role rate of 44.6 overstates him. No row.

### Aday Mara (OKC, C, free agent)

- Rate **31.4** · season 27.1 (15) · L7 34.3 (3) · L15 33.1 (8) · L30 27.1 (15)
- ESPN: active
- **Role:** news on 18 Nov: "Mara will start in Wednesday's game versus Atlanta."
- News (18 Nov): Mara will start in Wednesday's game versus Atlanta.
- News (16 Nov): Mara closed with 16 points (8-11 FG), 13 rebounds and three assists across 26 minutes off the bench during Sunday's 125-103 win over Sacramento.
- **Research:**
  - Started 18 Nov vs ATL (5th start) for Kenrich Williams; 10 pts, 6 reb, 8 ast; OKC lineup keeps rotating with Holmgren out. [NBC/Rotoworld, 2026-11-18](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/thunder-to-start-shai-ajay-mccain-mara-i-hart) · [NBC/Rotoworld, 2026-11-18](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/aday-mara-records-10-points-eight-assists)
  - Minutes steady ~26 starting or not; no source calls the start ongoing. [CBS, 2026-11-18](https://www.cbssports.com/fantasy/basketball/news/thunders-aday-mara-starting-against-hawks/)
  - Verdict: nothing new found.

### Tyrese Proctor (CLE, SG, free agent)

- Rate **28.8** · role rate 30.8 · season 22.6 (15) · L7 39.5 (4) · L15 27.7 (9) · L30 22.6 (15)
- ESPN: active
- **Role:** started 2 of his last 2 games after 2 of 13 before; 27.8 min in his starts, against 20.3 for the season
- **Minutes:** 29.7 min over his last 3 games against 20.3 for the season (+9.3)
- News (17 Nov): Proctor had 17 points (6-13 FG, 2-6 3Pt, 3-5 FT), three rebounds, two assists, two steals and one block over 29 minutes during Monday's 126-115 victory over the Bulls.
- News (14 Nov): Proctor posted 24 points (10-19 FG, 4-13 3Pt), 11 rebounds and 10 assists across 34 minutes during Saturday's 127-117 win over Dallas.
- **Research:**
  - Started 14, 16, 18 Nov with Mobley (toe) and Tyson (ankle) out. [NBC/Rotoworld, 2026-11-18](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/cavs-start-harden-mitchell-proctor-mario-allen)
  - Rotoworld: likely back to the bench when Tyson returns (earliest 23 Nov); Mobley re-evaluated 7–10 days from 16 Nov. [ESPN, 2026-11-16](https://www.espn.com/nba/story/_/id/50505177/evan-mobley-sidelined-another-7-10-days-sprained-toe)
  - Verdict: ESPN corrected (short-term role). Override: role 27 until 2026-11-22

### Grayson Allen (CHA, PG/SG, free agent)

- Rate **28.6** · role rate 29.7 · season 26.8 (13) · L7 27.5 (2) · L15 31.6 (5) · L30 26.8 (13) · projected 26.6
- ESPN: out, ESPN est. 23 Nov (Concussion, updated 2026-11-19)
- **Role:** started 1 of his last 2 games after 2 of 11 before; 30.0 min in his starts, against 27.2 for the season
- News (19 Nov): Allen (concussion) has been ruled out for Friday's game against Atlanta.
- News (17 Nov): Allen (concussion-like symptoms) has been ruled out for Tuesday's game against the Lakers.
- **Research:**
  - Late scratch 17 Nov (concussion-like symptoms); OUT Fri 20 Nov vs ATL, in concussion protocol; no timetable reported. [CBS, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/hornets-grayson-allen-out-for-friday/) · [RotoWire, 2026-11-19](https://www.rotowire.com/basketball/headlines/grayson-allen-injury-out-for-friday-540053)
  - Role flag stale: back to the bench since Brandon Miller returned 15 Nov.
  - Verdict: nothing new found (ESPN est. 23 Nov plausible; protocol has no fixed date).

### Jakob Poeltl (TOR, C, free agent)

- Rate **27.1** · season 25.5 (13) · L7 24.8 (4) · L15 31.0 (8) · L30 25.5 (13) · projected 31.7
- ESPN: active
- **Role:** news on 18 Nov: "Poeltl will start Wednesday's game against the Wizards."
- News (18 Nov): Poeltl will start Wednesday's game against the Wizards.
- News (18 Nov): Poeltl closed Tuesday's 111-102 loss to the Knicks with three points (1-3 FG, 1-2 FT), six rebounds, one assist and one steal over 18 minutes.
- **Research:**
  - Started 18 Nov vs WSH only because Barrett (hamstring) and Barnes (rest) were out; 29 min. Bench behind Murray-Boyles 15 and 17 Nov at 17–18 min. [RotoWire, 2026-11-18](https://www.rotowire.com/basketball/headlines/jakob-poeltl-news-back-in-starting-lineup-539839)
  - Barnes's absence was one-game injury management. [Yahoo, 2026-11-18](https://ca.sports.yahoo.com/news/raptors-forward-barnes-against-wizards-183808081.html)
  - Verdict: nothing new found (one-off).

### Jaylon Tyson (CLE, SG/SF, free agent)

- Rate **23.1** · role rate 25.8 · season 19.2 (8) · L7 28.0 (2) · L15 20.3 (3) · L30 19.2 (8) · projected 25.6
- ESPN: out, ESPN est. 23 Nov (Right Ankle, updated 2026-11-19)
- **Role:** started 2 of his last 2 games after 0 of 6 before; 32.0 min in his starts, against 23.9 for the season
- **Minutes:** 29.0 min over his last 3 games against 23.9 for the season (+5.1)
- News (19 Nov): Tyson (ankle) has been ruled out for Friday's game against Indiana.
- News (18 Nov): Tyson (ankle) has been ruled out for Wednesday's game against Memphis.
- **Research:**
  - Ruled out Fri 20 Nov vs IND (third straight, right ankle injury management); next chance Mon 23 Nov at CHI. [CBS, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/cavaliers-jaylon-tyson-out-for-friday/) · [NBC/Rotoworld, 2026-11-19](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jaylon-tyson-ankle-remains-out-friday-vs-pacers)
  - Verdict: ESPN confirmed (23 Nov). No row (same as ESPN).

### Kasparas Jakucionis (MIL, PG, free agent)

- Rate **28.7** · role rate 26.3 · season 20.4 (15) · L7 44.7 (3) · L15 22.4 (8) · L30 20.4 (15) · projected 20.2
- ESPN: active
- **Minutes:** 24.7 min over his last 3 games against 19.1 for the season (+5.5)
- News (19 Nov): Jakucionis produced 20 points (6-8 FG, 3-5 3Pt, 5-6 FT), three rebounds, five assists and two steals over 26 minutes during Wednesday's 137-130 loss to Miami.
- News (16 Nov): Jakucionis finished with 25 points (9-16 FG, 4-10 3Pt, 3-3 FT), five rebounds, five assists and three steals across 26 minutes off the bench during Sunday's 113-106 loss to Atlanta.
- **Research:**
  - The minutes spike came with Ryan Rollins out ill (15 and 18 Nov, 26 min each); Rollins was off the report for 19 Nov and Jakucionis played 22. [Yahoo (NBC minutes report), 2026-11-19](https://sports.yahoo.com/articles/2026-27-nba-minutes-report-161955518.html) · [FantasyPros, 2026-11-19](https://www.fantasypros.com/nba/news/621206/ryan-rollins-illness-off-injury-report-thursday.php)
  - Verdict: nothing new found (one-off, over).

### Caleb Wilson (CHI, SF, free agent)

- Rate **28.0** · role rate 26.1 · season 34.9 (10) · L7 — · L15 17.7 (3) · L30 34.9 (10) · projected 34.9
- ESPN: out, ESPN est. 13 Dec (Right Hand, updated 2026-11-12)
- **Minutes:** 23.0 min over his last 3 games against 30.7 for the season (−7.7)
- News (12 Nov): Wilson is undergoing surgery for a fractured right hand and will miss at least four to six weeks, Shams Charania of ESPN reports.
- News (11 Nov): Wilson won't return to Wednesday's game against the Spurs due to a right hand injury. He'll finish with 15 points (5-7 FG, 2-2 3Pt, 3-3 FT), five rebounds and one steal in 15 minutes.
- **Research:**
  - Fractured right hand 11 Nov (15-min exit), surgery 12 Nov, out 4–6 weeks (about 10–24 Dec); re-evaluation ~3 weeks. [Yahoo, 2026-11-13](https://sports.yahoo.com/articles/caleb-wilson-injury-hand-surgery-233926022.html) · [Yahoo](https://sports.yahoo.com/articles/caleb-wilson-4-6-weeks-170006714.html)
  - Verdict: ESPN confirmed (est. 13 Dec sits inside 4–6 weeks).

### P.J. Washington (DAL, SF/PF, free agent)

- Rate **27.6** · role rate 23.3 · season 28.2 (15) · L7 24.8 (4) · L15 29.8 (8) · L30 28.2 (15) · projected 26.9
- ESPN: active
- **Minutes:** 25.3 min over his last 3 games against 30.9 for the season (−5.6)
- News (19 Nov): Washington posted 21 points (7-10 FG, 5-7 3Pt, 2-2 FT), five rebounds, two assists, three blocks and one steal over 25 minutes during Wednesday's 116-94 win over the Warriors.
- News (13 Nov): Washington accumulated 10 points (4-7 FG, 1-4 3Pt, 1-1 FT) and three rebounds over 16 minutes during Thursday's 133-94 loss to Minnesota.
- **Research:**
  - Still starts (18 Nov lineup Martin, Washington, Gafford, Flagg, Irving); low minutes came from blowouts (16 min in a 39-point loss at MIN). [CBS Sports, 2026-11-13](https://www.cbssports.com/fantasy/basketball/news/mavericks-p-j-washington-limited-to-16-minutes-in-blowout-loss/) · [Dallas Sports Journal](https://dallassportsjournal.com/dusty-may-mavericks-15-games-lineup-evaluation-rotation/)
  - A healthier frontcourt trims him to ~25–30 min. Verdict: nothing new found.

### T.J. McConnell (IND, PG, free agent)

- Rate **25.1** · season 22.5 (6) · L7 29.7 (3) · L15 22.5 (6) · L30 22.5 (6) · projected 24.4
- ESPN: day-to-day, ESPN est. 20 Nov (Right Hamstring Strain, updated 2026-11-19)
- **Minutes:** news on 17 Nov: "McConnell's minutes have been steadily ramping up since he made his regular-season debut Nov. 7, and he had his best game yet in Sunday's 131-124 loss to the 76ers, finishing with 12 points, five rebounds, five assists and one steal in 19 minutes off the bench."
- News (19 Nov): McConnell (hamstring) is listed as probable for Friday's game in Cleveland.
- News (18 Nov): McConnell recorded 14 points (7-10 FG), five assists, two rebounds and two steals over 18 minutes during the Packers' 119-104 loss to the Rockets on Wednesday.
- **Research:**
  - Probable Fri 20 Nov at CLE (right hamstring); minutes ramping 8, 14, 17, 19, 18 with Haliburton and Nembhard out. [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/pacers-t-j-mcconnell-probable-for-friday-538834/)
  - Nembhard (hip) questionable Friday, "won't be out long" per Carlisle; his return trims McConnell. [NBA.com, 2026-11-20](https://www.nba.com/pacers/news/preview-pacers-cavaliers-261120)
  - Verdict: ESPN confirmed (20 Nov).

### Precious Achiuwa (SAC, PF/C, free agent)

- Rate **13.5** · role rate 19.8 · season 25.4 (12) · L7 -3.0 (1) · L15 15.8 (5) · L30 25.4 (12) · projected 24.1
- ESPN: day-to-day, ESPN est. 20 Nov (Left Lower Leg Bruise, updated 2026-11-20)
- **Minutes:** 19.3 min over his last 3 games against 24.8 for the season (−5.5)
- News (19 Nov): Achiuwa is doubtful for Friday's game against the Lakers due to a left lower leg bruise.
- News (18 Nov): Achiuwa (lower leg) is available for Wednesday's game against the Suns.
- **Research:**
  - Doubtful Fri 20 Nov vs LAL (left lower-leg bruise); came back for only 8 min on 18 Nov. [RotoWire, 2026-11-19](https://www.rotowire.com/basketball/headlines/precious-achiuwa-injury-deemed-doubtful-for-friday-540091)
  - "Has seemingly fallen out of the rotation"; Keegan Murray took the start. [Yahoo (NBC minutes report), 2026-11-19](https://sports.yahoo.com/articles/2026-27-nba-minutes-report-161955518.html)
  - Verdict: ESPN corrected (mildly): 20 Nov is too early; 21 Nov at the earliest. No timetable reported.

### Neemias Queta (BOS, C, free agent)

- Rate **32.1** · season 27.3 (14) · L7 38.0 (2) · L15 30.4 (7) · L30 27.3 (14) · projected 27.2
- ESPN: active
- **Rest:** back-to-back Sat 21–Sun 22 Nov; news on 19 Nov: "Back in action after getting a breather Monday in the second half of a back-to-back, Queta delivered his second double-double of the season while setting a new season-high scoring mark."; sat the second night of the 15–16 Nov back-to-back, playing the games either side
- News (19 Nov): Queta notched 17 points (8-14 FG, 0-1 3Pt, 1-1 FT), 10 rebounds, three assists and two steals in 27 minutes during Wednesday's 105-101 loss to the Nuggets.
- News (17 Nov): Queta (rest) is available for Wednesday's game against the Nuggets, Jack Simone of BostonSportsJournal.com reports.
- **Research:**
  - Sat 16 Nov vs ORL (2nd night of a back-to-back, rest); off the report for 17 Nov. [RotoWire, 2026-11-16](https://www.rotowire.com/basketball/headlines/neemias-queta-news-sitting-out-monday-539449) · [NBC Sports, 2026-11-17](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-17/neemias-queta-rest-removed-from-injury-report)
  - Verdict: nothing new found; a one-night sit risk on 21–22 Nov, unconfirmed.

### Myles Turner (MIL, C, free agent)

- Rate **28.6** · season 26.6 (14) · L7 32.3 (3) · L15 26.3 (7) · L30 26.6 (14) · projected 28.4
- ESPN: day-to-day, ESPN est. 21 Nov (Left Shoulder Bruise, updated 2026-11-20)
- **Rest:** back-to-back Fri 27–Sat 28 Nov; sat the second night of the 10–11 Nov back-to-back, playing the games either side
- News (19 Nov): Turner has been ruled out for Thursday's game against Portland due to a left shoulder contusion.
- News (19 Nov): Turner posted four points (2-5 FG, 0-2 3Pt), five rebounds, four assists and three blocks in 21 minutes during Wednesday's 137-130 loss to Miami.
- **Research:**
  - Out Thu 19 Nov vs POR (left shoulder contusion); next chance Sat 21 Nov vs PHI. [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/bucks-myles-turner-sidelined-by-left-shoulder-contusion/) · [RotoWire, 2026-11-19](https://www.rotowire.com/basketball/headlines/myles-turner-injury-sidelined-by-left-shoulder-contusion-540024)
  - Verdict: ESPN confirmed (21 Nov).

### Ryan Rollins (MIL, PG/SG, free agent)

- Rate **27.1** · season 24.4 (14) · L7 28.5 (2) · L15 26.3 (7) · L30 24.4 (14) · projected 31.9
- ESPN: active
- **Rest:** back-to-back Fri 27–Sat 28 Nov; news on 19 Nov: "Rollins is off the injury report after missing back-to-back contests with an illness."
- News (19 Nov): Rollins (illness) is available for Thursday's game against Portland.
- News (18 Nov): Rollins (illness) has been ruled out for Wednesday's game at Miami.
- **Research:**
  - Misses on 15 and 18 Nov were illness, not rest; cleared for 19 Nov. [RotoWire, 2026-11-19](https://www.rotowire.com/basketball/headlines/ryan-rollins-news-cleared-from-injury-report-540025)
  - Verdict: nothing new found (false positive).

### Ja Morant (POR, PG, free agent)

- Rate **34.1** · season 33.8 (4) · L7 — · L15 — · L30 33.8 (4) · projected 37.5
- ESPN: out, ESPN est. 01 Dec (Left Hamstring, updated 2026-11-08)
- **Gap:** listed out, and no news in 5 days (ESPN est. 01 Dec)
- News (07 Nov): Head coach Micah Nori said Morant met with a doctor in Los Angeles, who gave him a positive outlook on his recovery from the hamstring injury. While Nori declined to update Morant's timetable, he added Morant "may not be out for as long as we thought," Trail Blazers Insider Sean Highkin reports.
- News (30 Oct): Morant has been diagnosed with a Grade 2 left hamstring strain and is expected to miss four weeks, Portland announced Friday.
- **Research:**
  - Grade 2 left hamstring strain; "re-evaluated in four weeks" (30 Oct), so ~27 Nov. [Trail Blazers, 2026-10-30](https://www.nba.com/blazers/news/ja-morant-injury-update)
  - Nori (7 Nov): "may not be out for as long as we thought", no new date. [NBC Sports, 2026-11-07](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-07/nori-morant-could-be-back-sooner-than-expected)
  - Verdict: ESPN corrected (slightly). Override: return 2026-11-28

## Opponents: this week and next

### Jaylen Brown (PHI, SG/SF, Snow Time Lakers)

- Rate **42.4** · season 40.8 (14) · L7 43.7 (3) · L15 41.9 (7) · L30 40.8 (14) · projected 38.6
- ESPN: out, ESPN est. 23 Nov (Left Hamstring, updated 2026-11-18)
- **Injury:** ESPN est. 23 Nov (Out, Left Hamstring, updated 18 Nov), but the news said on 18 Nov: "Brown (hamstring) will be re-evaluated at some point this weekend, per Kris Rihm of ESPN.com."
- News (18 Nov): Brown (hamstring) will be re-evaluated at some point this weekend, per Kris Rihm of ESPN.com.
- News (17 Nov): Brown is out for Wednesday's game against the Magic with a left hamstring strain.
- **Research:**
  - Left hamstring strain; out 18 Nov; to be re-evaluated before Sat 21 Nov vs MIL; 76ers bracing for multiple games missed, no timetable. [CBS Sports, 2026-11-18](https://www.cbssports.com/fantasy/basketball/news/76ers-jaylen-brown-no-timetable-for-return/) · [Yahoo/SI, 2026-11-18](https://sports.yahoo.com/articles/espn-insider-drops-latest-jaylen-013927700.html)
  - Verdict: ESPN confirmed (23 Nov); no row (the rule would only move it a day earlier, against the "multiple games" report).

### Brandin Podziemski (GS, PG/SG, Matt Wright's Foxies)

- Rate **28.0** · season 33.1 (14) · L7 20.5 (4) · L15 30.6 (8) · L30 33.1 (14) · projected 30.8
- ESPN: active
- **Minutes:** news on 19 Nov: "His consistent offensive involvement provides fantasy appeal, though poor shooting and fluctuating minutes limit his reliability."
- News (19 Nov): Podziemski accumulated 10 points (5-13 FG, 0-5 3Pt, 0-2 FT), three rebounds and four assists over 29 minutes during Wednesday's 116-94 loss to the Mavericks.
- News (17 Nov): Podziemski recorded 15 points (3-8 FG, 3-7 3Pt, 6-7 FT), six rebounds, three assists, one steal and two blocks across 30 minutes in Monday's 115-94 loss to the Pelicans.
- **Research:**
  - Minutes follow game script (37, 30, 29 recently) with Stephen Curry out (oblique tear, ~a month from 12 Nov); the low L7 is shooting (38.5% FG over 5), not role. [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/warriors-brandin-podziemski-goes-cold-from-deep-in-dallas/)
  - Verdict: nothing new found.

### Brandon Miller (CHA, SG/SF, Matt Wright's Foxies)

- Rate **24.6** · role rate 22.6 · season 29.5 (12) · L7 24.5 (2) · L15 15.8 (4) · L30 29.5 (12) · projected 37.4
- ESPN: active
- **Minutes:** 23.3 min over his last 3 games against 30.5 for the season (−7.2)
- News (18 Nov): Miller amassed 28 points (10-19 FG, 5-12 3Pt, 3-3 FT), two rebounds, four assists and one block in 32 minutes during Tuesday's 118-114 overtime loss to the Lakers.
- News (16 Nov): Miller finished Sunday's 113-105 loss to the Clippers with five points (1-10 FG, 1-6 3Pt, 2-3 FT), four assists, two rebounds and one steal over 24 minutes.
- **Research:**
  - On a minutes restriction after his hip strain: held out of overtime 17 Nov "solely due to a minutes restriction", after 32 min in regulation; no end date. [SI, 2026-11-19](https://www.si.com/nba/hornets-bizarre-decision-rest-starters-ot-nba-injury-problem) · [Yahoo](https://sports.yahoo.com/articles/hornets-coach-explains-why-brandon-104117242.html)
  - Verdict: ESPN confirmed; no row (cap allows ~32 min, no end date).

### Cooper Flagg (DAL, SF/PF, Matt Wright's Foxies)

- Rate **46.8** · season 51.0 (14) · L7 40.5 (4) · L15 50.8 (8) · L30 51.0 (14) · projected 45.4
- ESPN: active
- **Rest:** back-to-back Sat 21–Sun 22 Nov; sat the second night of the 23–24 Oct back-to-back, playing the games either side
- News (19 Nov): Flagg chipped in 33 points (11-15 FG, 3-5 3Pt, 8-8 FT), five rebounds, nine assists and four steals across 34 minutes during Wednesday's 116-94 victory over the Warriors.
- News (16 Nov): Flagg contributed 17 points (5-15 FG, 2-6 3Pt, 5-5 FT), three rebounds, four assists, one block and one steal in 27 minutes during Sunday's 131-94 loss to the Celtics.
- **Research:**
  - The 24 Oct absence was a mild left shoulder sprain, not rest; he played both nights of 14–15 Nov. [NBC Sports, 2026-10-24](https://www.nbcsports.com/fantasy/basketball/player-news/2026-10-24/cooper-flagg-shoulder-out-saturday-vs-spurs)
  - Verdict: nothing new found (false positive).

### Kyrie Irving (DAL, PG, Snow Time Lakers)

- Rate **43.0** · season 41.8 (12) · L7 45.3 (3) · L15 41.4 (7) · L30 41.8 (12) · projected 44.2
- ESPN: active
- **Rest:** back-to-back Sat 21–Sun 22 Nov; news on 19 Nov: "After sitting out the second game of a weekend back-to-back set, Irving returned to action and delivered decent numbers."; sat the second night of the 23–24 Oct back-to-back, playing the games either side; sat the second night of the 14–15 Nov back-to-back, playing the games either side
- News (19 Nov): Irving supplied 17 points (7-15 FG, 1-6 3Pt, 2-2 FT), six rebounds, five assists and two steals over 29 minutes during Wednesday's 116-94 win over Golden State.
- News (17 Nov): Irving (knee) is not listed on the injury report ahead of Wednesday's game against the Warriors.
- **Research:**
  - Sat the second night of 2 of 3 back-to-backs (knee management, post-ACL); Dusty May decides on the morning and calls the sits "not predictable". [RotoWire, 2026-11-17](https://rotowire.com/basketball/headlines/kyrie-irving-news-off-injury-report-for-wednesday-539644) · [Hoops Rumors, 2026-11-09](https://www.hoopsrumors.com/2026/11/mavs-notes-irving-aldama-johnson-martin-new-balance.html)
  - Verdict: nothing new found; likely sit risk Sun 22 Nov (not announced, so no row).

### Pascal Siakam (IND, PF, Matt Wright's Foxies)

- Rate **40.4** · season 40.1 (14) · L7 37.3 (3) · L15 44.4 (7) · L30 40.1 (14) · projected 41.1
- ESPN: active
- **Rest:** back-to-back Sun 22–Mon 23 Nov, Fri 27–Sat 28 Nov; news on 18 Nov: "He's been locked in over the past two games, totaling 55 points, five assists and four steals on 61.1 percent shooting from the field and 90.0 percent at the line, but despite his efforts, Indiana has suffered back-to-back losses."; sat the second night of the 01–02 Nov back-to-back, playing the games either side
- News (18 Nov): Siakam chipped in 24 points (10-17 FG, 2-2 3Pt, 2-2 FT), four rebounds, three assists, one block and three steals across 33 minutes during Wednesday's 119-104 loss to the Rockets.
- News (15 Nov): Siakam recorded 31 points (12-19 FG, 0-3 3Pt, 7-8 FT), two rebounds, two assists and one steal across 34 minutes during Sunday's 131-124 loss to Philadelphia.
- **Research:**
  - One rest night (2 Nov, Pacers rested starters); playing 32–35 min with Haliburton out. [FantasyPros](https://www.fantasypros.com/nba/news/617291/pascal-siakam-rest-ruled-out-monday.php) · [NBC Sports, 2026-11-18](https://nbcsports.com/fantasy/basketball/player-news/2026-11-18/pascal-siakam-scores-24-gets-three-steals)
  - Verdict: nothing new found; possible risk 23 and 28 Nov, unannounced.

### Tyler Herro (MIL, PG/SG, Snow Time Lakers)

- Rate **30.4** · season 32.4 (15) → 34.5 (14) · L7 19.5 (4) → 25.0 (3) · L15 27.2 (8) → 30.7 (7) · L30 32.4 (15) → 34.5 (14) · projected 38.8
- ESPN: active
- **Rest:** back-to-back Fri 27–Sat 28 Nov; sat the first night of the 10–11 Nov back-to-back, playing the games either side
- News (19 Nov): Herro ended Wednesday's 137-130 loss to Miami with eight points (4-11 FG, 0-5 3Pt, 0-1 FT), two rebounds, four assists and one steal over 24 minutes.
- News (13 Nov): Herro had 18 points (5-17 FG, 2-7 3Pt, 6-7 FT), two assists, two steals, one rebound and one block across 34 minutes in Friday's 107-99 loss to the Magic.
- **Research:**
  - The 10 Nov absence was a right knee contusion, not rest; he played both nights of 18–19 Nov. [NBC Sports, 2026-11-11](https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-11/tyler-herro-knee-a-game-time-decision-wednesday)
  - Low L7 is shooting (10-for-41 over three games) at 24–35 min. [CBS Sports, ~2026-11-18](https://www.cbssports.com/fantasy/basketball/news/bucks-tyler-herro-shooting-slump-continues-in-miami-return/)
  - Verdict: nothing new found (false positive).

### Andrew Nembhard (IND, PG/SG, Matt Wright's Foxies)

- Rate **25.9** · season 33.2 (11) · L7 12.0 (1) · L15 31.8 (5) · L30 33.2 (11) · projected 28.2
- ESPN: day-to-day, ESPN est. 20 Nov (Left Hip Soreness, updated 2026-11-19)
- **Rest:** back-to-back Sun 22–Mon 23 Nov, Fri 27–Sat 28 Nov; sat the second night of the 25–26 Oct back-to-back, playing the games either side; sat the second night of the 01–02 Nov back-to-back, playing the games either side
- News (19 Nov): Nembhard (hip) is questionable for Friday's game in Cleveland.
- News (18 Nov): Nembhard (hip) won't play in Wednesday's game against the Rockets, Tony East of Forbes.com reports.
- **Research:**
  - Questionable Fri 20 Nov at CLE (left hip soreness) after two missed games; Carlisle: won't be out long. [CBS Sports, 2026-11-19](https://www.cbssports.com/fantasy/basketball/news/pacers-andrew-nembhard-could-miss-another-game-friday/)
  - Verdict: ESPN confirmed (day-to-day, 20 Nov); hip is a back-to-back risk, no sit date.

## Other rosters: injury flags only

### Jalen Brunson (NY, PG, Melbourne poopoo)

- Rate **46.2** · season 41.9 (15) · L7 50.0 (4) · L15 47.6 (8) · L30 41.9 (15) · projected 43.8
- ESPN: active
- **Injury:** not in ESPN's injury feed, but the news said on 19 Nov: "Brunson exited to the locker room in the first quarter of Thursday's game against Minnesota due to an apparent facial injury, Jared Schwartz of the New York Post reports."
- News (19 Nov): Brunson (face) returned to Thursday's game against the Timberwolves with 2:47 remaining in the first quarter, per the broadcast.
- News (19 Nov): Brunson exited to the locker room in the first quarter of Thursday's game against Minnesota due to an apparent facial injury, Jared Schwartz of the New York Post reports.
- **Research:**
  - Took a blow to the face 19 Nov at MIN, returned in the first quarter and finished (35 min); no diagnosis or designation. [RotoWire, 2026-11-19](https://www.rotowire.com/basketball/headlines/jalen-brunson-injury-exits-to-locker-room-540089)
  - Verdict: ESPN confirmed (active).

### Brandon Ingram (LAC, SF/PF, Melbourne poopoo)

- Rate **36.5** · season — · L7 — · L15 — · L30 — · projected 38.5
- ESPN: out, ESPN est. 21 Nov (Right Achilles Surgery, updated 2026-11-18)
- **Injury:** ESPN est. 21 Nov (Out, Right Achilles Surgery, updated 18 Nov), but the news said on 18 Nov: "Ingram was cleared for full-contact work Nov. 6, and he's been playing 5-on-5 for the past couple of weeks."
- News (18 Nov): Ingram (heel/Achilles) will remain on the inactive list for Thursday's game in San Antonio.
- News (12 Nov): Ingram (Achilles) won't play in Friday's game against the Thunder, per Law Murray of The Athletic.
- **Research:**
  - Inactive 19 Nov at SA; cleared for contact 6 Nov; Lue hopes for a debut on this road trip (Sat 21 Nov at DAL possible, unconfirmed); expect a minutes limit. [CBS Sports, 2026-11-18](https://www.cbssports.com/fantasy/basketball/news/clippers-brandon-ingram-not-ready-for-season-debut/) · [Hoops Rumors, 2026-11](https://www.hoopsrumors.com/2026/11/l-a-notes-ingram-clippers-thiero-doncic-carr-james.html)
  - Verdict: ESPN confirmed (21 Nov = earliest possible debut).

### Paolo Banchero (ORL, SF/PF, Dr White Slong)

- Rate **60.9** (small sample) · season 47.0 (2) → 65.0 (1) · L7 — · L15 — · L30 47.0 (2) → 65.0 (1) · projected 39.0
- ESPN: out, ESPN est. 29 Nov (Right Ankle Sprain, updated 2026-10-24)
- **Gap:** listed out, and no news in 5 days (ESPN est. 29 Nov)
- News (24 Oct): Banchero is expected to be sidelined for the next four-to-six weeks due to a right high-ankle sprain, Shams Charania of ESPN reports.
- News (23 Oct): Banchero didn't check back in during the fourth quarter of Friday's 115-93 loss to the Timberwolves after being deemed doubtful to return. He finished with 14 points (5-11 FG, 0-2 3Pt, 2-4 FT), six rebounds, five assists and one steal across 26 minutes.
- **Research:**
  - Right high-ankle sprain; Banchero 19 Nov: "hopefully within the next couple of weeks" (~3 Dec); Sweeney: no timetable. [Basketnews, 2026-11-19](https://basketnews.com/news-259854-paolo-banchero-shares-major-update-on-his-recovery-from-ankle-injury.html) · [Yahoo](https://sports.yahoo.com/articles/sean-sweeney-provides-paolo-banchero-215307729.html)
  - Verdict: ESPN partly confirmed: no timetable reported, ESPN est. 29 Nov looks a few days early.

## Sources

- ESPN fantasy player news (`site.api.espn.com/apis/fantasy/v2/games/fba/news/players`), ESPN's NBA injury feed, ESPN box scores (cached in `council/.cache/box`), and league 423671879 (`kona_player_info`, `mTeam`, `proTeamSchedules_wl`), read 2026-11-20 06:55 UTC.
- <https://basketnews.com/news-259854-paolo-banchero-shares-major-update-on-his-recovery-from-ankle-injury.html>
- <https://bleacherreport.com/articles/25535329-new-dejounte-murray-trade-rumors-negative-value-contract-potential-deal-structure>
- <https://ca.sports.yahoo.com/news/raptors-forward-barnes-against-wizards-183808081.html>
- <https://cbssports.com/fantasy/basketball/news/lakers-austin-reaves-still-out-friday-540088>
- <https://dallassportsjournal.com/dusty-may-mavericks-15-games-lineup-evaluation-rotation/>
- <https://globalnews.ca/news/12158569/barrett-murray-boyles-put-on-raptors-injured-list>
- <https://heavy.com/sports/nba/detroit-pistons/injury-report-vs-raptors-november-20/>
- <https://hottakes.com/articles/paul-george-sits-out-celtics-rockets-clash-because-back-to-backs-remain-809d9de3-287d-456b-ab9b-c5b8da459c54>
- <https://nbcsports.com/fantasy/basketball/player-news/2026-11-18/pascal-siakam-scores-24-gets-three-steals>
- <https://rotowire.com/basketball/headlines/kyrie-irving-news-off-injury-report-for-wednesday-539644>
- <https://roundtable.io/sports/nba/pelicans/news/pelicans-star-trey-murphy-finally-upgraded-on-initial-injury-report-vs-thunder>
- <https://sports.yahoo.com/articles/2026-27-nba-minutes-report-161955518.html>
- <https://sports.yahoo.com/articles/caleb-wilson-4-6-weeks-170006714.html>
- <https://sports.yahoo.com/articles/caleb-wilson-injury-hand-surgery-233926022.html>
- <https://sports.yahoo.com/articles/espn-insider-drops-latest-jaylen-013927700.html>
- <https://sports.yahoo.com/articles/grizzlies-gg-jackson-ii-needs-172020038.html>
- <https://sports.yahoo.com/articles/hornets-coach-explains-why-brandon-104117242.html>
- <https://sports.yahoo.com/articles/sean-sweeney-provides-paolo-banchero-215307729.html>
- <https://sports.yahoo.com/articles/warriors-vs-grizzlies-injury-report-234754065.html>
- <https://www.bleachernation.com/bulls/2026/11/14/bulls-bullets-jalen-smith/>
- <https://www.cbssports.com/fantasy/basketball/news/76ers-jaylen-brown-no-timetable-for-return/>
- <https://www.cbssports.com/fantasy/basketball/news/bucks-myles-turner-sidelined-by-left-shoulder-contusion/>
- <https://www.cbssports.com/fantasy/basketball/news/bucks-tyler-herro-shooting-slump-continues-in-miami-return/>
- <https://www.cbssports.com/fantasy/basketball/news/bulls-jalen-smith-fades-injury-report/>
- <https://www.cbssports.com/fantasy/basketball/news/cavaliers-jaylon-tyson-out-for-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/clippers-brandon-ingram-not-ready-for-season-debut/>
- <https://www.cbssports.com/fantasy/basketball/news/hornets-grayson-allen-out-for-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/jazzs-jusuf-nurkic-not-ready-to-return-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/kings-maxime-raynaud-still-out-for-tuesday/>
- <https://www.cbssports.com/fantasy/basketball/news/mavericks-p-j-washington-limited-to-16-minutes-in-blowout-loss/>
- <https://www.cbssports.com/fantasy/basketball/news/pacers-andrew-nembhard-could-miss-another-game-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/pacers-t-j-mcconnell-probable-for-friday-538834/>
- <https://www.cbssports.com/fantasy/basketball/news/pelicans-bennedict-mathurin-another-absence-coming/>
- <https://www.cbssports.com/fantasy/basketball/news/pistons-cade-cunningham-expected-to-play-friday/>
- <https://www.cbssports.com/fantasy/basketball/news/rockets-fred-vanvleet-to-miss-back-to-backs/>
- <https://www.cbssports.com/fantasy/basketball/news/thunders-aday-mara-starting-against-hawks/>
- <https://www.cbssports.com/fantasy/basketball/news/warriors-brandin-podziemski-goes-cold-from-deep-in-dallas/>
- <https://www.detroitnews.com/story/sports/nba/pistons/2026/11/08/pistons-all-star-jalen-duren-out-another-two-weeks-with-hamstring-strain/92677147007/>
- <https://www.espn.com/nba/story/_/id/50473732/sources-dejounte-murray-wants-trade-pelicans>
- <https://www.espn.com/nba/story/_/id/50505177/evan-mobley-sidelined-another-7-10-days-sprained-toe>
- <https://www.espn.com/nba/story/_/id/50513506/hawks-lose-cj-mccollum-least-4-weeks-calf-strain>
- <https://www.fantasypros.com/nba/news/617291/pascal-siakam-rest-ruled-out-monday.php>
- <https://www.fantasypros.com/nba/news/621124/robert-williams-iii-rest-ruled-out-thursday.php>
- <https://www.fantasypros.com/nba/news/621206/ryan-rollins-illness-off-injury-report-thursday.php>
- <https://www.hoopshype.com/story/sports/nba/rumors/2026/11/02/paul-george-rest-out/92568567007/>
- <https://www.hoopshype.com/story/sports/nba/rumors/2026/11/19/pistons-list-cade-cunningham-right-knee-soreness-as/92867630007/>
- <https://www.hoopsrumors.com/2026/11/jazz-center-jusuf-nurkic-out-at-least-two-more-weeks.html>
- <https://www.hoopsrumors.com/2026/11/l-a-notes-ingram-clippers-thiero-doncic-carr-james.html>
- <https://www.hoopsrumors.com/2026/11/mavs-notes-irving-aldama-johnson-martin-new-balance.html>
- <https://www.nba.com/blazers/news/ja-morant-injury-update>
- <https://www.nba.com/jazz/news/jusuf-nurkic-injury-update-2>
- <https://www.nba.com/news/lakers-austin-reaves-heel-injury>
- <https://www.nba.com/pacers/news/preview-pacers-cavaliers-261120>
- <https://www.nba.com/pelicans/news/pelicans-shootaround-update-nets-tip-off-important-five-game-new-orleans-homestand>
- <https://www.nba.com/pelicans/news/pelicans-vs-pistons-injury-report-game-preview-11-18-2026>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-10-24/cooper-flagg-shoulder-out-saturday-vs-spurs>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-07/nori-morant-could-be-back-sooner-than-expected>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-11/nic-claxton-scores-17-points-in-16-minutes>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-11/tyler-herro-knee-a-game-time-decision-wednesday>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-12/maxime-raynaud-knee-progressing-no-timeline>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-13/pelicans-start-fears-jones-bey-zion-jordan>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-16/saddiq-bey-finishes-rout-with-team-high-23-points>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-17/neemias-queta-rest-removed-from-injury-report>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/aday-mara-records-10-points-eight-assists>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/cavs-start-harden-mitchell-proctor-mario-allen>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/robert-williams-rest-out-thursday-vs-milwaukee>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-18/thunder-to-start-shai-ajay-mccain-mara-i-hart>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jaxson-hayes-knee-plays-25-minutes-in-return>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/jaylon-tyson-ankle-remains-out-friday-vs-pacers>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/scottie-barnes-groin-removed-from-injury-report>
- <https://www.nbcsports.com/fantasy/basketball/player-news/2026-11-19/trey-murphy-knee-questionable-friday-vs-thunder>
- <https://www.rotowire.com/basketball/headlines/cj-mccollum-news-leads-hawks-bench-with-21-points-538466>
- <https://www.rotowire.com/basketball/headlines/grayson-allen-injury-out-for-friday-540053>
- <https://www.rotowire.com/basketball/headlines/jakob-poeltl-news-back-in-starting-lineup-539839>
- <https://www.rotowire.com/basketball/headlines/jalen-brunson-injury-exits-to-locker-room-540089>
- <https://www.rotowire.com/basketball/headlines/maxime-raynaud-injury-still-out-wednesday-539684>
- <https://www.rotowire.com/basketball/headlines/myles-turner-injury-sidelined-by-left-shoulder-contusion-540024>
- <https://www.rotowire.com/basketball/headlines/neemias-queta-news-sitting-out-monday-539449>
- <https://www.rotowire.com/basketball/headlines/precious-achiuwa-injury-deemed-doubtful-for-friday-540091>
- <https://www.rotowire.com/basketball/headlines/ryan-rollins-news-cleared-from-injury-report-540025>
- <https://www.rotowire.com/basketball/headlines/scottie-barnes-news-removed-from-injury-report-540046>
- <https://www.si.com/nba/hornets-bizarre-decision-rest-starters-ot-nba-injury-problem>
- <https://www.si.com/nba/jazz/onsi/utah-jazz-vs-la-clippers-injury-report-who-s-trending-to-miss-game>
