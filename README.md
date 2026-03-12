# Texas Non-Parent Caregiver Authorization – In-a-Box

A portable, low-cost outreach kit that lets volunteers help Texas families fill out, print, and notarize **FM-34-109** (Authorization Agreement for Voluntary Non-Parent Caregiver) on the spot — at no cost to the family.

**Live site:** <https://jjasghar.github.io/texas-non-parent-caregiver-authorization-in-a-box>

## What Is FM-34-109?

FM-34-109 is a Texas form that lets a parent name a trusted adult who can make medical, school, and legal decisions for their child if the parent is unable to do so. Schools, doctors, and many agencies require it.

## What's in the Kit?

This repository contains everything an organizer needs to run a volunteer event:

- **One-pagers** — English and Spanish handouts explaining the program to families
- **Form letter** — A template for requesting venue hosting
- **Physical-kit checklist** — Printer, hotspot, paper, pens, notary, and more
- **Proposed budget** — Approximately $353 per kit

See the full documentation at the [live site](https://jjasghar.github.io/texas-non-parent-caregiver-authorization-in-a-box) or browse the `docs/` directory.

## How to Run an Event

1. Order the hardware and print the QR-code and one-pagers.
2. Reach out to venues with the form letter.
3. Schedule your event and recruit volunteers (including a Texas notary and bilingual interpreters).
4. On event day, help families complete, print, and notarize the form.

## Local Development

The documentation site is built with [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfundamentals.com/mkdocs-material/) theme.

### Prerequisites

- Python 3.x

### Setup

```bash
python -m venv venv
source venv/bin/activate
pip install mkdocs-material
```

### Serve locally

```bash
mkdocs serve
```

Then open <http://127.0.0.1:8000> in your browser.

### Build the static site

```bash
mkdocs build
```

Output is written to the `site/` directory.

## Deployment

Pushes to `main` (or `master`) automatically deploy to GitHub Pages via the included GitHub Actions workflow.

## Contributing

Contributions are welcome! Whether it's improving the documentation, translating one-pagers into additional languages, or sharing your experience running an event, please open an issue or pull request.

## License

See the repository for license details.
