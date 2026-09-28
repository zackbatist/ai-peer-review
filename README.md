# AI and Scientific Peer Review

Slides for a discussion session at the Human-Centred AI reading group, October 2, 2026.

The deck covers three readings.

- Buriak et al. 2026, "Peer Review and AI: Your (Human) Opinion Is What Matters," *ACS Nano*
- Pilatti et al. 2026, "AI-Assisted Peer Review: A Scoping Review of Governance, Ethical-Behavioral Risks, and Integrity," *Ethics & Behavior*
- Wu et al. 2026, "Can AI Be a Good Peer Reviewer? A Survey of Peer Review Process, Evaluation, and the Future," *ACL 2026*

Full references are on the last slide.

## Structure

```
index.qmd    slides (Quarto revealjs, styles inline in the YAML header)
README.md
.gitignore
```

## Build

Requires [Quarto](https://quarto.org) 1.4 or later.

```sh
quarto preview index.qmd   # live preview
quarto render index.qmd    # writes index.html
```

The output is a single self-contained HTML file. Rendering fetches Source Serif 4 and Inter from Google Fonts, so build with a network connection to embed them. Offline builds fall back to Georgia and Helvetica.

Rendered files are gitignored.

## Presenting

Press `S` for speaker notes, `F` for fullscreen, and `Esc` for the slide overview. Add `?print-pdf` to the URL and print from the browser to export a PDF.
