# arthurr_pencilgon: Portfolio (Akatsuki Edition)

A single-file portfolio (`index.html`). No build step, no dependencies. Just open it in a browser.

Content is merged from the original React/Vite portfolio (NIPUN.DEV): profile, TaskFlow project,
skills, learning/interests, approach, contact links and SEO tags.

## Edit your info
Open `index.html` in any text editor and find the block labelled `EDIT YOUR INFO HERE` (inside the `<script>` near the bottom):
- `name`, `handle`, `initials`, `tagline`, `status`, `location`, `introduction`, `journey`, `focus`
- `email`, `github`, `linkedin`, `resume`: full links (email = just the address). Empty `resume` hides the CV button
- `learning`, `interests`: lists shown in the About section
- `skills`: skill groups `{title, desc, status, icon, items:[...]}`; icon = code | globe | db | term | brace | layers
- `projects`: each has `title, subtitle, desc, status, state ('ongoing' or 'completed'), tech, features, preview`. Copy the block to add a project; a small 'Upcoming' tile always stays at the end. Add `github:'https://...'` and
  `url:'https://...'` when TaskFlow's repo and live demo are ready, and the "coming soon" placeholders turn into buttons
- `sections`: set `builds`, `fieldkit`, `skills`, `roadmap` or `contact` to `false` to hide it
- `accent` / `accent2`: optional colour overrides

Save, refresh the page, done.

## Put it online (free)
1. Create a GitHub repo and upload `index.html`.
2. On vercel.com choose Add New → Project → import the repo. Framework preset: Other. Leave build settings empty and deploy.
   (Alternative: drag the folder onto app.netlify.com/drop.)

## Notes
- Fonts load from Google Fonts, so the first load needs internet.
- Animations switch off automatically for visitors with "reduce motion" enabled.
