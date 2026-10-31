# Iron Eight Logbook

A mobile-first web app for tracking an 8-week upper/lower strength program, 4 days a week.

**Live demo:** https://kudret05.github.io/iron-eight-logbook/

## Features

- **8-week periodized program**: Build, Deload, Strength and Peak phases (32 sessions), with sets, reps and RPE that change each week
- **Per-set logging**: enter weight and reps, tick a set done; last week's numbers show as a hint so you know what to beat
- **Progress dashboard**: block completion, sessions finished, sets ticked and total volume (kg moved)
- **Strength trend charts**: best estimated 1-rep max per week for bench, squat, row and deadlift (Epley formula: kg × (1 + reps ÷ 30))
- **Session notes** for sleep, pain, PRs
- **Saves automatically** in the browser (localStorage)
- **Dark mode** and responsive layout for phones

## Design

Phase colors borrow from competition weight plates: blue (20 kg) for hypertrophy, green (10 kg) for deload, red (25 kg) for strength, yellow (15 kg) for peak. Typography pairs Saira Condensed for headings with IBM Plex Sans and JetBrains Mono for numbers.

## Tech

Single-file app in plain HTML, CSS and JavaScript, with no frameworks or build step. Charts are hand-drawn SVG. Built with AI-assisted development (Claude).

## Author

Kudret Muminov · [@muminov.ascends](https://www.tiktok.com/@muminov.ascends)
