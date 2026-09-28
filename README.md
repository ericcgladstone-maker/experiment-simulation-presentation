# Building and simulating a behavioral experiment with an AI agent

Eric Gladstone · research walkthrough · independent work · September 2026. The presentation's own header reads "Experimental rehearsal · Experimental design".

A real Claude Code session, presented as it was worked through. The Claude Code console is on the left and my commentary is on the right. Starting from a client brief, the session decides what the first experiment has to answer, reviews outside evidence, specifies the measures and decision thresholds, compares designs, and builds the chosen one as protocol, analysis plan and code. It then simulates the experiment 400 times in each of ten synthetic worlds where the truth is known, stress-tests its assumptions, finds where it could mislead a decision, revises it, retests the revision on the same worlds, and ends with a conditional recommendation.

- **Live:** https://experimentsimulation.eric-c-gladstone.workers.dev
- **Also at:** https://graystoneindustries.co/talks/ (embedded)

## What is verbatim and what is editorial

The questions are mine. Claude's replies and tool output are verbatim, from one continuous session (Claude Code 2.1.282, Opus 5.5), recorded 27 September 2026. Turns 1–20 are the original build. Turns 21–23 are later questions in the same session, labeled on screen, that show one synthetic experiment end to end, draw two figures from the saved results, and bring the decision table forward; they changed nothing the earlier turns produced. Omitted parts of replies are marked on screen. Timing, grouping into parts, focus, and the commentary on the right are editorial.

The organization (Civic Access Network) and its brief are fictional, written for this demonstration. The session ran in an isolated directory, and account names are removed from the published data.

## Use

Open it and step with ← →. Use shift+← → to move between sections and space to play. A− / A+ (or the - and = keys) change the terminal text size. URL options: `?s=<screen>&b=<part>` opens at a given point, `?play=1` autoplays, `?t=<px>` sets the terminal size, and `?embed=1` fills its frame for embedding.

Run locally with any static server, for example `python3 -m http.server 4720 --directory public`.

## Files

`public/` is the whole site: `index.html`, `app.js`, `style.css`, `data/session.js` (the session, as the page plays it), `data/walkthrough.js` (the commentary), `data/figures/` (the two figures the session drew), self-hosted Geist fonts, and `vendor/marked.umd.js` (MIT) for rendering Markdown. It makes no third-party requests.
