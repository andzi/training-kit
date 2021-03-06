---
layout: simple-class
header:
  overlay_image: cover.jpeg
  overlay_filter: rgba(46, 129, 200, 0.6)
title: Keep Things in Sync
permalink: /github-desktop/11/
next-page: /github-desktop/12/
facilitator: false
sidebar:
  nav: "github-desktop-nav"
main-content:
  includes:
    - activity/github-desktop/08-sync-desktop.md
show-me-how: "images/gifs/sync-changes.gif"
tell-me-why: |
  ## Keeping your local repository in sync

  As we discussed previously, Git doesn't require an internet connection which means it doesn't communicate with remote repositories unless explicitly instructed to do so.

  When you merge your Pull Request on GitHub.com, the changes you made locally are merged into the `master` branch on the _remote_ repository on GitHub.

   However, you won't automatically see those changes reflected in your local copy until you do another sync.

  You should `sync` your local repository regularly to ensure you are always working with the most recent copies of the files in the repository.

---
