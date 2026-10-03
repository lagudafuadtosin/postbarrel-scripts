# Postbarrel scripts

A free Claude skill that writes short-form video scripts (TikTok, Reels, Shorts) that sound like you, not like an AI.

It interviews you first and writes only from your answers. Your opinion, your story and your verdict stay yours. It never adds an event, a name, a number or a feeling you did not give.

Made by Fuad Laguda. The same method runs the Postbarrel app at https://postbarrel.com/?utm_source=skill-readme, which adds saved profiles, series memory, a teleprompter and recording.

## What it writes

19 content types:

- Reviews: film and anime, book, gaming, food and restaurants, tech
- Stories: storytime, true crime and scary stories
- Out and about: travel, events and concerts, football and sports
- Everyday: outfit of the day, get ready with me, fitness, pets
- Explainers: science, money, sustainable living
- Small business: behind the scenes, answering a question or a review

## Install

**From the Claude directory:** find Postbarrel scripts in the directory inside Claude and add it. It works in Claude chat, Cowork and Claude Code.

**Claude Code from this repository:** copy the `skills/postbarrel-scripts` folder into `~/.claude/skills/`.

**Claude chat without the directory:** download `postbarrel-scripts.zip` from the Releases page of this repository, open Settings, find Skills, and upload the zip.

Then ask for a script, for example "write me a review script for the film I watched last night".

## How it works

1. It asks what you watched, did or want to talk about, and your take. Reviews can add a rating.
2. It asks what stands out and anything else you remember. Say skip if you have nothing to add.
3. It asks how long, in words, with a rough time beside each choice.

Say "write it" or "go" at any point and it writes straight away with what you have given.

If your answers are short for the length you picked, it still writes to that length and puts a note at the top telling you it padded the script.

## Web search

Science, money, fitness and true crime need web search turned on, because the facts are the video and a wrong one can mislead people or wrong a real person. Without search, those four ask you to turn it on and try again. Every other type writes from your answers alone when search is off, and uses search to check facts when it is on.

## The scripts sound like talking, on purpose

Real people double back, fold one point into another and change direction mid-thought. These scripts do the same. That is deliberate, not a mistake to tidy up.

## What it runs and sends

Nothing. The skill is plain text instructions. It has no code, no scripts, no connectors and no hooks. It does not store your answers, read your files or chat history, or send anything anywhere. When web search is turned on in Claude, it uses Claude's own search to check facts, and nothing else.

## Troubleshooting

- **It writes before asking anything.** Make sure you asked for a script, and that the skill is turned on. It always asks three short questions first unless you say "write it" or "go".
- **It says a type needs web search.** Turn on web search in Claude and ask again. Science, money, fitness and true crime need it.
- **It picked the wrong type.** Say which type you want, for example "make it a storytime".
- **The script is shorter or longer than you wanted.** Ask for the length in words, for example "make it 150 to 220 words".

## Use at your own risk

This skill writes from what you tell it. It does not give financial, medical, legal or fitness advice, and it can get things wrong. Check every fact before you post. You are responsible for what you publish.

Tested on Claude. It is plain text, so other AIs can read it, but they have not been tested.

## Support

Report a problem or ask a question on the Issues page of this repository: https://github.com/lagudafuadtosin/postbarrel-scripts/issues

## Licence

Creative Commons Attribution 4.0 (CC BY 4.0). You can use, change and share it, including commercially, as long as you credit **Fuad Laguda and Postbarrel (https://postbarrel.com)**. See `LICENSE`.
