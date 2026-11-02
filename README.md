<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/psychedelicsinrecovery/.github/main/profile/assets/banner-dark.svg">
  <img alt="PIR®, Psychedelics In Recovery™: a night sky breathing toward daybreak, where constellations draw themselves in (still, for readers who ask for reduced motion)." src="https://raw.githubusercontent.com/psychedelicsinrecovery/.github/main/profile/assets/banner-light.svg" width="100%">
</picture>

# <img src="assets/icons/book-open.svg" width="32" height="32" alt=""> PIR® Reading Room (public)

</div>

> <img src="assets/icons/globe.svg" width="16" height="16" alt=""> **[psychedelicsinrecovery.github.io/reading-room-public](https://psychedelicsinrecovery.github.io/reading-room-public/)** ·
> <img src="assets/icons/scroll-text.svg" width="16" height="16" alt=""> [Public procedures](https://github.com/psychedelicsinrecovery/ops-standard-operating-procedures-public) ·
> <img src="assets/icons/door-open.svg" width="16" height="16" alt=""> [The members' room](https://github.com/psychedelicsinrecovery/reading-room) (sign in; the way in for members) ·
> <img src="assets/icons/users.svg" width="16" height="16" alt=""> [Who's who](https://github.com/psychedelicsinrecovery/.github/blob/main/CONTACTS.md)

The public side of **Psychedelics In Recovery™ (PIR®)**'s reading room: a one-page front end (`index.html`, no build
step) that lists what PIR® has made ready for visitors (the public procedures, the decks, what the Board has
published) and says how members ask for the private room.

## <img src="assets/icons/book-open.svg" width="24" height="24" alt=""> What's public here

| File | What it is |
|---|---|
| [`index.html`](index.html) | The page GitHub Pages serves: plain HTML and CSS in PIR® purple, readable on a phone, light and dark |
| `README.md` | This page |
| `room-manifest.json` | Written by each sync: the list of files it carried. The page's **Read now** list is built from it, so it shows exactly what arrived |
| everything else | Only paths an officer adds to the private room's `PUBLIC-ALLOWLIST.txt`: since 2026-11-01, proposal **000 Start here** and the universal procedures as PDFs, arriving with the first sync (it waits for its key) |

## <img src="assets/icons/folder-lock.svg" width="24" height="24" alt=""> The private side

This repository is published from PIR®'s private `reading-room` by an allowlist and a tripwire that reads every file,
PDFs included, and is **never edited by hand**: the page's source lives in the private room's `public-site/` folder. Members can request the private room
with `/github` in [PIR®'s Discord](https://discord.gg/MyprTq8w95) or the
[web helpdesk](https://psychedelicsinrecovery.github.io/alex-desk-public/portal.html).

<sub>Icons: Lucide (ISC), carried here by the sync from the private room's `assets/icons`, so they never go stale (SOP-OPS-003).</sub>
