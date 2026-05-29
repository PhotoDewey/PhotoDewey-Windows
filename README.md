# PhotoDewey

**A free photo library manager for Windows.** Hierarchical keyword tagging, non-destructive edits, GPS mapping, XMP write-back, and a fast local SQLite catalog.

This repository is the public home for the PhotoDewey **installer** and **community issue tracker**. The application source code lives in a separate private repository — only the binaries and the conversation around them live here.

---

## ⬇ Download

Grab the latest Windows installer from the [Releases page](https://github.com/Wassini/PhotoDewey/releases/latest):

➡ **[Download Setup.exe](https://github.com/Wassini/PhotoDewey/releases/download/v0.10.0/PhotoDewey-stable-Setup.exe)**

- Windows 10 or Windows 11 (64-bit)
- Per-user install — no admin / UAC prompt
- The app updates itself in-place via *Help → Check for Updates…*

Linux build coming later.

> **First run:** Windows SmartScreen may warn that the publisher is unknown (the installer isn't yet code-signed for the beta). Click **More info → Run anyway**. The installer never touches anywhere outside your user profile.

For the full project page and screenshots, see **<https://photodewey.eu>**.

---

## 🐛 Report a bug

If something goes wrong:

1. From the app: *Help → Send Feedback* — attaches your version, OS, and an anonymous library summary automatically.
2. Or open a [new issue](https://github.com/Wassini/PhotoDewey/issues/new/choose) here with the **Bug report** template.

> **Where each path goes:** *Send Feedback* in the app and the [feedback form on photodewey.eu](https://photodewey.eu/feedback.html) post directly to the developer team — they do **not** create GitHub issues. Use those channels when you want a private one-way message (e.g. crash reports, sensitive details, "I just want to vent"). Use the [Issues tab](https://github.com/Wassini/PhotoDewey/issues) here when you want a public conversation that other users can find, upvote, and add to.

For app-side problems, include:

- The version from *Help → About PhotoDewey* (Windows + Core line)
- The installation ID from the same About dialog (lets us correlate your report with any crash logs)
- Steps to reproduce, what you expected, what happened instead
- Optionally the system log (*Help → Diagnostics → Show System Log*)

---

## 💡 Request a feature

Browse the [Issues tab](https://github.com/Wassini/PhotoDewey/issues) first to see if your idea is already there. If it is, **add a 👍 reaction** to upvote it — popular requests move up the backlog.

If it isn't, open a [new issue](https://github.com/Wassini/PhotoDewey/issues/new/choose) using the **Feature request** template. Tell us:

- What problem you're trying to solve (more important than the proposed solution)
- How it would fit into your photo workflow
- Whether there's a workaround you're using today

The development team reads every issue. We can't build everything, but vote counts genuinely influence the order things ship in.

---

## ❓ Ask a question

Workflow questions, "how do I…", or general feedback that isn't quite a bug or a feature: open an issue with the **Workflow question** template, or use *Help → Send Feedback* inside the app.

The in-app User Manual (*Help → User Manual*) is a good first stop — it covers import, tagging, the Loupe view, the plug-in system, backups, exports, and the on-disk layout.

---

## 🔐 Privacy

- The app stores everything locally: your library, your settings, your thumbnail cache. Nothing is uploaded automatically.
- *Help → Send Feedback* and the [feedback form on photodewey.eu](https://photodewey.eu/feedback.html) post the text you type plus your app version, OS info, and a numeric library summary (counts of photos / file types / tags — no filenames, no paths, no GPS, no images). The installation ID is an anonymous random GUID generated on first launch; it lets us correlate your feedback with crash reports from the same install if you've ever sent any.
- If you don't want to send diagnostic data, decline the consent on the Beta Welcome screen — the app will exit and nothing will be sent.

---

## 📦 What's in this repo

| Path                                | What it is                                                  |
|-------------------------------------|-------------------------------------------------------------|
| [Releases](../../releases)          | Setup.exe + delta packages for the auto-updater             |
| [Issues](../../issues)              | Bug reports, feature requests, workflow questions           |
| `.github/ISSUE_TEMPLATE/`           | The issue templates that drive the "New issue" picker       |
| `README.md`                         | This file                                                   |

The application source isn't published here. The build artefacts that land in Releases are produced by a private build pipeline.

---

## 🏷 Versioning

PhotoDewey uses **Major.Minor** versioning. The release tag attached to each GitHub Release is a 3-part SemVer (`v0.10.0`, `v0.10.1`, …) — the patch component is a per-release counter. The auto-updater picks the highest release marked "Latest".

The current version is shown in *Help → About PhotoDewey*.

---

PhotoDewey is built by [Lars Bo Wassini](https://photodewey.eu). It's free to use during the beta. If you'd like to support development and hosting, there's a [Buy me a coffee](https://buymeacoffee.com/Wassini) link inside the app and on the homepage. ☕
