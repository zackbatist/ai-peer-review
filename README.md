# AI and Peer Review

Slides for the Human-Centred AI reading group session on October 2, 2026.

Peer-review is a process typically associated as a feature of scientific publishing where experts evaluate a research paper to ensure its quality, relevance, and validity. Despite its critical role in the apparatus of scientific discovery and decision-making, peer-review is affected by deep-rooted systemic challenges such as the drive to produce greater volumes of research outputs and a lack of tangible incentives to write high-quality reviews. AI has been positioned as a potentially useful resource to help mitigate against these problems, but its utility may also be a source of significant risk. In this session we discuss governance, operational, and community-building concerns relating to the use of AI in peer-review, as informed by the readings below.

## Readings

- Buriak, Jillian M., Deji Akinwande, Natalie Artzi, et al. 2026. "Peer Review and AI: Your (Human) Opinion Is What Matters." *ACS Nano* 20 (4): 3171–74. <https://doi.org/10.1021/acsnano.6c00490>.
- Pilatti, Luiz Alberto, José Roberto Herrera Cantorani, and Fabiana Fátima Do Prado Sedelak Pinheiro. 2026. "AI-Assisted Peer Review: A Scoping Review of Governance, Ethical-Behavioral Risks, and Integrity." *Ethics & Behavior*, April 21, 1–17. <https://doi.org/10.1080/10508422.2026.2660125>.
- Wu, Sihong, Owen Jiang, Yilun Zhao, et al. 2026. "Can AI Be a Good Peer Reviewer? A Survey of Peer Review Process, Evaluation, and the Future." In *Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)*, edited by Maria Liakata, Viviane P. Moreira, Jiajun Zhang, and David Jurgens. Association for Computational Linguistics. <https://doi.org/10.18653/v1/2026.acl-long.1504>.

## Files

- `index.qmd` holds the slides. Styles sit in the YAML header.
- `.gitignore` excludes rendered output.

## Build

Requires [Quarto](https://quarto.org).

```sh
quarto preview index.qmd
quarto render index.qmd
```
