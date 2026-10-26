# Anchor Day 🌿

A calm daily planner built around how ADHD actually works — not a rigid timetable you have to obey, but a gentle structure you can lean on. Made for you to **use every day and change however you like.**

👉 **Open it here:** _(add your live link once it's published — see "Putting it online" below)_

---

## How to use it, day to day

You don't have to do anything special. Just open it in the morning.

- **Right Now** (top) — always shows what's happening now and what's next, with a little bar that fills as time passes. You never have to track time in your head.
- **Today's 3** — pick only three things that matter today. Three, not thirty. Tap the circle to check one off.
- **Focus sprint** — the hardest part of anything is *starting*. Type one thing, pick 10 / 25 / 45 minutes, hit **Start**, and just stay with it until the timer stops. You don't have to finish — starting is the win.
- **The shape of today** — your flexible routine. The ⚓ anchors (wake, meals, walk, wind-down) are the few fixed points that hold the day together; everything between them can move.
- **Brain dump** — a thought pulling at you mid-task? Park it here so it stops nagging, and keep going. Clear it later.
- **Wins** — counts everything you check off. Nothing ever turns red or scolds you.
- **"Jump back in at right now"** — fell off the plan? Totally normal. One tap re-centres you on the current moment. No catching up, no guilt.

**It remembers everything automatically.** Your schedule, your 3, your brain dump — all saved right in your browser on that device. Close it, come back tomorrow, it's all still there.

> One thing to know: it saves *per device and browser*. If you use it on your phone, always open it in the same browser (and the same link) so your stuff is there. Opening it on a different device starts fresh.

### Make it feel like an app

Add it to your phone's home screen so it opens full-screen with one tap:

- **iPhone (Safari):** open the link → tap the Share button → **Add to Home Screen**.
- **Android (Chrome):** open the link → tap the ⋮ menu → **Add to Home screen**.

---

## Making it yours (no coding needed)

Everything you'll want to change day to day is editable right in the page:

- **Change the schedule:** tap **Edit schedule** at the bottom of "The shape of today." You can change the time or wording of any block, **+ Add block**, or delete one with the ✕. Tap **Done editing** when you're finished.
- **Change your priorities:** just type over the three slots.
- Want a totally clean routine? In edit mode there's a **Restore example day** button to start over.

---

## Changing the built-in defaults (optional — a little bit of code)

The in-page editing above saves to *your browser*. If you'd rather change what the planner starts with for *everyone* who opens it (or you just like tinkering), edit `index.html`. You can do it right on GitHub — click the file, then the ✏️ pencil icon. Two easy spots:

- **The default schedule** — search the file for `DEFAULT_BLOCKS`. It's a plain list of times and labels. Add, remove, or reword lines; keep the format the same.
- **The daily #1 priority** — search for `SEED_PRIORITY`. That's the task that shows up in slot 1 of "Today's 3" each new day. Change the text in the quotes.

Save (GitHub calls it "Commit changes") and, if it's published online, your live link updates in a minute or two.

---

## Putting it online (so you have a link)

The simplest way, no software to install:

1. Create a free account at **github.com** (if you don't have one).
2. Make a new repository → choose **"uploading an existing file"** → drag in `index.html` and `README.md`.
3. In the repo, go to **Settings → Pages**, set the source to the `main` branch, and save.
4. GitHub gives you a link like `https://yourname.github.io/anchor-day/` in a minute or two. That's your planner. Bookmark it and add it to your home screen.

---

## A note on the design

Every piece of this is here for an ADHD-specific reason — time made visible to fight time-blindness, only three priorities to avoid overwhelm, tiny starting steps for the hard stuff, anchors instead of a brittle timetable, and a win counter with a no-shame reset because shame spirals are what actually derail a day. There's a **"Why this planner is built this way"** section at the very bottom of the page that explains it all.

It's yours now. Change anything. 💚
