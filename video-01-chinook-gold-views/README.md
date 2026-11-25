# Video one: Gold views and an exam on Chinook

One task, two runs. First by hand, then with AI. Same task, same exam, an on-screen stopwatch on both.

## The task

Build three Gold views on the Chinook database in PostgreSQL:

- Monthly revenue
- Revenue by genre
- Customer value (revenue and orders per customer, by country)

## The exam

- 10 business questions with a written answer key
- 7 standard questions and 3 new ones an AI could not have memorised
- One question is a trap: summing invoice totals after joining down to the invoice lines counts each invoice once per line
- The answer key comes from plain SQL on the raw tables, not from the AI
- A script compares result sets with a small tolerance and prints PASS or FAIL per question

## Status

Setup only. The SQL, the exam script and the timings land here as they are built.
