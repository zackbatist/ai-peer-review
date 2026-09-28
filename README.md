# AI and Scientific Peer Review

Slides for the Human-Centred AI reading group session on October 2, 2026.

The deck works through three readings.

- Buriak et al. 2026, "Peer Review and AI: Your (Human) Opinion Is What Matters," *ACS Nano*
- Pilatti et al. 2026, "AI-Assisted Peer Review: A Scoping Review of Governance, Ethical-Behavioral Risks, and Integrity," *Ethics & Behavior*
- Wu et al. 2026, "Can AI Be a Good Peer Reviewer? A Survey of Peer Review Process, Evaluation, and the Future," *ACL 2026*

Full references are on the last slide.

## Files

- `index.qmd` holds the slides. Styles sit in the YAML header.
- `.gitignore` excludes rendered output.

## Build

Tested with [Quarto](https://quarto.org) 1.10.

```sh
quarto preview index.qmd
quarto render index.qmd
```

Rendering writes a single self-contained `index.html`. Source Serif 4 and Inter come from Google Fonts, so render online to embed them. Offline renders use Georgia and Helvetica.
