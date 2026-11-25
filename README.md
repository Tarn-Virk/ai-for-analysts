# AI for analysts

Short videos where one analyst task is done by hand, then again side by side with AI, with checks included. Each run is timed on screen. Everything is on small public datasets so you can rerun it yourself.

Part of the de-tech-ify channel.

## The rule behind every video

- **AI proposes.** It drafts the SQL, the views and the plan.
- **The engine computes.** The database runs the queries. The numbers never come from the AI.
- **You approve.** Nothing counts until it passes the checks and you have read it.

Under every stage sit three things: Git history, a query log and a 10-question exam.

## What is in here

| Folder | What it holds |
| --- | --- |
| `video-01-chinook-gold-views/` | Video one: three Gold views and a 10-question exam on the Chinook database |
| `skills/` | The skill and prompt pack that reruns each video's AI run |

Each new video gets its own `video-NN-...` folder.

## Data

Video one uses the Chinook sample database (a digital music store), loaded into PostgreSQL.

- Source: https://github.com/cwoodruff/ChinookDatabase
- Licence: MIT

## Status

Video one is in progress. Files land here as each step is built.
