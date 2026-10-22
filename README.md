# Introduction to the New Testament: Learning Games

Five standalone learning games, one for each unit of the GSOL course guide *Introduction to the New Testament*, with a homepage that links to them. Everything is plain HTML, CSS and JavaScript: no server, database, API key or external library.

## Files

```text
course-games/
├── index.html      (homepage)
├── unit_1.html     (Unit 1: Into the Silent Years)
├── unit_2.html     (Unit 2: Keepers of the Canon)
├── unit_3.html     (Unit 3: Witnesses on the Road)
├── unit_4.html     (Unit 4: Letters to the Churches)
├── unit_5.html     (Unit 5: Signs of the Kingdom)
└── README.md
```

## Games and activity types

- **Unit 1: The World Behind the New Testament**, game *Into the Silent Years*: 13 challenges; Narrative Detective, Story Sequencer, Theme and Character Matcher, Unlock the Scroll, Arrange the Evidence, Choose Your Path, Build the Story, Reflection Challenge.
- **Unit 2: How We Got the New Testament**, game *Keepers of the Canon*: 12 challenges; Unlock the Scroll, Story Sequencer, Arrange the Evidence, Narrative Detective, Build the Story, Theme and Character Matcher, Choose Your Path, Reflection Challenge.
- **Unit 3: The Gospels and Acts**, game *Witnesses on the Road*: 13 challenges; Narrative Detective, Theme and Character Matcher, Arrange the Evidence, Build the Story, Choose Your Path, Story Sequencer, Unlock the Scroll, Reflection Challenge.
- **Unit 4: The Epistles and Revelation**, game *Letters to the Churches*: 13 challenges; Build the Story, Unlock the Scroll, Arrange the Evidence, Theme and Character Matcher, Narrative Detective, Choose Your Path, Story Sequencer, Reflection Challenge.
- **Unit 5: The Theology of the New Testament**, game *Signs of the Kingdom*: 13 challenges; Unlock the Scroll, Arrange the Evidence, Theme and Character Matcher, Narrative Detective, Choose Your Path, Story Sequencer, Build the Story, Reflection Challenge.

## Scoring

- Each challenge is worth 10 points.
- Sequencing, matching, sorting and story-map tasks earn points in proportion to the items placed correctly; full marks require the whole response to be correct.
- Unlock the Scroll: 10 / 6 / 3 points on the first / second / third try.
- Choose Your Path: 10 for the best response, 5 for a partial one, 0 otherwise. All scenarios are hypothetical.
- Reflection: 10 points for completing at least 25 words. Reflections are not graded automatically; students compare their answer with guidance and a model response.
- Answer options are shuffled every time a challenge is shown and when a game is restarted.

## Publish on GitHub Pages

1. Sign in to GitHub and create a new repository (for example `nt-course-games`), or open an existing one.
2. Click **Add file → Upload files**. Upload `index.html`, `unit_1.html` to `unit_5.html` and `README.md` into the **root** of the repository, all in the same folder.
3. Keep the homepage named exactly `index.html`.
4. Click **Commit changes**.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then click **Save**.
7. Wait a minute or two for deployment. The site address appears at the top of the Pages settings (for example `https://<your-username>.github.io/nt-course-games/`).
8. Open the site, check that the homepage shows all five unit cards, and click each card to confirm it opens the correct game.

All links are relative, so the site works as a GitHub Pages project site or opened directly from a folder on your computer.
