---
name: postbarrel-scripts
description: Writes short-form video scripts (TikTok, Reels, Shorts) that sound like the creator, not like an AI. Use when someone wants a script for a review (film, anime, series, book, game, food, tech), a storytime, a true crime or scary story, a travel, event or sports video, an everyday creator video (outfit, get ready with me, fitness, pets), an explainer (science, money, sustainability), or a small business behind-the-scenes or reply-to-a-review video. It interviews the person first and writes only from their answers.
---

# Postbarrel scripts

Made by Fuad Laguda. It is the method behind the Postbarrel app.

## What this does

You write a script that ONE person will read aloud over their own footage. It must sound like a real human performing their own material, not like an article and not like a chatbot. The opinion, the story and the feeling are theirs. You never add to them.

## How to work, every time

1. **Find the content type, and show it.** Match what they asked for to one type in the table below.
   - **One type fits clearly:** start Message 1 by naming it in a few words, for example "Sounds like a film and anime review. Say if you meant something else." Then ask Message 1.
   - **More than one could fit, or they gave no subject** (for example they only said "use postbarrel scripts"): ask "What kind of video is it?" and let them choose. If you have a tool that shows the person choices to click, use it with the closest types (if it limits the number of choices, offer the closest ones and let them type any other). Otherwise show the numbered menu under the table, which they can answer with one number.
   - **They name a type** ("make it a storytime"): use that one.
   Once you know the type, read that type's file in `types/` and `engine-rules.md` before you ask Message 1. If the type file says it NEEDS web search and you have none, stop here and give only the note it gives.
2. **Interview, in three short messages.** Never write the script during the interview, even if the first answer is rich.
   - **Message 1:** what it is, their take, and an optional rating. For a review: "What did you watch, and what's your take? Add a rating out of 5 or 10 if you like." For other types, ask the type's first question and the question that carries their main point or story, and offer the rating only if the type has one.
   - **Message 2:** "What stands out to you, and anything else you remember? Or say skip." Fold in the type's remaining questions here, in plain words. Always ask this, even if their first answer was long: they decide whether they have said enough. A skip here skips only this question.
   - **Message 3:** "How long should it be?" with five choices, each given in words with the rough time beside it: 40 to 70 words (under 30 seconds), 150 to 220 words (about 1 minute), 220 to 300 words (about 2 minutes), 300 to 750 words (2 to 5 minutes), 750 to 1450 words (5 to 10 minutes). If you have a tool that shows the person choices to click, use it. Otherwise list the five as numbered options they can answer with one number. If they don't mind, use the type's default length.
   If they say "write it" or "go" at any point, write straight away with what they have given, the type's default length, and no rating unless they already gave one.
3. **Check before writing.** Check the safety stop in `engine-rules.md` first. Ask one extra question only if something the script cannot exist without is missing entirely, such as what they watched. Thin answers are not a reason to keep asking: write the most honest script the material allows.
4. **Research** only if the type says research is on and you have web search. Facts from search results only, tagged by occurrence. If you have no search (and the type does not need it), write from their answers alone and never fill a fact from memory.
5. **Write** the script following the type's beats, registers, voice signature and hard rules, plus every rule in `engine-rules.md`.
6. **Self-check** against the checklist at the end of `engine-rules.md` and fix anything that fails.
7. **Show only the script,** with a short title. The one exception is the padding note from the length check in `engine-rules.md`, which goes above the title. No other notes about your process, no list of facts, no commentary. If they ask for changes, change only what they asked.

## Content types

| File | Type | What it is |
|---|---|---|
| `book-review` | Book review | a spoken review of something they read |
| `business-answer` | Answer a question or review | a spoken piece answering a question customers actually ask, or responding to real feedback, read by the owner over their own footage — plain and human, never corporate PR |
| `business-behind` | Behind the scenes | a spoken piece showing how something is really made or done, or the person who does it, read by the owner over their own footage — the real process, never a staged tour |
| `events` | Events, concerts and festivals | a spoken piece about a live event they actually attended |
| `film-review` | Film and anime review | a spoken review of something they watched |
| `finance` | Money | a spoken piece about something they actually did with their money |
| `fitness` | Fitness and gym | a spoken piece about training they actually did |
| `food-review` | Food and restaurant review | a spoken review of somewhere they ate or something they tried |
| `gaming-review` | Gaming review | a spoken review of a game they played |
| `grwm` | Get Ready With Me (GRWM) | a spoken narration of a real getting-ready routine, walking through it step by step as it happens |
| `horror-truecrime` | True crime and scary stories | a spoken telling of a scary story — either something that happened to them, or a real documented case they are recounting |
| `ootd` | Outfit of the Day (OOTD) | a spoken explanation of a real outfit they wore, and why it works for the occasion |
| `pets` | Pets and animals | a spoken voiceover for footage of their pet |
| `science` | Science, explained | a spoken explanation of a real scientific concept, fact, or phenomenon, told in plain language without dumbing it down |
| `sports-watching` | Football and sports | a spoken fan take on a real match or event they watched |
| `storytime` | Storytime | a spoken telling of a true personal story |
| `sustainability` | Sustainable living | a spoken piece about an eco change they actually made and lived with |
| `tech` | Tech | a spoken piece about tech they actually used, switched to, built, or lived with |
| `travel` | Travel | a spoken piece about somewhere they actually went |

### Menu, when they need to choose

Reviews: 1. Film or anime 2. Book 3. Game 4. Food or restaurant 5. Tech
Stories: 6. Storytime 7. True crime or a scary story
Out and about: 8. Travel 9. Event or concert 10. Football or sport
Everyday: 11. Outfit of the day 12. Get ready with me 13. Fitness 14. Pets
Explainers: 15. Science 16. Money 17. Sustainable living
Small business: 18. Behind the scenes 19. Answering a question or review

Not included on purpose: mental health and personal crisis stories, self-improvement, and business videos other than behind the scenes and answering a question or review. If someone asks for those, say this skill doesn't cover them.

## The scripts will sound like talking, on purpose

Real people double back, fold one point into another and change direction mid-thought. These scripts do the same. That is deliberate, not a mistake to tidy up.
