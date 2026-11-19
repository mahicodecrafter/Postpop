Postpop ✦

Plan the week. Pop the post.

Postpop is a colorful, animated content calendar for creators. Plan posts by week or month, keep a bank of content ideas, and let Postpop fill a whole week for you. It is a single HTML file. There is no login, no backend and no build step, and all your data stays in your browser.

Features
Week view: seven pastel day columns, a progress bar and weekly goal targets (Attract, Build trust, Sell).
Month calendar: your whole month at a glance, with goal-colored post chips and a day detail panel.
Content ideas: save ideas with format, platform, topic and goal. Filter them, then schedule any idea in one tap.
Surprise me / Fill a week: auto-plans a week from your unused ideas, balanced against your goal targets.
Post status board: Idea, Script, Film/Create, Edit, Scheduled, Posted. Drag posts between columns.
Drag and drop: move posts between days in week and month views.
Braindump and inspiration notes: saved per week. Turn braindump lines into ideas.
Multiple profiles: switch between creator handles, each with its own posts and ideas.
Motion: animated logo, marquee, floating shapes, page-in transitions and confetti when you mark a post as posted. Respects prefers-reduced-motion.
Light, dark or system theme.
Backup and restore: copy your data as JSON and import it on another browser.
Responsive: works on desktop, tablet and phone.
Quick start
Download or clone this repo.
Open index.html in any modern browser.

That is it.

To host it for free, push the repo to GitHub, then go to Settings → Pages, choose your branch and the root folder, and save. Your planner will be live at https://<your-username>.github.io/<repo-name>/.

How your data is saved

Everything is stored in localStorage under the key postpop.v1.

Data never leaves your device.
Each browser and device has its own copy. Use Settings → Copy my data and Import pasted data to move it.
Clearing site data or using a private window will erase or skip saving. The header shows "Not saving" when storage is unavailable.
Tech
Vanilla HTML, CSS and JavaScript in one file, with no framework and no dependencies.
Hash routing (#week, #calendar, #ideas).
Fonts from Google Fonts (Bricolage Grotesque and Fraunces) with system fallbacks, so it still works offline.
Project structure
postpop/
├── index.html   # the whole app
└── README.md
Customize
Colors: edit the :root tokens and the PAL object in the script.
Formats, platforms, topics, goals: edit the FORMATS, PLATFORMS, TOPICS and GOALS arrays.
Default weekly targets: change them in Settings, or edit settings.targets in seed().
Name: search for postpop to rebrand.
Roadmap ideas
Export to .ics for Google or Apple Calendar
Analytics for posted content
Hashtag and caption banks
Recurring post templates
License

MIT. Use it, remix it and ship it.
