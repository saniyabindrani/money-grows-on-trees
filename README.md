# Money Grows on Trees

A 4-minute farm game for people who have never invested. You earn money, watch inflation eat it, then learn to put it to work.

**[Play it here](https://saniyabindrani.github.io/money-grows-on-trees/)**

---

## Why a game

Marketing Brew wrote about brands borrowing ideas from video games for their campaigns. One example was Coinbase, which made an Academy Awards ad about a video game character who realises he's stuck in the machine and breaks out.

I wanted to see what that looks like for onboarding. Investing apps in the region do a good job explaining their products. I think there's room for more fun, especially for people who find investing intimidating.

The format is inspired by Township, the farming game you've probably seen in mobile ads: plant, harvest, upgrade, come back tomorrow. Those games are built around habits, and habits are what an investing app needs.

Clearly, I'm not a gamer. The only games I play are board games. Did the launch of a certain very popular video game have anything to do with this? I couldn't possibly say. I built it as a product marketing experiment for growth.

## The growth problem

I picked one persona and one problem.

**The persona:** Someone new to investing. Their money sits in gold, a traditional savings account, or a current account. They've heard investing is risky and assume it's for other people.

**The problem:** Getting this person from curious to funded. Using the framework from Product Marketing Alliance, the barriers are:

- **Low trust at the start.** New investors worry about losing money and don't know the app.
- **High education burden.** Terms like diversification and compounding mean nothing yet.
- **Behaviour change required.** Moving money out of savings or gold is a big shift.

Under those sit the emotional barriers: confusion, fear, inertia and a lack of confidence.

## The behaviours I want to increase

1. **The first deposit.** The first meaningful action after sign-up.
2. **The first auto-invest.** The habit most likely to keep someone investing long term.
3. **Coming back.** Replaying the game, so the ideas stick.

## How the game works

Three short levels. Each teaches one idea and gets a little harder.

| Level | What you do | What it teaches | Habit you practise |
|---|---|---|---|
| 1. Grow | Chop wood, sell it, watch idle cash shrink, plant in your first farm | Cash sitting still loses value to inflation | Making a first deposit. Your account opens and your bank links automatically along the way |
| 2. Spread out | Two more farms open: wheat (steady, like bonds), corn (compounding, like index funds) and berries (high growth, like growth stocks). A storm hits one crop | One bad event only hits part of your money when it's spread out | Spreading money across low, medium and high risk |
| 3. Autopilot | Pick a share of every paycheck to auto-deposit. Drones invest it and replant harvests. A cow gets sick and needs a vet | Automation compounds your money. Savings cover surprise bills so you don't have to sell investments | Setting up an auto-deposit and building an emergency fund |

Each level has a goal. Hit it and the level ends early with a "Level cleared!" card. Run out of time and you still move on, with a "so close" and your number.

## The mechanics, and why each one is there

| Mechanic | Barrier it addresses | Behaviour it builds |
|---|---|---|
| Inflation cloud that vacuums up idle cash | Inertia | Investing instead of holding cash |
| Account opening shown as a 3-second animation | Low trust, fear of paperwork | Feeling that sign-up is easy |
| Farm cards with risk bars and example growth rates | Education burden, confusion | Understanding risk before choosing |
| One storm per game, with a damage report showing the hit as a share of total money | Fear of losing everything | Diversifying |
| Sick cow and Emergency Fund | Fear of surprises | Keeping savings separate from investments |
| Auto-deposit picker and drones | Lack of confidence, effort | Setting up auto-invest |
| Level goals, personal best, a hard AED 10,000 finish | Low engagement | Replaying |

## Building the message around achievement

The end screen leads with what the player gained:

- How their money grew: paychecks earned, growth from their farms, then what inflation, the storm and surprise bills took
- What kind of investor they played as, with one honest line about that style
- What a monthly auto-deposit could look like over 10 years, at an illustrative 5% a year compounded monthly, next to the same money left as cash
- Their rewards: a first-deposit match for everyone, valid for 7 days, plus a starter bonus at AED 5,000 or AED 10,000
- A shareable scorecard

To claim rewards, the player gives their email and answers one question: **"What's stopping you from investing?"** Each answer points to a different follow-up email, so lifecycle messaging is segmented from the first touch.

## Guardrails

Following the same framework, the game tries to stay:

- **Tied to real outcomes.** Every mechanic maps to a real habit.
- **Behaviour-based.** Rewards come from finishing levels and good habits. Going all-in on the riskiest farm doesn't pay off. In my test runs, an all-berries farm finished behind a spread-out one because the storm hit it harder.
- **Trust-building.** Losses always come with the reason and the fix.
- **Compliant and transparent.** Rates and projections are labelled as examples. The timer belongs to the game and never to the bonus.
- **Educational as much as motivational.** One lesson per level, in plain words.

## How I'd measure it

The bonus code and claim email link a player to their app account, which makes these measurable:

- **Activation rate:** Players who open an account with the code
- **Time to first deposit:** From claiming rewards to funding, inside the 7-day match window
- **Auto-invest setup rate:** Among players who fund
- **Engagement:** Levels reached, replays per player, scorecard shares
- **Reward claim rate**, and which barrier answer converts best

## What this doesn't solve (yet)

The game gets someone to make a first deposit and automate it. It doesn't answer the next question a new investor has: what do I actually put my money in?

That's the next onboarding problem, and the game sets it up in two ways. The end screen shows each player's style as a low, medium and high risk mix. The claim form flags everyone who answers "I don't know where to start". In the app, that answer could lead into a short risk quiz and a ready-made starter portfolio, so the first deposit lands somewhere the person understands.

## Notes

- This is a concept. "Your Investing App" is a placeholder brand. The bonus, deposit match and returns are made up for the game.
- Your best score is saved in your own browser. Nothing is sent anywhere, and the email form shows the flow only.
- Not financial advice.
- This is my first time building a game. Feedback is very welcome, on the game or the growth thinking.

## Built with

One HTML file, [Three.js](https://threejs.org/) for the 3D world, and Claude as my build partner.
