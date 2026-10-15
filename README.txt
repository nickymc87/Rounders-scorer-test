ROUNDERS SCORER — V8 COMBINED PREVIEW

This preview is separate from the current v7.5 scoring app. DO NOT replace your existing GitHub Pages files until you are ready to test and have backed up important match results.

FILES
index.html: fixed-ball 20-good-ball and timed scoring preview, last-batter option, one-minute rest countdown, scorecards/signatures from v7.5.
tournament.html: tournament organiser demonstration with team registration by organiser, fixture entry, league standings (3/2/1 points), groups and knockout fixture lists.
service-worker.js and other assets: offline support and branding.

WHAT DOES NOT WORK YET
This prototype does not synchronise between phones, issue club registration links, verify accounts, publish live scores, enforce official eligibility, or advance knockout winners automatically. Those require a deployed secure backend and proper authentication. Do not use the demo for official results.

IMPORTANT RULES
Rules are implemented according to the user-provided description, not formally certified as Rounders England compliant. Check the last-batter rule and no-ball scoring with the umpire. In timed innings the umpire starts the clock; one-minute rest does not pause it; no deliveries after time expires. Fixed 20 good balls never exceeds the cap.

TEST CHECKLIST
1. Choose fixed 20 and confirm one innings per team; start away team first.
2. Record ordinary, rounder, half-rounder, no ball, no-ball rounder; check delivery/good-ball counters.
3. Put all but one batter out. Check last-batter 3-ball option, reset after full rounder, and one-minute rest.
4. Confirm innings ends at 20 good balls even after a reset; test with only 1-2 good balls left.
5. Timed format: manually start timer, verify rest does not pause, verify scoring disabled at 00:00.
6. Complete match, two-umpire signoff, print/save PDF.
7. Open tournament.html: add fictional teams, create fixtures, record results and check points and rounders difference.
8. Check offline loading after first visit.

This is a testing milestone, not the final connected tournament release.
