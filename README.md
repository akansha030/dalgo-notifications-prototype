# Dalgo — Notifications prototype (review fixes)

A self-contained design prototype of the Dalgo **Notifications** page, with the fixes raised in review of the new build. Open `index.html` in a browser, or view the live version via GitHub Pages.

**Design artifact only** — mock data, no product code, no real data.

### Fixes demonstrated
1. **Concise filter** — the 7 notification types roll up into 3 groups (Data & pipeline · Collaboration · Platform). Each row still shows its specific tag.
2. **Labelled "Urgent" badge** — replaces the bare red icon that had no visible meaning.
3. **Clear "See more / See less"** — truncated messages get an obvious, spaced inline toggle.
4. **Contextual bulk actions** — *Mark as read / Mark as unread* appear only when rows are selected. There's no separate "Mark all as read" button: **Select all** on a page offers **"Select all N across all pages"**, which correctly reaches notifications on other pages.

Built as a single HTML file (React + Tailwind via CDN).
