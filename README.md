# Big Data Study Room

A standalone study site for midterm and finals quizzes.

- `index.html`: exam selection home page.
- `midterm/index.html`: existing 115-question quiz from Exercises 1–4.
- `finals/index.html`: coming-soon page, ready to replace when finals material is available.

## GitHub Pages

In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select the branch containing these files and **/ (root)**, then save. GitHub Pages will show the published URL.

No installation or build step is required. Navigation uses relative links, so it works under a repository's GitHub Pages path.

## Progress

Midterm progress remains in this browser's existing `big-data-study-v1` local storage entry. The future finals quiz must use a different key, such as `big-data-finals-v1`, to keep progress separate. Moving between local files and a hosted site does not transfer browser progress.

## Adding finals later

Replace `finals/index.html` with the finals quiz and update its status on the home page. Keep the midterm file and its storage key unchanged.
