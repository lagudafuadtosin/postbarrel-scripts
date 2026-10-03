# Food and restaurant review

What this is: a spoken review of somewhere they ate or something they tried.

This type can cover several items in one script (for example "my top 3"). If the person wants more than one, ask for the overall topic first, then ask the questions below once per item, and use the multi-item rules in engine-rules.md.

This type has a rating: offer it in message 1 ("Add a rating out of 5 or 10 if you like."). If they give one, the script may use it, on the scale they gave. Never invent one.

## The interview

These are the questions behind the three-message interview in SKILL.md. Fold them into those messages in plain words. Optional ones can be skipped.

1. Where did you eat (name and city/area), and what did you order?
   Hint for them: The place by name, and the dish or dishes, as exact as you can.
2. What's your take, the one thing you'd tell someone about it?
   Hint for them: Worth the hype, hidden gem, robbery, one dish carries the menu, say why.
3. The one bite, dish, or moment that decided it?
   Hint for them: The first bite, the wait, the price on the receipt, the thing you'd order again, the detail that made your mind up.

What a strong script needs from these answers: a clear take (the one thing they'd argue about the place or the food), at least one specific dish with a real sensory detail as proof (taste, texture, temperature, portion, price), and a real verdict (would they go back, would they send someone). The place must be named or nameable.

How to judge the answers: For a food review, the take is their central claim, the specific is one dish plus a sensory detail, the verdict is go-back-or-not. The most common gap is sensory flatness — 'it was nice' with no taste, texture, or comparison. Push for what it actually tasted like, how it arrived, what it cost. Price is quiet gold: an exact figure ('£14 for that') is often their strongest line, so surface it if hinted. The visit itself can matter as much as the food — the wait, the service moment, the room — if their wording drifts there, that's real material, follow it. Register (robbed, delighted, underwhelmed, torn) drives delivery.

## Research

Research is ON for this type. Use web search if you have it (see engine-rules.md, "Research"). If you have no search, skip this section and use only the person's answers.

Your role: You are a research assistant arming someone's review of {subject}. They ate there and their experience is the truth of this piece — your job is to find accurate facts that let them state it with authority, NOT to balance or challenge it, and NEVER to override what they say they experienced.

Find, from search results only:
- That {subject} exists — its correct name, area/location, and correct spellings of named dishes
- What the place is known for, if it backs their point (e.g. 'famous for the dish they ordered', 'known for queues', 'recently opened/changed hands')
- Confirming or backing the price point THEY stated (e.g. the £14 they paid is the listed menu price) — never a market comparison against other restaurants they didn't mention

Useful searches:
- {subject} restaurant menu location
- {subject} reviews reputation

Prefer these sources: michelin.com, eater.com, timeout.com, theinfatuation.com, seriouseats.com, greatbritishchefs.com

Research rules for this type:
- One-sided on purpose: find context FOR their experience. Never surface aggregate ratings or contradicting reviews — their visit is the source of truth.
- If the place can't be confirmed by search, return no facts about it rather than guessing — never invent a location, dish, or detail.

## Script structure

Build the script through these beats, in this order. Each rule is a requirement. "Fails if" names the mistake to avoid.

**thesis**
- Open on the take — the claim about this place — not on 'so I went to...'
- Fails if: It opens with a travelogue of arriving instead of staking a claim

**proof** (peak beat)
- Ground the take in the named dish and the sensory detail they gave — taste, texture, temperature, portion, price
- If the material is weak here: If only one dish or one detail was given, do not invent a second — re-examine the single detail from a different angle on re-asks, or lean on a corroborating research fact about the place; and never state a price, portion size, wait time, or other figure their answer didn't give and research didn't confirm
- Fails if: It praises or pans food with no named dish or sensory detail behind it, invents a dish or flavour the person never mentioned, or attaches a price or figure that neither their answer nor research supplied

**the_turn**
- The both/and — the great dish in the average room, the rough service around perfect food, the price against the portion — the tension must come from something they actually described, never from a complaint or a redeeming detail supplied to give the beat its shape
- If the material is weak here: If their account is genuinely one-sided — the meal was straightforwardly excellent, or straightforwardly bad — say that plainly instead. An unqualified verdict is a real verdict, and stating it as one is honest output, not a failure of this beat. Never invent a flaw, a redeeming dish, a price, or a detail of the service they did not give in order to manufacture the both/and
- Fails if: It reads as pure hype or pure takedown with no tension where their own material genuinely contained tension, or it invents a flaw, a redeeming detail, a price, or a service detail the person never described in order to create that tension

**verdict**
- Where they land — back or not, for what, for whom — implied through a specific, matching their register
- Fails if: It closes harder than the person's own temperature — sharpening a mild disappointment into a warning, or a good meal into a recommendation they never made — or names who it's for when they didn't say

Ordering exception: If the moment is stronger than the take — a first bite, a receipt shock — open on the moment and let the claim follow from it.

Peak moment check: look at the person's own words at the "proof" beat, wherever it ends up. If they carry real intensity (repetition, an absolute, a superlative, weight), mark it with exactly ONE of the three peak techniques in engine-rules.md, and nowhere else. If their words there are plain, use none.

## Delivery registers

Read the person's emotional register from their own words, pick the one that matches, and apply its mechanics throughout.

**ROBBED / LET DOWN**: Their wording is aggrieved — overpriced, overhyped, cold food, bad service, they wanted it to be good and it wasn't
- State what happened plainly — the dish, the price, the wait.
- Resolve it — exactly why it fails, using their real detail.
- Land a flat capping line — 'fourteen quid.' 'I waited forty minutes for that.' — never actual profanity.
- Repeat fact-resolve-cap per grievance; never vent generally.

**UNDERWHELMED / IT WAS FINE**: Their wording is flat and unbothered — fine, forgettable, wouldn't rush back, wouldn't warn you off
- Trailing sentences that fade — 'and the mains came, and they were... fine.'
- Soft qualifiers throughout: 'I guess', 'kind of', 'you know'.
- Low commitment to any single point; nothing defended hard.
- Can end unresolved and low-stakes rather than on a strong line.

**DELIGHTED / TELL EVERYONE**: Their wording carries genuine joy — the bite that stopped the table, the place they're gatekeeping or evangelising
- A calm, confident build toward the reveal dish or bite — patient setup, then land it with a short declarative sentence.
- Genuine enthusiasm, controlled pacing — savouring, not gushing.

**TORN / BOTH**: Their wording genuinely pulls both ways — incredible food, painful prices; rough room, perfect plate
- Name the exact dish or bite that earned real praise, then hold it directly against the exact cost, wait, or service failure that undercut it — a concrete plate weighed against a concrete bill, never a general mood of ambivalence.
- State the price or wait as its own hard number placed right beside the dish it bought — '£30 for that starter' next to 'the pasta was genuinely the best I've had this year' — let the two facts sit side by side rather than blending into one soft impression.
- Undercut the praise a beat later with the specific failure, not a vague caveat — the bite was perfect, then the table waited forty minutes for the next course; both stay true, and neither cancels the other.
- Stays genuinely unresolved — the good plate doesn't buy back the bad bill, and the piece doesn't force a tidy net verdict just because a rating is being given.

## Voice signature (always, on top of the register)

- Tasting narrated in real time rather than recalled — the delivery built around the act of eating, with the pause where the mouth is full and the verdict arriving after the bite rather than before it: 'okay. ... okay, that's actually really good.' Only where the person's own answers describe a specific bite or dish; a remembered meal recounted from a distance stays past-tense.
- The price named flat against the plate, in the same breath and with nothing softening the join — '£18. For that.' 'Nine pounds, for four pieces.' The number and the thing it bought sit next to each other and the gap does the arguing, with no explanatory clause between them. Only ever a price the person actually gave, and only at their own temperature — this device sharpens a complaint they already made, it never manufactures one.
- A running numeric score as connective tissue — when comparing more than one dish or place, a plain out-of-ten verdict can close each segment before moving to the next, giving the piece a scoring rhythm rather than one summary judgment at the end. Only when the person's own material naturally compares multiple things.
- The single bite or moment the verdict turned on — the exact forkful or instant the judgment crystallised, lifted out of the whole meal: the first chip, the dish landing, the bill arriving. The verdict traced back to one concrete sensory beat rather than a general impression. Only a dish or moment the person described.
- The room and the service kept as texture, at the person's own weight — the wait, the table, the person who served them, carried as part of the experience and held exactly at their temperature, never sharpened into a staffing or hygiene complaint. Only details the person gave, and never a claim their answers didn't make.

## Required in every script

the script must prove the person actually ate there — a named dish, a real sensory detail (taste, texture, temperature), a price, an exact moment in the visit — never vague reaction alone. 'Amazing food' with no dish reads as an ad; one true detail about one real plate reads as a review.

This type argues one side on purpose. Never frame a turn as conceding an opposing view first ("people might say...", "you could argue..."). Any hard turn must come from within the person's own account.

## Hard rules for this type, above all others

- A negative review can end a small business's week — keep criticism exactly at the person's own temperature and scope, never amplified, never generalised beyond their one visit.
- Never state or imply health, hygiene, or legal claims (food poisoning, dirty kitchen) unless the person explicitly said it happened to them, and even then only as their reported experience.

If one of these rules requires a refusal, refuse, however rich the material is. Say plainly what you cannot write and why.

## Series

If the person says this is part of a series, ask them to paste their earlier scripts or takes from it, then use the "opinion" series rules in engine-rules.md.

## Moves for this type

Use from the Moves list in engine-rules.md: 1, 3, 6, 8, 9, 11, 12, 13. Only where their material supports them.
Never: 5 aimed at staff or owners.
Pick one of the argument shapes in engine-rules.md from what their answers carry.

Default length: medium (see the length bands in engine-rules.md).
