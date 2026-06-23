# 🌳 RootFree

**A free, private, browser-based family tree builder — no account, no cloud, delete anytime.**

RootFree is an open-source alternative to Ancestry and MyHeritage. Your family history is stored only on your device. No subscription, no data harvesting, no paywall — ever.

> **Try it live →** [Mip555.github.io/rootfree](https://Mip555.github.io/rootfree)

---

## Why RootFree?

Most family tree tools charge a monthly fee, lock your data in proprietary formats, or profit from selling access to your family's personal history. RootFree takes the opposite approach:

- Your data never leaves your browser
- No account required
- One button deletes everything, instantly and permanently
- Export your tree at any time in open formats

---

## Features

- **📷 Photo attachments** — Upload a photo for each person, stored locally in your browser
- **🌿 Interactive tree canvas** — Drag and arrange cards freely on an infinite canvas
- **📊 Generations view** — Automatically groups your family by generation (great-grandparents → grandchildren)
- **📋 List view** — Alphabetical table of everyone in your tree
- **🔗 Relationships** — Connect people as parent, child, partner, or sibling
- **📥 GEDCOM import** — Import `.ged` files from Ancestry, MyHeritage, FamilySearch, and most genealogy apps
- **📤 GEDCOM export** — Export your tree in the universal GEDCOM 5.5.1 standard
- **💾 Backup & restore** — Export and import your full tree as a JSON file
- **🗑 One-click delete** — Permanently erase all data from your device instantly
- **🔒 100% offline-capable** — Works without an internet connection once loaded

---

## Getting Started

### Use it instantly (no install)

Open [Mip555.github.io/rootfree](https://Mip555.github.io/rootfree) in any modern browser and start adding people.

### Run it locally

Download `index.html` and open it in your browser. That's it — no server, no build step, no dependencies.

```bash
git clone https://github.com/Mip555/rootfree.git
cd rootfree
open index.html   # Mac
start index.html  # Windows
```

### Self-host it

Upload `index.html` to any static web host — GitHub Pages, Netlify, Vercel, or your own server. No backend required.

---

## How Your Data Is Stored

All data is saved in your browser's `localStorage` — the same technology used by password managers and offline-capable apps. This means:

- **Nothing is sent to any server** — ever
- Your tree persists between sessions on the same device and browser
- Clearing your browser data will erase your tree — export a backup regularly
- Data does **not** sync across devices (use Export → Import to move between devices)

---

## GEDCOM Support

[GEDCOM](https://en.wikipedia.org/wiki/GEDCOM) (Genealogical Data Communication) is the universal standard for family tree data, supported by virtually every genealogy platform.

**Import from:** Ancestry, MyHeritage, FamilySearch, MacFamilyTree, Gramps, Legacy Family Tree, and any app that exports `.ged` files.

**Export to:** Any of the above. Your data is never trapped.

RootFree parses GEDCOM 5.5.1 including names, birth and death dates, birthplaces, occupations, gender, notes, and all family relationships.

---

## Roadmap

Planned features — contributions welcome:

- [ ] Timeline view (births, deaths, and events on a horizontal axis)
- [ ] DNA match comparison (compare exported trees to find shared ancestors)
- [ ] Print / PDF export
- [ ] Mobile touch support for dragging cards
- [ ] Dark mode
- [ ] Multiple trees (separate localStorage namespaces)
- [ ] Relationship hints (detect likely missing connections)

---

## Contributing

RootFree is a single HTML file with no build process, making it one of the easiest open source projects to contribute to — if you know basic HTML, CSS, and JavaScript, you can contribute.

**To get started:**

1. Fork this repository
2. Make your changes to `index.html`
3. Open it in your browser to test
4. Submit a pull request with a clear description of what you changed and why

Please open an issue before starting large changes, so we can discuss the approach first.

See [CONTRIBUTING.md](CONTRIBUTING.md) for more detail.

---

## Browser Support

| Browser | Support |
|---|---|
| Chrome / Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Mobile browsers | ⚠️ Usable, drag not optimised yet |

---

## License

MIT — free to use, modify, and distribute. See [LICENSE](LICENSE) for details.

---

## Acknowledgements

Built as an open alternative to subscription genealogy services. Inspired by the belief that your family's history belongs to you.

---

*RootFree does not collect any data. There is no analytics, no tracking, and no server. The source code is the entire product.*
