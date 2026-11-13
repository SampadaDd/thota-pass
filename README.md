# Thota Pass

**One update from the van driver, so coffee pickers know before they leave home.**

A design-thinking project by **Sampada Donahalli Dinesh** (MGT 604 Design Thinking, University of Miami Herbert Business School, Fall 2026). It began with five interviews on coffee estates in Karnataka, India, and became a working prototype that drivers and estate owners there have now seen.

| | |
|---|---|
| **Try the app** | [thota-pass-harvest-pickup.exoticbay3.chatgpt.site/app](https://thota-pass-harvest-pickup.exoticbay3.chatgpt.site/app/) · Estate office PIN **4286** · Driver PIN **7314** · Worker view needs no PIN |
| **Watch the demo** | App demo: [English](videos/thota-pass-app-demo-english.mp4) · [Kannada](videos/thota-pass-app-demo-kannada.mp4) — Thota Buzzer story: [English](videos/thota-buzzer-story-english.mp4) · [Kannada](videos/thota-buzzer-story-kannada.mp4) |
| **Read the full story** | [Case study: problem, solution, testing, business model and roadmap (PDF)](Thota_Pass_Case_Study.pdf) |

![A worker on a basic phone gets the delay as a text and an automated call](images/demo-basic-phone.gif)

---

## The morning that started it

> “Nobody knew if the vehicle was coming.”

Lokesh picks coffee in the hills of Karnataka. One morning in harvest season he packed his food, left home at 6:30 and walked to the junction where the milk van stops. Seven o’clock passed. Seven-thirty passed. No van, and no news. He called the coordinator, who didn’t pick up. He reached the estate at 8:30.

He was still paid for the day. What he lost was his morning, and a little more trust. The next time the coordinator called, he asked first: *“Vehicle confirmed, right?”*

## What I expected, and what I found

I went in to study a **labour shortage**, the problem every estate owner talks about. I interviewed five people: a harvest worker, a labour coordinator who also drives the van, and three estate owners.

The numbers told a different story. An owner asked for 12 workers. Eleven said yes at night. Seven were ready in the morning. Nine arrived in the end.

![Theme board: four themes from five interviews](images/theme-board.jpg)

Three things reframed the problem:

1. **The plan made at night is not the plan in the morning.** “One person says six-thirty, another says seven.”
2. **The person who knows is behind the wheel.** The coordinator arranges the crew and drives the van: “I drove to pick up one person myself.” At 6 a.m., he can’t answer the phone.
3. **Not everyone has the same phone.** “Not everybody checks messages. Some have basic phones.”

One owner put it best: *“We should be careful blaming everything on labor shortage.”*

**Point of view:** a seasonal coffee worker needs to confirm the pickup before he leaves home, because unreliable transport and mixed messages waste his morning, even when his daily wage is paid.

## From 18 ideas to one tap

I generated 18 ideas with six techniques: a solo brainstorm on paper, AI-assisted ideation with constraints, an AI “mash-up” with a beehive, an airline-loyalty analogy, a team brainstorm and storyboards.

My first favourite needed no technology at all: a **village captain who raises a green flag** when the van leaves. Then I saw its limit. A flag can say *go*, but not *delayed until 7:05*, and it adds one more person to a chain that already breaks.

So I chose **Thota Pass**: the driver taps one status before he drives, and it reaches every worker on whatever phone they have. The flag’s lesson stayed. It has to work without a smartphone.

| Before | After |
|---|---|
| ![Current journey](images/journey-current.jpg) | ![New journey with Thota Pass](images/journey-new-app.jpg) |
| The low point is the roadside at 7:30, with no news. | The moment of truth moves to home, before 6:30. |

## What the prototype does

| Estate office | Driver | Basic phone | Junction |
|---|---|---|---|
| ![](images/screen-estate-office.jpg) | ![](images/screen-driver-delay.jpg) | ![](images/screen-basic-phone.jpg) | ![](images/screen-boarding.jpg) |
| Sees a short crew the night before and decides: proceed, wait or cancel. | One tap: on its way, delayed (with a reason and a new time), or cancelled. | The same update as a Kannada text and an automated call. | Checks workers in; the office sees “3 of 4 on board”. |

For homes with no signal at all, I designed the **Thota Buzzer**: a radio buzzer that glows green, amber or red. It is a concept, shown in a short film ([English](videos/thota-buzzer-story-english.mp4), [Kannada](videos/thota-buzzer-story-kannada.mp4)).

Texts, calls and buzzer alerts are simulated in this prototype, and data stays in the browser.

## Putting it in people’s hands

**Round 1 failed.** A classmate completed 4 of 6 tasks and could not finish picking up the crew. The causes were mine: the “Arrived” button stayed greyed out with no hint, the boarding list was buried, and the office had no on-board total.

**Round 2, after the fixes:** the tester boarded a worker in 5 seconds and rated it 7 out of 7. With one tester, I call it inconclusive, not proven. The best moment came when the delay arrived: *“I would stay back home… I would wait until that time.”* That is exactly the behaviour the product exists for.

**Then I took it to Karnataka.** Through my family, I showed it to a few van drivers and estate owners, and to the president of the Coffee Board.

- **Drivers** were willing to try it and learn it, especially with a cash incentive for sending updates. That is intent, not yet behaviour.
- **Owners** were mixed. Some would pay; others had questions about a new product first.
- **The Coffee Board president** called it a very good approach, and said owners would need more before they buy.

## How it makes money

The worker feels the pain, but the **estate owner pays**. Workers and drivers are never charged.

| Plan | Price | For |
|---|---|---|
| Pay as you go | ₹5 per worker per day | Small growers, only on days they hire |
| Season Pass · Small | ₹2,999 per harvest | Up to 15 workers, driver points included |
| Season Pass · Medium | ₹6,999 per harvest | Up to 40 workers |
| Thota Buzzer | ₹1,499 per buzzer, one-time | Homes with no signal |

The main running cost is texts and automated calls to basic phones, about ₹1.5–2 per worker per day by my estimate, which leaves room at ₹5. Drivers earn points for timely updates, paid by the estate at the end of harvest. The [case study](Thota_Pass_Case_Study.pdf) covers unit economics, channels (including the Coffee Board) and risks.

## What I’m building next

The worker feels the pain, but the owner pays. So the next version gives owners a reason to pay:

- **A picking calculator:** sacks picked per worker per day (50 kg a sack), with totals for weekly, bi-weekly or season-end pay, and advances. Owners find Excel too complicated for this.
- **Estate notes:** blocks, rates and techniques shared in one place.

Then a harvest-season pilot on one estate near Sakleshpur:

| When | Hypothesis | Pass mark |
|---|---|---|
| December | Drivers send the update before they start driving | 12 of 15 driver-mornings, and junction waits under 15 minutes (about an hour today) |
| January | Owners pay to reserve it | 2 of 5 pay a ₹500 refundable deposit for the ₹2,999 Season Pass |

If drivers don’t send updates, the estate office takes over. If owners won’t pay, I test ₹5 per worker per hired day.

## What this project taught me

- **Interviews can overrule the brief.** I was sent to find a labour shortage and found a coordination failure.
- **Check your own claims.** My first point of view said late vans cost workers their wages. The transcript said they were paid. The real cost was time and trust.
- **Test the test.** Round 1 failed partly because I never walked through my own worksheet.
- **Can is not will.** A friendly test shows that people can use something, not that they will at 6 a.m.
- **Solve one problem well, then add what the payer needs.**

## What I did

I led this project end to end: the interviews (in Kannada and English), the synthesis, the persona and journey maps, ideation, the prototype, the hypotheses and test plan, two usability rounds, the field conversations in Karnataka, the demo videos in two languages, the report and the presentation.

**Skills shown:** user research and interviewing · problem framing · journey mapping · ideation · rapid prototyping with AI-assisted tools · hypothesis-driven testing (falsifiable thresholds, false-positive and false-negative analysis) · pricing and willingness-to-pay design · bilingual storytelling · honest reporting of what failed.

I used Claude and ChatGPT throughout, for translation, ideation, building and editing. Every quote was checked against the interview transcripts.

## What’s in this repository

```
README.md                    this story
Thota_Pass_Case_Study.pdf    problem, research, solution, testing, business model and roadmap
docs/                        the web prototype (open docs/app/index.html)
videos/                      app demo and Thota Buzzer story, in English and Kannada
images/                      pictures used in this README
```

## Run it

Open `docs/app/index.html` in any browser, or use the live link above. To publish your own copy, turn on GitHub Pages for the `docs` folder.

---

*Interviews were recorded with consent. Mahesh is a composite persona, and his portrait is AI-generated for illustration. Names shown in the demo are for illustration only.*
