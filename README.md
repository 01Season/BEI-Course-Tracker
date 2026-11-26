# BEI-Course-Tracker

A checklist page for the B.E. Electronics, Communication & Information Engineering course structure (8 semesters, 51 subjects). Tick subjects as you finish them to see how many are done, how many remain, and your completion percentage.

## Use

1. Open `bei-tracker.html` in any browser.
2. Tick a subject when done; untick to undo.
3. Check the ring, bar and stats at the top. **Clear all** resets everything.

## Progress

`percentage = round(completed / 51 * 100)`. Every subject counts equally, and all ticked is 100%.

## Customize

Edit the `DATA` array in the script to change subjects, and the CSS variables at the top (`--coral`, `--card`, etc.) to change colors.

## Privacy

Ticks are saved only in your browser (`localStorage`). Nothing is sent anywhere, and progress doesn't sync between devices.
