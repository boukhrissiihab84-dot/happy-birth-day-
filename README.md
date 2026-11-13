# Our Little Universe

A responsive birthday website built with React, Vite, and TypeScript.

## Run it locally

Install Node.js 20 or newer, then run:

```bash
npm install
npm run dev
```

Or use pnpm:

```bash
pnpm install
pnpm dev
```

Create a production build with `npm run build` (or `pnpm build`).

## Personalize the page

1. Edit the name, date, captions, timeline, reasons, letter, signature, and final message in `src/config/content.ts`.
2. Put photos in `public/assets/photos/`, videos in `public/assets/videos/`, and music in `public/assets/music/`.
3. Update the matching media paths in `src/config/content.ts`.
4. Test on both a phone and desktop before sharing.

The site does not include personal information or media by default. Only add media you have permission to share. Files in `public/` are available to anyone who can access the published site; this site does not have a password gate or private account system.

## Publish with GitHub

Create a new GitHub repository, upload the contents of this folder, then commit and push. The included `package.json` makes this copy installable independently from the original Replit workspace.
