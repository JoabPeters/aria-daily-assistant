# Aria — Daily Life Assistant (Simulated Alexa+ Experience)

Aria is a conversational assistant that helps people manage reminders, to-dos, and
their daily schedule through natural language, hands-free, the way Alexa+ would.

Built for the **Build, Ship, Shape: Amazon Developer Hackathon** — Alexa+ track,
simulated-experience path.

## What it does

- Add a reminder or to-do just by describing it: *"remind me to call mum at 6pm"*
- Ask what's on your list: *"what do I have today?"*
- Mark things done: *"I finished the report"*
- See everything at a glance in a live side panel

## How it works

The interface is a single self-contained web page (`index.html`). User input is sent
to an AI model that interprets the request as one of four actions (add, list,
complete, or none) and returns a structured response plus a natural, spoken-style
reply, mirroring how a voice assistant like Alexa+ processes a request end to end.

## Why it matters

Most reminder and to-do apps require typing, tapping through menus, and manual
sorting. Aria collapses that into a single spoken or typed sentence, useful for
anyone, and especially valuable for people who find typing or navigating screens
difficult (accessibility, multitasking, low vision).

## Running it

Open `index.html` in a browser. See the demo video for a full walkthrough.

## Track & submission

- **Track:** Alexa+ (simulated experience)
- **Mini challenge:** Open Source
