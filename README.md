# English Hub — Teen Journal

A responsive, static Grade 8 English learning journal. It uses plain HTML, CSS and JavaScript, has no dependencies, and stores student work in the browser's `localStorage`.

## Open locally

Download or clone the project, then double-click `index.html`. No server or build command is required. Answers and progress belong to the browser and device where the file is opened.

## Edit lesson data

Open `app.js` in a text editor:

- `lessons` contains the 12 module-card titles and descriptions.
- `lessonOne()` and `lessonTwo()` contain the detailed interactive tasks.
- `starterLessons` contains tasks for Lessons 3–12.
- `grammarTopics` and `vocabulary` control those journal sections.

The helper functions `textTask`, `mcTask`, and `selectTask` can be reused for new activities. Keep each saved task ID unique so its answer has its own localStorage entry.

## Publish with GitHub Pages

1. Create a GitHub repository and add these four files at its root.
2. Push the files to the default branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch and `/ (root)`, then save.

GitHub will show the public Pages address after deployment. Because all paths are relative and there is no backend, the app works unchanged on Pages.
