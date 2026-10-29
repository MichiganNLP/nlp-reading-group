# Michigan NLP Seminar

Website for the University of Michigan NLP Seminar (formerly the NLP Reading Group), a weekly seminar on NLP and LLM research.

The site is a single static page, `index.html`, served by GitHub Pages from the `main` branch. The home view shows the current schedule; `#archive` lists every past talk since Winter 2023.

To update the schedule, edit the talk lists in `index.html` and push to `main`. The "Next session" card and its Google Calendar link advance on their own to the first talk in `#fall-schedule` or `#winter-schedule` (`<li data-date="YYYY-MM-DD">`) that has not ended yet, re-checking every minute while the page is open, so list only confirmed talks there; add `data-time="17:00"` for a session outside the default 11:00 AM ET slot. Speaker and host photos are 200×200 JPEGs in `images/people/`, cropped from each person's own homepage; a speaker without a public photo gets a blank spacer (`<span class="t-pic t-nopic"></span>`) instead, never a placeholder avatar. Sign-ups and paper suggestions live in the [group Google Sheet](https://docs.google.com/spreadsheets/d/1yyMZw2ZXc6kvGz80anxgtc12o3QHLTpG3Z1kvxIpRDk/edit).

To join the seminar, [enroll](https://mcommunity.umich.edu/group/NLP%20Reading%20Group) in its mailing list on MCommunity (still named "NLP Reading Group").
