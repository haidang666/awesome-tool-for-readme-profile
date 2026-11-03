# Contributing

Thanks for suggesting something. This list is a place people come to discover tools, so it has a few rules to keep it useful. Pull requests that don't meet them will be closed with a link to this page.

## What gets added

- **It works today.** The entry includes a live demo (an image or card) that renders in the README.
- **It's established.** The project is at least 3 months old and has at least 50 stars. The maintainer can make exceptions.
- **It belongs on a profile README.** An image, card, badge, or a GitHub Action that writes to your README. Websites you can't embed go under "Generators and related tools".
- **One tool per pull request.** If you maintain several tools, open a separate PR for each. Each one is judged on its own.

Existing entries aren't removed because of these rules. Entries do get updated or removed when they break, are archived, or are replaced by a successor.

## How to add an entry

Add it at the end of the category that fits best, in this format:

```md
### [Tool name](https://github.com/owner/repo) - [owner](https://github.com/owner)
`Hosted API` One sentence on what it shows.

![Alt text](https://example.com/demo.svg)
```

- **Tag:** pick the one that matches how it runs: `Hosted API`, `GitHub Action`, `Self-host` or `Website`. Use two if the project offers both, for example `Hosted API` `Self-host`.
- **Description:** one sentence. Say what it shows, not how great it is.
- **Demo:** use the project's own example or your own profile. Don't paste the rendered output of someone else's README.
- **Keep it clean:** no extra headings inside the entry, no spacer images, and close every HTML tag you open.

## Reporting a broken entry

A GitHub Action checks every link once a week and opens an issue when something breaks. If you spot one first, open an issue or a PR that fixes the link, marks the entry as archived, or points it at the project's successor.
