# VolleyDrills

Animated volleyball drills for the County League teams at Cambridge Volleyball Club, compiled by Monika Krzak (County Women Assistant Coach and Beach Volleyball Ambassador).

**Live site:** https://mkrzak.github.io/VolleyDrills/

The page (`index.html`, with drill data in `more.js`, `more2.js` and `more3.js`): a library of 120 drill cards (twelve per topic, easy to advanced) across setting, hitting, blocking, passing, out of system, free ball, communication, pipe, serving and defence. The front page shows the cards with a topic filter; each card opens its own drill page (`index.html#drill-id`) with an animated court diagram, the steps, any relevant rule (e.g. libero setting), scoring, coaching cues and a progression.

The previous drills (Grow the Team, Defence Drill, Block Cover Drill) are kept in `old-drills.html`, which is not linked from the site.

Keep `index.html` and the `more*.js` files together; it works offline by opening `index.html` in a browser.


## Update the site

Replace `index.html` with the new version, then:
```
git add .
git commit -m "Update VolleyDrills"
git push
```
GitHub Pages republishes automatically after every push (Settings → Pages: deploy from branch `main`, folder `/ (root)`).
