# Meshdiff Desktop

**See exactly what changed between two versions of a 3D model, and whether it will print. Free, on your own computer, no account, no upload.**

[**Download for Windows**](https://github.com/Projscope/meshdiff-releases/releases/latest) &nbsp;·&nbsp; [meshdiff.com](https://meshdiff.com) &nbsp;·&nbsp; [Pricing](https://meshdiff.com/pricing)

---

You changed a bracket, a gear, an enclosure. Did the wall get thinner? Did a hole shrink? Is there a new overhang that will need supports? Scrolling through two CAD exports side by side won't tell you. **Meshdiff does.**

Drop in your STL, OBJ or 3MF files, and Meshdiff compares each version with the one before it: what was added, what was removed, how much volume and size changed, and whether the part is still printable.

## Free. Really.

Meshdiff Desktop is **free software**: no price, no trial, no account. Everything below works offline:

- **Compare versions** of a model and see added and removed material in 3D, colour-coded.
- **Printability checks** for FDM printing: wall thickness, overhangs, small holes and an overall pass / warn / fail.
- **Measurements and hole detection**: volume change, bounding-box change per axis, hole diameters before and after.
- **Version history** for every project: every file you add becomes a version, with a plain-language summary of what changed.
- **Comments pinned to the 3D model**: click a spot on the part, leave a comment, reply, mark it resolved.
- **Works with real-world files**: STL, OBJ and 3MF, including 3MF exports from slicers such as BambuStudio, PrusaSlicer and OrcaSlicer.
- **Big models are fine**: detailed parts with hundreds of thousands of triangles are analysed in seconds on a modern computer, and Meshdiff sizes its limits to your machine so it never freezes.
- **Updates itself**: new versions download in the background and install when you restart.

## Your models stay yours

This is not a cloud tool with an offline mode. It is a desktop app that **doesn't need the cloud at all**.

- Your projects, model files and comments live in a folder on **your** computer. Open it, copy it, back it up.
- No account, no sign-up, no telemetry on your models.
- The app's window **cannot make network requests**, and the app has no feature that uploads your model files.
- If you ever do sync with a team (below), **your model files are still never uploaded**.

Working on proprietary hardware? Unreleased products? Client designs? That's what this is built for.

## Free offline. Paid only when you go online with a team.

Meshdiff Desktop costs nothing. The paid part is the **online collaboration** on [meshdiff.com](https://meshdiff.com), and only if you want it:

| | **Desktop** | **With a Team plan** |
| --- | --- | --- |
| Compare, analyse, comment, version history | Free, offline | Same |
| Account required | No | Yes (same account as the website) |
| Where your files live | Your computer | Your computer (never uploaded) |
| Sync a project with your team | | **Yes** |
| Teammates see your versions' stats and comments | | **Yes** |
| Teammates' comments and replies arrive on your desktop | | **Yes** |
| Review and approval workflow on the web | | **Yes** |

**How team sync works:** connect a project to your team and Meshdiff shares, for each version, its file name, size, a SHA-256 fingerprint of the file, the analysis results and your comments. A teammate opens the project on their desktop, sees every version's stats and every comment, and attaches **their own copy** of the file to see it in 3D. The app accepts it only if it is exactly the same file (the fingerprint must match). Nobody ever uploads a model.

See [meshdiff.com/pricing](https://meshdiff.com/pricing) for current plans.

## Part of Meshdiff

Meshdiff is a review and version-control layer for 3D designs, and the desktop app is its local-first client:

- **[meshdiff.com](https://meshdiff.com)**: in the browser, the free **Live Diff** tool compares two models in seconds with no sign-up, and paid plans add project workspaces, version history, comment pins, PDF diff reports and, with Team, review and approval workflows for hardware teams.
- **Meshdiff Desktop** (this app): the same comparison engine on your own computer, with your files kept local, plus optional sync with your team's projects on meshdiff.com.

Use either one or both; they speak the same language.

## Install

1. Download **`Meshdiff-Setup-<version>.exe`** from the [latest release](https://github.com/Projscope/meshdiff-releases/releases/latest).
2. Run it. It installs for your user only, so it needs no administrator rights, and starts straight away.
3. Create a project, add your first model, add the next version, and see what changed.

Windows 10 and 11 (64-bit). macOS and Linux are not available yet.

> **Heads up:** while we get the installer code-signed, Windows SmartScreen may show an "unknown publisher" warning. Choose **More info → Run anyway**. Every release is built automatically from source by GitHub Actions and published here.

## Questions

**Is it really free?** Yes. The desktop app, used offline with no account, has no price, no trial and no limit on projects or versions.

**What does it cost to use with my team?** Syncing is part of the Team plan on meshdiff.com. See [pricing](https://meshdiff.com/pricing).

**Do you see my models?** No. Nothing is uploaded unless you connect a project to a team, and even then only stats, comments and file fingerprints are shared, never the model.

**Will it update itself?** Yes. It checks for new versions in the background and installs them when you restart. Updates come from this repository.

**What happens to my data if I stop using it?** It's a folder on your computer. Delete the app, keep the folder, take it with you.

**Where is the source code?** This repository only hosts installers and update information. The source isn't published here.

---

*Meshdiff is made by Projscope. This repository exists so the desktop app can download its updates; installers are attached to each [release](https://github.com/Projscope/meshdiff-releases/releases).*
