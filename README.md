# Lessons to My Son

Static, personal writing archive. No CMS, no database, no submissions.

## Structure
- `index.html` homepage
- `posts/` manual posts, named `YYYY-MM-DD-title.html`
- `styles/style.css` base styles
- `assets/` for images or files (optional)

## Publishing workflow
1. Write the essay.
2. Create a new file in `posts/` using the `YYYY-MM-DD-title.html` format.
3. Add a link on `index.html` with title, date, and author.
4. `git add .`
5. `git commit -m "Add post: YYYY-MM-DD title"`
6. `git push` (Vercel auto deploys from GitHub)

## Principles
- Longevity over features.
- Manual publishing only.
- Works with plain HTML/CSS.
