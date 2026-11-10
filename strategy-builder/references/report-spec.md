# Report Spec: the strategy drafts

**What the person gets:** **two or three named strategies**, each a complete strategy document on its own tab of one shareable HTML file, after a short overview. The first is the **Hold**, the strategy if the product stays roughly where it is. The others are **Moves**, each taking the product into an underserved gap nearby. A **More directions** tab holds the other gaps worth a look. They read them, push back, pick favourite parts from each, and the strategies get revised round after round.

**What they don't get:** a comparison report, scorecards, a list of rejects, or a pile of research.

**These are starting points, not answers.** Version 1 is never "done". People will pick and choose, argue with it and develop it further. It's the start of a conversation that ends with one strategy, dialled in.


## Every strategy has a name that says what it is

- **Name it in plain words for what it is:** 3–6 words that tell a stranger, from the name alone, who it's for and what changes. Examples: "Designer Furniture for Every Budget", "Flights Cheaper Than the Bus", "Luxury Electric Cars First".
- **No metaphors, invented words or single evocative nouns.** "The Open Kitchen Strategy" or "The North Star Strategy" sound like strategy and say nothing.
- It names the bet, never a feature, and never a tagline.
- **Names stay stable across revisions** so feedback can refer to them ("take the taglines from Flights Cheaper Than the Bus"). Only rename one if the idea itself changes, and if you do, note the old name.
- **When strategies are combined,** the new one gets its own plain name, plus a line saying what it came from.

## Build it from the template

Start from `assets/report-template.html` in the skill folder and replace every `{{PLACEHOLDER}}`.
- **One self-contained, shareable HTML file.** No external fonts, scripts or images; diagrams are inline SVG. Anyone can open it, read it and pass it on. 
- **Tabs, not one long scroll.** An **Overview** tab, then **one tab per strategy** (the Hold, then the Moves), then **More directions**, then a **Market & sources** tab. Each strategy tab reads as its own complete document, so the reader can focus on one strategy at a time. With no script, or when printed, every tab shows in order.
- **Light mode only.** Don't add a dark scheme.
- **Each strategy gets its own accent colour**, used on its tab button, its overview card and its whole tab.
- Search the finished file for `{{` before delivering, and delete any block that has nothing real in it.
- Write in plain English throughout. No book jargon. If a term is unavoidable, explain it in a few words.

## The file, tab by tab

### Tab 1: Overview
The general picture every strategy shares. Short, scannable.
- **Cover:** the product's name; "Strategy drafts", the version (v1, v2…) and the date; one sentence on what the product is; one line on how to read the file.
- **The line-up:** one card per strategy with its name, its label ("Hold · stay where you are" or "Move · into ___"), its one-line idea and its picked tagline. The Hold comes first. Each card opens that strategy's tab.
- **Leaning** (optional, one line) and, from v2 onward, **What changed**: the person's feedback quoted, then what changed in each strategy by name.
- **The business today:** six fact cards: what it is, who uses it now, where it stands (what's live and what isn't), the goal (kept separate from the strategy), what it already leans toward, and what it won't do.
- **In your words:** 3–5 things the person said in the interview, quoted exactly, each with one line on why it matters.
- **Where you stand:** one line on where the product sits in the market today, two or three sentences on the open ground nearby, and the **positioning map** (inline SVG): the competitors, the product today as a dashed circle, the Hold beside it, and an arrow from today to each Move in that strategy's colour.
- **The market in one look:** one headline truth about the market and two or three sentences, pointing to the Market tab.
- **How the market picks** (only for products that haven't launched): one cheap test that runs every strategy against the same kind of buyer at the same time, such as one landing page or deposit offer per strategy. It gives a pass mark for each and a date to decide by. The report leans; the test decides.
- **What they have in common:** the ground every strategy shares, so the strategy tabs only have to cover what's different.

### Tabs 2–4: one complete document per strategy (the Hold first, then the Moves)
Each strategy tab opens with a hero (the plain name, the bet in one clunky sentence, its Hold or Move label, the picked tagline and subline, and a "Revised in vN" note when it changed). A contents list sits down the side. Then fifteen parts, always in this order:

1. **The strategy.** **The bet** comes first: one clunky, explicit sentence of about 30 words at most, saying what the business will be and for whom, with no feature names (Strategy Builder, Stage 4, Pass 2). It must pass the stranger test. Then four cards, carried over unchanged from the core that cleared power judging:
   - **What everyone assumes:** the belief the category takes for granted, with evidence.
   - **What we see instead:** why it falls short, shown by a pain buyers already act on.
   - **The true competitor:** what the buyer would otherwise do.
   - **What we give up:** the sacrifice a sensible competitor wouldn't make.

   Then two cards: **Stands for** (the one thing, in a word or two) and **The enemy** (the assumption at work: the status quo, habit or belief the buyer is fighting, never a named competitor). Then the **20-second pitch**: what it is, the problem it solves, why it's different, one sentence each.
2. **From here to there.** Today and where this strategy takes it, side by side. **The gap:** who is underserved there and the evidence (their words, their workarounds, who left it open and why). **Keep / build or change / stop or give up.** **How far** (small, medium or large, with a rough size in time and people, and what's risky), **the first cheap test** of the gap before building, and **commit when** (the signal that says go). **Enough of them:** the size math, reachable buyers times the price stance from part 9, against the goal. It uses the same price model as part 9, and every ratio is sourced or labelled a guess. For the Hold this part is short: what to double down on and what to stop. For a Move it is the heart of the tab.
3. **The buyer.** Who decides to buy, described by how they work and what they value, never by a feature. The real moment they feel it. Their own words, quoted with a source. **Who it's not for**, and what the strategy gives up.
4. **The argument.** The big idea as a short argument: how things are today (the enemy at work), why that falls short, and what this strategy does differently. Then **the story we tell**: the buyer as the hero against the enemy, in 4–6 sentences a customer would recognise. Then **the objections**: the 2–4 a skeptical buyer or boss would raise, each answered.
5. **How it's different.** What's unique, in plain words (never "the only ___"). One card per main alternative: what they own (in their words), where this strategy sits, and what they'd have to give up to follow. Then the **logo-swap check**: put a competitor's name on the pitch and say why it breaks.
6. **Taglines.** Follow [Taglines](taglines.md): the **three** best lines from the separate tagline judge, each labelled with its type and a note on what it says read cold. The pick goes on top with its descriptive subline and why it was chosen. If no line scored 8, label them "working lines, none strong yet".
7. **How to talk about it.** The **one promise**, then exactly **three proofs**, each with specific evidence (a real customer story, a visible part of the product, a number that can't be picked apart) and an example line showing how to say it. No credentials or awards as proof. Then **words we use / words we avoid** (the buyer's own words versus category clichés, insider terms, and anything that could sound lazy or like surveillance). Then **the voice**: 3 traits, each with what it sounds like and what it isn't.
8. **Marketing.** The **homepage's first screen** (headline, subline, call to action) and what the next sections show. **2–3 campaign ideas**, each with what people see and an "if this, then that" line: the promise, exaggerated into a consequence the buyer recognises. **The two best channels**: for each, why this buyer is there at the moment they feel the pain, what to put there first, and whether its cost fits the price. This is a sketch; the full channel plan belongs to the go-to-market skill.
9. **Brand.** Look and feel: the category cues to keep, and the tone and voice to borrow from named brands in other categories. **Price stance:** what you charge for (per person, per company, size bands), a rough level against what the buyer pays today (the price map), the signal it sends, and discount rules. Part 2's sizing uses this same model. It's an assumption until the go-to-market work tests it. Names and words for features, plans or the category, if the strategy changes them.
10. **Product.** 2–4 visible moves for the first 6–12 months, biggest first, each labelled live, partly live or missing today. Then **ship / wait / cut**, mapped to the real product's state. Then **the first ten minutes**: what a new customer sees and does first under this strategy.
11. **Across the business.** **The flood:** 6–10 ideas beyond the product that the strategy sparks: pricing, sales, onboarding, support, hiring, rituals, community, partnerships, founder marketing. If this part is thin, the strategy is too small.
12. **First 90 days.** What happens at 30, 60 and 90 days.
13. **Risks and checks.** 2–4 things that have to be true, each with the cheapest way to check it (and whether buyers must know the brand before they'll choose it). 2–3 risks, each with what to do if it happens.
14. **Why it matters.** The motivating reason (the purpose line, the founder's why), kept separate from the strategy and never used as a message.
15. **How it holds up.** Two lines saying what's unique in plain words and against whom, and the reasons that matter. Then a collapsed list of **all 15 checks, each with a one-line reason**. That way the reader can see every check was met, without a scorecard comparing strategies.

**Depth:** each strategy tab is a real document, about **2,500–4,000 words**. Every part gives direction someone could act on: what to say, what to build, what to do first. A part with nothing concrete in it is a failure, not a placeholder.

### More directions
The other gaps and angles the research turned up that didn't become full strategies: **4–8 cards**, each with the kind of gap (new buyer, neglected job, incumbent retreating, new shift, nearby category), the gap in a phrase, the idea in one plain sentence, the **evidence** with a source, what **carries over** from the product, what it **would take**, the **open question** that stops it being a full strategy yet, its **score** out of 25 from the gap scoring (main note, Pass 3) and the **one reason it isn't a Move**. One opening paragraph says these are starting points, not graded strategies, and which one is worth developing next. That can't be a card that outscored a Move; if it did, it should have been the Move. Never include a Taste-log rejection, a feature dressed up as a strategy, or ground a competitor already owns.

### Last tab: Market & sources
- **Reading the market:** two or three paragraphs covering the category, what everyone competes on, how much buyers care and what's changing.
- **The positioning map** lives on the Overview ("Where you stand"). Repeat it here only if the market reading needs a second map.
- **In their own words:** each main alternative's homepage headline quoted, with one line on whether you could swap the logos.
- **What buyers say:** verbatim buyer quotes with links.
- **Sources:** numbered links with the date checked, plus the notes read.

There are **no** comparison tables between strategies, no scorecards for the strategies and no rejected lists anywhere in the file. The only scores shown are the gap scores on More directions cards. Rejected ideas go in the session record. More directions is not a rejected list: it holds open ground worth exploring, never ideas that failed for being bullshit.

## Recommending

The skill may say which strategy it leans towards, in **one line** on the cover ("Leaning: Flights Cheaper Than the Bus, because…"). The person chooses, and often picks parts from each.

## The revision rounds

- Every round is a new version (`v2`, `v3`…) of the same file.
- Feedback arrives in conversation, usually by strategy name and part ("the marketing on Flights Cheaper Than the Bus is thin").
- Each strategy page that changed gets a small **"Revised in vN"** note listing what changed and why, quoting the feedback.
- **Mixing:** when the person asks to combine parts ("the taglines from X, the first moves from Y"), build the combined strategy as a new named page, grade it like any other, and keep the originals until they're dropped.
- **Narrowing:** when the person drops a strategy, remove its page. Keep one line about it in the session record, not in the file.
- **When one strategy is chosen and dialled in,** move to the full strategy document (main note, phase 2).

## Quality bar

- **Strategy, not positioning.** Every strategy's core scored 8 or more out of 10 for power from two independent judges (Grader, Gate 1), and the finished tab still does. If none reached 8 after three loops, the report still has a working Hold for the main buyer and the best Move, each labelled with its real score. A strategy below the bar is never presented as if it cleared it.
- **One Hold and one or two Moves, each passing all 15 tests.** Never ship a single strategy, and never ship one with warnings. If every idea collapses into the Hold, the search stayed too close to today's product: hunt for gaps again.
- **Moves really move.** Each differs from the Hold on at least two of the buyer, the job and the category, and couldn't ship as a feature of the Hold.
- **One set of numbers.** One price stance per strategy, used in the sizing, Brand and Across the business alike.
- **It opens up the market, not just the product.** Someone reading it should see where the product stands, the open ground around it, and at least one direction they hadn't considered.
- **Strategies from different directions.** Each starts from a different source, and any two differ on at least two of the buyer, the enemy and what it gives up. If two collapse into the same idea, merge them and find another.
- **Every headline passes the stranger test**: the name, the bet and the tagline pick. The name alone says who it's for and what changes.
- **Logo-swap test:** put a main competitor's name on the statement, the pitch and the pick. If it still works, it isn't this strategy yet.
- **No sentence that fits any company.** No insider words: no feature names, framework names or book terms.
- **Rich and directive:** each strategy tab is about 2,500–4,000 words and reads as a complete strategy someone could act on. It should look designed, with cards and visuals rather than walls of text.
