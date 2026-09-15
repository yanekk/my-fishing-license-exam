# Karta Wędkarska — Trener

Single-file, offline study app for the Polish angling-card exam (egzamin na kartę
wędkarską), tuned for the PZW Okręg Gdański district. Open index.html in any browser —
no build step, no server, no account. Progress is saved in the browser's localStorage.

## Modes
- Nauka — within-session mastery loop (built for a one-night cram, not day-scale spacing).
  Grade each card Nie znam / Prawie / Umiem; "Umiem" twice retires the card for the session.
  A readiness gauge shows how much you confidently know; a topic filter drills a weak area.
- Egzamin próbny — randomized single-choice mock exam (10/20/30 q), immediate feedback,
  pass threshold 70%, per-topic breakdown, and a list of what you missed.
- Postępy — mastery per topic (weakest at the bottom) and best mock-exam score.

## Content
92 questions across 7 topics (25 minimum-size, 14 closed-season, plus rules, documents,
methods, distances, limits, species protection). Every answer carries its source. Where the
Gdańsk RAPR is stricter than national law, the app uses the district value (sandacz 50 cm,
szczupak 50 cm, węgorz 60 cm, okoń 18 cm, daily bag limits, etc.).

Sources: RAPR PZW Okręg Gdański 2026; Rozporządzenie MRiRW z 12.07.2023 (Dz.U. 2023 poz.
1373); Ustawa o rybactwie śródlądowym z 18.04.1985; 50 official example questions (ompzw.pl).

Not legal advice. Verify against current regulations and your permit before fishing.
