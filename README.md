# Anchor Day

Anchor Day is Jackie's editable daily and weekly dashboard. It turns vague expectations into visible, finite choices without making the dashboard a report card.

## What is included

- **Today:** live “right now” guidance, three priorities, focus timer, editable schedule, brain dump and wins.
- **Before bed:** a separate editable checklist. Its wording persists; its checkmarks reset each day.
- **History:** 7-day, 30-day and all-history views showing each day’s planned priorities, completed priorities, other checked items and optional daily note.
- **Week:** Monday–Friday career lanes, weekend home/food lanes, two workouts that can land on any days, the Friday-to-Sunday food handoff, and daily yes/no packing choices for oats, snacks, shake, yogurt, fruit and lunch plus the dinner plan.
- **Lists:** job leads and a parking lot for errands, returns, admin and ideas. Job leads are suggestions until Jackie chooses their status.
- **Household:** editable agreements with Jackie’s part, Denzil’s part, a definition of done and a low-capacity version.
- **Private food-planner shortcut:** a Google Sheet URL can be saved in the browser without putting the private link in the public GitHub files.
- **Backup:** download or import the planner’s browser data as JSON.

The initial nightly list is:

1. Make sure the sink is empty at night.
2. Make sure there is no clothing on the bedroom floor.
3. Make sure there are no plates or utensils in the living room.

Every item and agreement can be edited or removed in the page.

## Important storage limitation

The site is static and private data is saved in `localStorage`, which means it stays in that specific browser on that specific device. Each calendar day gets its own saved record: “Today’s 3” starts fresh the next day, while the previous day remains visible in **History**. GitHub Pages does **not** sync checkmarks or entries between Jackie’s and Denzil’s phones.

Use **Household → Download backup** before clearing browser data or moving devices. A later version could add accounts and live device sync, but that requires a database/authentication service rather than GitHub Pages alone.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `anchor-day`.
2. Upload `index.html`, `README.md` and `.nojekyll` to the repository’s `main` branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then save.
6. GitHub will provide a URL such as `https://YOUR-USERNAME.github.io/anchor-day/`.

On iPhone, open the published link in Safari, tap **Share**, and choose **Add to Home Screen**.

## Everyday use

- Open **Today** in the morning. “Out of bed by 9:30” and “in bed by 1:30” are anchors, not a minute-by-minute test.
- Choose no more than three priorities.
- Complete one 30–45 minute primary focus block. The suggested weekly career rhythm is three application blocks and two HubSpot blocks.
- Pick ClassPass dates only when the schedule becomes clear; the weekly commitment is two workouts, not fixed weekdays.
- On Friday, Denzil fills in the food needs; Saturday is recipe/list selection; Sunday is groceries plus one meal-prep session.
- If a new errand appears, note what it replaces. It does not silently stack on top of the plan.
- “Moved,” “Rest day” and the low-capacity versions are valid outcomes.

## Privacy

Do not put private links, medical details or personal notes directly into the public source code. The optional Google Sheet link is intentionally entered only after opening the site and is stored locally in the browser.
