# New Era Fantasy Football: Master File

**Last updated:** 2026-10-28. Maintained by Claude with Big Blue (Game Warden).

**What this is.** The single source of truth for the New Era hub project. Read this file first in any new chat.

**Companion files**
- `new-era-rulebook.md`: the official rulebook. Claude maintains it.
- Claude Doc "New Era Fantasy Hub — Master Plan" (https://claude.ai/artifact/JB5UzSMY1i6mRSBkx61Cra): long-form plan with feature tables.
- Repo `Msefyousef/league-page`, branch `new-era`: the code. It also has copies of these files under `docs/`.

---

## 1. The goal
A premium, installable web app (PWA) for every New Era league (est. 2010) that feels like "Sleeper meets Yahoo, made by a real company."

- It offers insight, history, community, giving, and rules enforcement.
- Lineups and trades stay on Sleeper and Yahoo, because both APIs are read-only. The app links out to them.
- This is Big Blue's side quest. He wants low effort on his end, with Claude doing the heavy lifting.

## 2. Leagues
| League | Platform | Format | Status | IDs |
| --- | --- | --- | --- | --- |
| NE2K | Yahoo | Redraft. The flagship and "heart and soul"; "Pen N' Paper Gang" | Sitting out 2026. Shown as a locked "Coming Back Soon" card with a return hub | — |
| NFIF (No Friends in Fantasy) | Sleeper | Dynasty, IDP, 10 teams | Live first | 2026: `1312083874368458752` (2025: `1183104551146070016`, 2024 chain: `1161043070113300480`) |
| Only Kangaroos | Yahoo | Guillotine ("Death League"), 18 teams | Phase 2, needs the Yahoo key | — |

**NFIF Sleeper users:**
- DaBoiTeb
- Moonie08
- BigBlueKangaroo (Big Blue)
- khader91 (Khader)
- BirdNation86
- D215
- moewilly (Mo Willy)
- med824 (Ehmed)
- fuzzmanchu (Fuzz)
- Larry516

## 3. Leadership
**Game Warden: Big Blue.** Top authority across New Era (rulebook 4b), and the creative director. Give the title respect everywhere: its own badge, top of the role hierarchy, and the name the AI Commissioner uses.

| League | Commissioner | Co-commissioner |
| --- | --- | --- |
| NFIF | Khader | Big Blue |
| Only Kangaroos | Big Blue (sole) | — |
| NE2K | Big Blue, if the league returns | — |

**Khader and NFIF:** Khader is the public face of NFIF. Give him visible credit in NFIF announcements, for example "Approved by Commissioner Khader and the Game Warden."

**Damen:** no longer a commissioner. The rulebook (section 15) still lists him; update it when NE2K's return is decided.

**Why rules must be enforced by the app:** in 2025, managers pressured a commissioner to reopen trading after the deadline, close to the Purge. It nearly ended the league. Big Blue has carried New Era for 16–17 years and felt unappreciated. The app must enforce rules mechanically, so no person can be pressured into bending them.

## 4. Working agreements
- **Rule changes:** Claude may implement first and ask later when Big Blue approves in chat. Edit `new-era-rulebook.md` and log each change in its "Latest updates."
- **Announcing rule changes in the app:** present them as AI Commissioner recommendations, approved by the commissioner and the Game Warden.
- **AI Commissioner (not "assistant"):**
  - Answers only from the rulebook and always cites the section.
  - Its rulings are advisory. Final rulings belong to the Game Warden and commissioners.
  - It holds the line on deadlines; section 13c says the deadline can't be extended.
- **Values:**
  - No gambling, betting odds, sportsbooks, or prizes for money in the app.
  - The app does not handle buy-ins.
  - Giving is encouraged, never sold as a way to get results.

## 5. Key dates for 2026 (from Sleeper's calendar; week 1 Sunday was Sep 13)
| Event | When |
| --- | --- |
| NFIF trade deadline | Sat Nov 14, 11:59pm ET |
| NE2K trade deadline (if active) | Saturday of week 11 |
| Purge Draw (live, automatic) | Sun Nov 22, proposed 11am ET |
| Purge window (if yes) | Wed Nov 25, 5–10pm ET |
| New Era Champion game (NE2K champ vs NFIF champ) | Week 17 |

No Purge was drawn before the 2026 season, so the live draw on Nov 22 is the first one in the app. **This sets the build deadline for the Purge drum.**

## 6. Brand
**Mascot: the blue kangaroo, "Big Blue."**
- Wears #80 as a Victor Cruz nod.
- His rival is the brown Eagles kangaroo, #5 "McNabb."
- In the app, the mascots wear custom New Era jerseys with no NFL logos. The original art lives in a gallery.

**Permanent logos (they never change):**
- **New Era is the main logo for the whole app.** A tan kangaroo inside a compass-burst circle with "The New Era Fantasy Football" in bronze. Saved in the repo as `static/brand/new-era-logo-dark.png` (transparent background).
- **NFIF:** a silver crest with a kangaroo gripping the letters, "No Friends in Fantasy Football League". Saved as `static/brand/nfif-logo-dark.png`, `nfif-logo-light.png` and `nfif-logo-outline.png`.
- **Everything else, including NE2K and Only Kangaroos, follows that season's theme.**

**League colors**

| League | Colors |
| --- | --- |
| New Era | Gold and tan (Kangaroo gold for champions) |
| NFIF | Black and silver crest |
| NE2K | Purple on black graffiti (the current trophy and profile logo). Alternates: the red triangle kangaroo, and the gold rainbow plaque as its retro badge |

The app uses a dark base.

**Champion title:** the Kangaroo. Motto: "No Friends in Fantasy… Not Even Cousins."

**Lore**

| Term | Meaning |
| --- | --- |
| Malukee | Putting a hex on someone's team by praising it |
| CMC Scandal | NE2K |
| Pen N' Paper Gang | NE2K |
| The Purge | Uses kangaroo Purge masks |
| Megatron takeover | The trophy's third form |
| Other terms | 2 for 20, Big Blue vs Big Green, Game Warden, Fowzi Dollar Tuesdays |

**Trophy:** fully custom; it has gone through 3 forms. More photos are still to come. Design notes in "New Era Trophy.docx": black and purple, kangaroos, a "RESIST" Palestine element, and the champions list.

**Socials and media**
- Instagram: @ne2kffl. Handles for the NFIF, Only Kangaroos, and New Era accounts are still to collect.
- NE2K Music: [Apple Music](https://music.apple.com/ca/artist/ne2k-music/1790518335), Amazon, [YouTube @NE2kMusic](https://www.youtube.com/@NE2kMusic/videos).
  - EP "NE2kXV".
  - Singles: "Megatron Freestyle", "I Got No FAAB", "Good Win", "I'm Sorry for Snapping in the Groupchat".
  - These will go in an "NE2K Radio" section.
- No Friends in Fantasy podcast/show: Big Blue and Fuzz. Its art is the blue and brown kangaroos.

**Art workflow:** Big Blue generates mascot art in his image tool using prompts Claude writes. Claude handles cutouts, icons, splash screens, and in-app art built in code.

## 6b. What the @ne2kffl Instagram shows (screenshots, Nov 6)
- **Bio:** "NE2k | A New Era Fantasy Football League. Home of the Kangaroo, Malukee, & Good Wins." It links to @NewEraFantasy, @nofriendsinfantasy, and a Chuffed campaign (chuffed.org/project/192408…). 465 posts.
- **Lineage:** New Era came first, and NE2K is the original league. New Era is now the umbrella name for the collection of leagues.
- **Logos:**
  - NE2K: purple graffiti profile logo; black geometric kangaroo inside a red triangle ("NE2K Fantasy Football League"); the gold and rainbow NE2K plaque.
  - Only Kangaroos: red kangaroo over "ONLY KANGAROO'S – Guillotine Fantasy Football League".
  - NE2K Music: neon logo.
  - Eid Mubarak art: a kangaroo in a keffiyeh.
- **Purge look:** black backgrounds with neon LED "Purge masks" (red X eyes; stitched grins in red, green and cyan). Other assets: "The Purge – New Era Event," "TRADE ALERT – PURGE" badges, "A New Era Event: THE PURGE," "Stop the Purge" protest art, and a "30 hours" countdown. A Purge was held on Friday 11/15 in an earlier season.
- **Recurring content (the app should automate or host these):**
  - "Mike's Matchup of the Week"
  - Weekly member video "Matchup" and "Week X Recap" posts
  - Chalkboard "NE2K22 Transactions – Week X" (trades and FAAB bids)
  - Trade-deadline countdowns (13 days, 5 days, 24 hours, an 11:59PM alarm clock, an arcade "Trade Deadline Over")
  - Trade alerts, projected rankings, NE2K report cards (A+ to F, with remarks), "Trading rewards," FAAB minimum-price charts
  - Rivalry and face-swap memes, Simpsons-style group art, the NE2K23 draft-board wall
  - Championship hype art (the Megatron/Transformers "NE2K Championship" piece)
  - Charity posts every Jumu'ah
- **Trophy:** a silver football on a pillar with the NE2K plaque and a base of engraved plates ("The New Era est. 2010 Champion," plates for 2011–2018), plus a newer plate tower. AI scene photos show it in a jungle guarded by lions and monkeys.


**Trophy forms (from Big Blue's video, Nov 6)**

1. **Original New Era trophy:**
   - A silver football on silver pillars, with a rainbow and tie-dye painted base and the Philly "LOVE" sign on its side.
   - The gold-on-rainbow NE2K plaque in the middle.
   - Base plate: "Fantasy Football League CHAMPION – The New Era; est. 2010", with engraved year plates for 2010–2018.
2. **Current trophy, "The NE2K Kangaroo"** (after the Megatron takeover):
   - Repainted black with purple graffiti and a purple graffiti NE2K plaque, matching the @ne2kffl profile picture.
   - A Transformers decal on the side, and "THE NE2K KANGAROO" lettered on the base.
   - Hand-lettered season plates, such as NE2K21 TK, NE2K22 Damen Mustafa and NE2K Big Blue.
   - The older New Era plates were moved aside and credited as **New Era legacy tags** to make space.

**Seasonal themes:** Big Blue gives NE2K and New Era a new theme every year, and only the kangaroos stay the same. The app should build this in:
- each season has its own theme (colors, art, trophy look) that can be switched without rebuilding the app
- the kangaroo and Big Blue the mascot stay constant across seasons
- past seasons keep their themes in the Hall of Kangaroos
- Claude drafts each new theme from one image or idea Big Blue picks

**Design implication:** NE2K's current identity is purple on black graffiti. The red triangle kangaroo is an alternate logo, and the rainbow plaque is the retro badge. The Hall of Kangaroos should show the legacy tags (2010–2018) and the NE2K Kangaroo plates as two eras.

## 7. History (partial)
**New Era champions**

| Year | Champion |
| --- | --- |
| 2010 | Big Blue vs Dark Horse |
| 2011 | Big Blue |
| 2012 | Gucci |
| 2013 | Khader |
| 2014 | Pepi |
| 2015 | Khader |
| 2016 | Ablava |

**NE2K Kangaroos**

| Year | Champion |
| --- | --- |
| 2019 | Big Blue (Mohamed Yousef), from the plate (listed under NE2K plates) |
| 2020 | Khader Mustafa, team "Diggs!!!" |
| 2021 | Tarik Kanan (TK), team "Don Corleone" |
| 2022 | Damen Mustafa, team "Dame Time" |
| Probably 2023 | Ehmed |

**Missing:** 2017–2018 and 2024–2025, plus Ehmed's year. Ask Big Blue.

## 8. Features
**Phase 1 (2–3 weeks; the Purge drum is built first)**
- New Era home: league switcher, NE2K "Coming Back Soon" card, "est. 2010"
- Purge drum (details below)
- Tank Watch: the #1 rookie pick goes to the lowest season Max PF (`ppts`). Shows projected pick odds; reruns each Tuesday and after trades.
- Trade calculator, dynasty + IDP (section 9)
- Manager career profiles, record book, Hall of Kangaroos, schedule luck, report cards
- AI Commissioner and rulebook pages
- Commissioner hub
- Announcements: League and New Era Initiatives channels, both pushed
- Giving section with a daily verified verse or hadith
- Suggestion box: upvotes, a weekly AI digest to the Game Warden, and a status per idea

**Purge drum details**
- A live in-app event with a spooky countdown all week.
- It spins automatically at the set time, with no button press.
- The red ball means Purge. The result is recorded with a timestamp.
- The AI Commissioner hosts and takes questions.

**Phase 2**
- Yahoo leagues: Only Kangaroos first, with a chopping block, graveyard, and survival pool
- Poacher's Post (section 10)
- Draft-pick ledger
- Contingent trade log
- Start/sit with IDP and player news
- NFL news feed
- AI weekly recaps
- Push alerts, pick'em, shareable graphics, trade grades and a trade regret tracker, trash-talk board

**Phase 3**
- Live scores
- Video grid for live events, up to about 28 people (Daily's free tier of 10k participant minutes a month is enough)
- Rivalry pages, badges, waiver assistant, rookie draft hub, League Wrapped
- Instagram feed (needs business or creator accounts)
- NE2K return hub

**WhatsApp community mapped to the app**

| WhatsApp group | In the app |
| --- | --- |
| Announcements | League channel |
| New Era Initiatives | Initiatives channel |
| League chats | League pages and channels |
| Commissioners Corner | Commissioner hub |
| Poachers Post | In-app Poacher's Post |
| FAAB logs | Automatic log (low priority) |
| NFIF Contingent Trades | Contingent trade log |

WhatsApp itself can't be automated (its API has no group access), so the app replaces it gradually.

## 9. Trade value model
**Offense:** DynastyProcess values (free, GPL-3). They come from FantasyPros ECR, using `value = 10500·e^(−0.0235·rank)`.

**IDP:** value over replacement under NFIF scoring, mapped to the offense scale, plus FantasyPros dynasty IDP ECR, times a market factor of about 0.7–0.85.

**Picks:** DynastyProcess pick values, minus about 15% for each year out.

**Age:** never applied on top of market values. Instead, each trade shows two verdicts, "who wins now" and "who wins in 3 years."

| Position | Ages well until | Declines |
| --- | --- | --- |
| RB | About 28 | 29–31 |
| WR | About 31 | Steeply at 32–33 |
| QB | — | Rushing QBs decline earlier |
| LB | 32 | After 32 |
| EDGE | — | Around 33 |
| DB | 28 | After 28 |

**Verdict thresholds**

| Value gap | Verdict |
| --- | --- |
| 5% or less | Fair |
| Up to 15% | Slight edge |
| More than 15% | Lopsided |

**Not used:** KeepTradeCut. Its terms forbid scraping and reuse, and it has no IDP values.

## 10. Poacher's Post (rulebook 35b, updated 10/28/26)
- A poacher can steal a taxi-squad rookie by offering a same-round pick from one of the **next two drafts**. 3rd-round picks and free-agent pickups cost a 3rd.
- The defender has **24 hours from the moment the poach is sent**. There are no active hours. The defender either elevates the player or accepts the pick. If the clock runs out, the poach is processed automatically.
- If the defender makes a trade during the window, the trade is cancelled and the whole league is notified.
- Invalid offers cost the poacher $10 FAAB, then $50, then the pick itself. The app blocks invalid offers before they're sent.
- The app is the official record, so no screenshots are needed. Commissioners process completed poaches in Sleeper.

## 11. Open questions
- **Startup-draft rookies on taxi squads** (for example, Big Blue's J.J. McCarthy) cost only a 3rd to poach. Possible fix: value them by where they'd rank in a rookie draft. Bring this to the league when it comes up.
- **Domain:** which one was bought back? nofriendsinfantasy.com is at Namecheap but parked. nfifleague.com looks unregistered.
- **Purge draw time:** 11am ET on Nov 22, or something darker?
- **NE2K's return** and the update to rulebook section 15.

## 12. Setup and costs
- **Stack:** Next.js (App Router) on Vercel, Supabase (Postgres, auth, cron), and Web Push.
- **Data sources:** Sleeper API (no key); Yahoo Fantasy API (OAuth, key still needed); DynastyProcess CSVs; nflverse; ESPN news JSON plus CBS and Yahoo RSS.
- **Login:** magic link by email, then each member claims their team.
- **Costs**

| Setup | Monthly cost |
| --- | --- |
| Start | About $2–5 |
| With Vercel Pro (live scores, news every 15 minutes) | About $25 |

- **AI cost:** Sonnet for recaps and Haiku for news, about $1–5 a month with a spending cap.

## 13. Status
**Done**
- GitHub is linked, and Claude can push.
- The `new-era` branch exists.
- Vercel is connected.
- This project and the master plan doc exist.
- Rulebook updated: 11a (live Purge) and 35b (poaching).

**Big Blue to do**
- Point the domain's DNS at Vercel: an `A` record `@` → `76.76.21.21`, and a `CNAME` `www` → `cname.vercel-dns.com`.
- Find or create the Yahoo developer key. Put it in Vercel as `YAHOO_CLIENT_ID` and `YAHOO_CLIENT_SECRET`, never in chat.
- Send trophy and Purge-mask photos, Instagram handles, the missing champions, and the fundraiser links.
- Optional: set up a separate desktop user with Claude so Claude can browse Instagram with him.

**Purge page:** the first version is built (`static/purge/index.html` on `new-era`, with a private preview artifact). The result comes from drand quicknet round 31,071,780 (11:00:00am ET on Nov 22). Waiting on the ball odds and the DNS fix. Next: restyle it with the neon stitched-mask look from the Instagram.

**Claude next:** build the Purge drum on `new-era` and send a preview link, then the New Era home and Tank Watch.
