# InkAndPanel

**One platform. Every story worth telling.**

InkAndPanel is a responsive storytelling web app prototype that brings written fiction and vertical comics into one reading and creator experience.

## Features in this prototype

- Discover demo stories by genre, format, and search.
- Read sample novel chapters and browse vertical comic episodes.
- Save stories to a personal library, mark stories as liked, and track what you are reading.
- Open story detail pages and post local reader comments.
- Create a profile and edit your display name, username, and bio.
- Draft, edit, and publish your own sample stories from Creator Studio.
- Upload comic panel image URLs, switch between dark and light themes, and use the layout on mobile or desktop.
- Custom InkAndPanel app icon.

## Try it locally

No build tools or package installation are needed. Open `index.html` in a modern browser.

## GitHub Pages

The repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`. In the repository's **Settings → Pages**, set the build and deployment source to **GitHub Actions** if it is not already selected. After that, pushes to `main` can trigger deployment. The expected project URL is:

`https://factorydefaulth12.github.io/InkAndPanel/`

GitHub Actions must complete successfully before the URL is considered live.

## Important prototype limits

This is currently a front-end prototype. Story data, drafts, likes, comments, and profile details are saved in the current browser with localStorage. They are **not** synced to a server, shared between users, or protected by real accounts. Do not store sensitive information here.

Real authentication, cross-device syncing, public uploads, shared comments, moderation, notifications, and payments require a backend and additional security work.

## Technology

Plain HTML, CSS, and JavaScript. No framework or build step, keeping the project lightweight and suitable for low-spec devices.

## Brand

InkAndPanel combines the two storytelling formats the platform is built around: ink on a page and panels in a comic.
