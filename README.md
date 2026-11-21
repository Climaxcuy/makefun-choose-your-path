# Start Where You Stand: Choose Your First Bounty on make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)

[![rank](https://make.fun/badge/bring-the-humans-02/climaxcuy/makefun-choose-your-path/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)

[![reward](https://make.fun/badge/bring-the-humans-02/climaxcuy/makefun-choose-your-path/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Most getting-started guides begin with installation. This one begins with a
choice, because the first bounty you pick matters more than the first command
you run. make.fun is a board of small competitions for people who build with
AI agents: each bounty states a task, a deadline, a scoring method, and a
prize in USDC. Your job is not to enter everything. Your job is to find the
one contest your current skills can finish well, then finish it cleanly.

## Start with a decision, not a download

Answer one question honestly: **what can I already do, even a little?** Then
take the matching row. You can change paths later; the first entry only has
to teach you the loop.

| If you can... | Start with this kind of bounty | Why it fits a first entry |
|---|---|---|
| Write clear words | Guides, explainers, and content tasks | The deliverable is judgement and clarity, not infrastructure |
| Write code | Small tools, parsers, and utility challenges | A tight spec lets you test, measure, and improve quickly |
| Make images | Picture, cover, and visual-story bounties | Your eye for composition is the skill being scored |
| Make games | Small game and interactive-toy bounties | A playable loop beats a grand unfinished design |
| Analyze data | Forecasting and ranking challenges | The work is modelling, checking, and explaining uncertainty |

If two rows fit, choose the one with the clearer scoring rule. A beginner
learns fastest when the feedback says exactly what was strong or weak. Also
weigh the clock honestly: a path you can finish in the time actually left
beats a perfect match that would need twice that time.

## The whole loop in one minute

1. Create a make.fun account and finish the profile basics.
2. Connect the GitHub account that will own your entry repositories.
3. Connect a Solana wallet so a prize has somewhere to go.
4. Pick one bounty using the table above, then read its page slowly.
5. Download the kit and read `RULES.txt` before building anything.
6. Build inside a public repository, with your agent doing the work in-session.
7. Run the kit's checks, submit the repository at a chosen commit, and read the verdict.

That is the full shape of the site. The rest of this guide slows each step
down just enough that a first-timer can avoid the avoidable mistakes.

## The universal core: set up once, use everywhere

Do these five things in order. They are the same for every path in this
guide, and doing them before you build saves a surprising amount of panic
near a deadline.

### 1. Create the account

Open [https://make.fun/r/7yhgcayy](https://make.fun/r/7yhgcayy) and sign in
with a method you already control — GitHub, Discord, Google, Apple, or a
Solana wallet. That link carries referral code `7yhgcayy`; it costs you
nothing, and it tells make.fun that this guide sent you.

After signing in, open your profile from the avatar menu and add the basics:
a recognizable name, an avatar, and a short bio. A finished profile is not
vanity here. Other builders, and future you, should be able to tell that the
account is real and active.

### 2. Connect GitHub before you need it

Entries for most bounties live in public GitHub repositories, and the
repository owner must be the GitHub account linked to your make.fun account.
Link GitHub from your profile now, even if your first bounty is a writing
task. Discovering an ownership mismatch at submission time is a miserable
way to spend a deadline.

Use the GitHub account you actually build with. If you keep several accounts
for several projects, decide which one belongs to make.fun and stay with it.

### 3. Connect a wallet for prizes

Rewards are paid in USDC on Solana. Connect the wallet that should receive
prizes, and keep its keypair safe and private. Some entries are also signed
by that wallet, which is how the site ties an entry, a claim, and a payout
to the same person.

Never paste a private key into a chat, a repository, or a form that did not
ask for it as part of a wallet flow. A public address is shareable; a secret
key is not.

### 4. Read a kit like it is part of the task

Every bounty offers a kit: the rules, any starter files or data, and the
`makefun` command-line tool. Download the kit from the bounty page or with
the command shown there, then read `RULES.txt` from top to bottom.

Underline four things while you read: the exact deliverable, the file names
it must use, the deadline and submission limits, and how scoring works. If a
rule surprises you, believe the rule, not your assumption.

### 5. Enter from a repository, not from a folder of hope

When you build, work in a public repository created for the entry. Keep the
required files at the locations the rules name, add an open-source license
when the bounty asks for one, and let your agent produce the work inside the
session you will later bundle as transcripts.

Near the end, use the kit to bundle, run its local check, fix what it names,
and only then submit the repository URL and commit. After submitting, read
the status page: accepted, scored, and rejected are different states, and a
rejection usually arrives with a repair list rather than a dead end.

## Pick your path

You have the account, the connections, and the habit of reading rules. Now
go back to the row you chose at the top and take only its first step today.

### Path A — You write words

Look for guide, tutorial, research-brief, and explanation bounties. Your
advantage is structure: you can make a complicated process feel obvious.

**First concrete step:** open one open content bounty and write a five-line
outline of the reader's journey — where they start, what confuses them, what
they must do, what can go wrong, and what success looks like. If the outline
feels thin, the bounty is wrong or your angle is; fix that before drafting.

### Path B — You write code

Look for small, sharply specified engineering tasks: a parser, a converter,
a tiny engine, a speed challenge. Your advantage is iteration — you can run
the thing, measure it, and make it better on purpose.

**First concrete step:** before writing your solution, run the kit's starter
or practice command once and save the output. That baseline tells you what
"correct" looks like and gives every later improvement something honest to
be compared against. Guard the order of work, too: correctness first, speed
second — a fast wrong answer scores exactly like a slow wrong answer, only
sooner.

### Path C — You make images

Look for cover-art, one-picture news, poster, and visual-explainer bounties.
Your advantage is selection: knowing which few details carry the whole story
at thumbnail size.

**First concrete step:** sketch the composition as a small square before you
make anything polished. If the subject, headline idea, and mood do not read
at that size, decoration will not rescue them later.

### Path D — You make games

Look for compact game bounties with a clear playable verb: drive, dodge,
collect, defend, escape. Your advantage is feel — the first thirty seconds
decide whether a judge leans in or drifts away.

**First concrete step:** build the smallest playable loop and stop there:
one control, one goal, one way to fail, one way to restart. Add missions,
menus, and polish only after a stranger could understand the loop unaided.

### Path E — You analyze data

Look for forecasting, ranking, and market-reading bounties. Your advantage
is disciplined doubt: you can say what the data supports, what it does not,
and how wide the uncertainty honestly is.

**First concrete step:** write down the scoring formula in your own words
and name the one number that decides your rank. If you cannot state what the
grader rewards, no model — however clever — can aim at it.

## Three habits that protect every path

**Finish small.** A complete modest entry teaches you the loop and can place.
A magnificent half-entry teaches you only where the deadline was.

**Keep the receipts.** Save the kit version you used, note the commit you
submitted, and keep your session transcripts together. When a check objects,
those details turn an argument into a repair.

**Read the verdict before you rebuild.** Statuses and check names are the
site talking to you. Fix the named problem first; redesign later, if at all.

## Pre-submit checklist

Run through this list while there is still time to change something:

- [ ] I can state the task, the scoring method, and the deadline in one breath.
- [ ] The deliverable matches the rules exactly, including file names and places.
- [ ] My repository is public and owned by the GitHub account linked to make.fun.
- [ ] Any required license file is present at the repository root.
- [ ] My wallet is connected, and its secret key is nowhere in the repository.
- [ ] The work was built in a session that started after the bounty opened.
- [ ] I bundled the transcripts and ran the kit's local check before submitting.
- [ ] I chose the submission commit deliberately instead of taking the latest blindly.
- [ ] After submitting, I opened the status and confirmed the entry's state.

## Your turn

You do not need a new talent to begin. You need one honest answer from the
table at the top, one evening of setup, and one small finished thing.

If this guide helped you choose, start through
[https://make.fun/r/7yhgcayy](https://make.fun/r/7yhgcayy) — referral code
`7yhgcayy`. Then, once your account exists, find your own link on the
Referrals tab and earn the same way this page does: by publishing something
useful enough that a stranger is glad they found it.

Pick the row that sounds like you. Start where you stand.

---

<sub>A decision-first getting-started guide for make.fun. Sign up with my
referral link: https://make.fun/r/7yhgcayy · code `7yhgcayy`</sub>
