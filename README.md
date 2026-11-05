# VolleyDrills

Animated volleyball drills for the County League teams at Cambridge Volleyball Club, compiled by Monika Krzak (County Women Assistant Coach and Beach Volleyball Ambassador).

**Live site:** https://mkrzak.github.io/VolleyDrills/

One self-contained page (`index.html`): a library of 17 drill cards across setting, hitting, blocking, passing, out of system, free ball, communication, pipe, serving and defence. The front page shows the cards with a topic filter; each card opens its own drill page (`index.html#drill-id`) with an animated court diagram, the steps, any relevant rule (e.g. libero setting), scoring, coaching cues and a progression.

The previous drills (Grow the Team, Defence Drill, Block Cover Drill) are kept in `old-drills.html`, which is not linked from the site.

Everything is built into `index.html`, so it also works offline: just open the file in a browser.

More training materials (warm-up, S&C, 5:1 systems, scoresheets and rules) are on [VolleySource](https://mkrzak.github.io/VolleySource/).

## Update the site

Replace `index.html` with the new version, then:
```
git add .
git commit -m "Update VolleyDrills"
git push
```
GitHub Pages republishes automatically after every push (Settings → Pages: deploy from branch `main`, folder `/ (root)`).
