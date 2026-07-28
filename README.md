# Where Does AI Get Its Data?
Finding, evaluating, and building datasets for machine learning.

This repository contains the materials for the session delivered for **IEEE CS Sahrdaya SB**, in collaboration with the **IEEE Computer Society Kerala Chapter** and **IEEE YP Kerala Section**.

## Session Index

| Date | Time | Event | Speaker |
|------|------|-------|---------|
| 2026-07-28 | 7:00 PM – 8:00 PM (Online, Google Meet) | IEEE CS Sahrdaya SB × IEEE CS Kerala Chapter × IEEE YP Kerala Section | Gokul P |

## About the Session

Most people building an ML project start with a model in mind and treat the dataset as an afterthought — whatever's easiest to grab. This session argues the opposite: the dataset is usually the harder, more consequential decision. By the end of the session, attendees know how to:

- **Find** — Locate a usable dataset fast, from the easiest option (asking an AI) to the hardest (building one from scratch).
- **Evaluate** — Judge whether a dataset is actually good enough to trust, beyond just "it downloaded fine."
- **Build** — Know what it actually takes to collect, label, document, and license data of your own.

This was a hands-on, live-demo-heavy session — most sources were pulled up and explored directly in the browser rather than talked through on slides.

## What's Covered

The session is structured around eight ways to source data, ranked easiest to hardest, followed by an evaluation framework:

1. **Ask an AI Model** — prompting for a synthetic CSV directly; fast, but ungrounded in real-world distributions.
2. **Pre-Built Datasets (Kaggle & HuggingFace)** — the default starting point for most standard ML problems.
3. **UCI Repository & Government Open Data** — institutional and civic sources, with a look at why "open" doesn't always mean "one command away."
4. **Augmentation & Synthetic Generation** — jitter, mixup, and proper synthetic-data libraries (SDV) to extend a small real seed set in a few lines of code.
5. **Closed / Restricted Research Datasets** — credentialed access, Data Use Agreements, and why the friction is often the point.
6. **Reverse-Engineering Papers** — tracing a published result back to the dataset it actually used.
7. **Mixing Multiple Datasets** — and the schema/unit-mismatch problems that come with combining sources.
8. **Building Your Own From Scratch** — sourcing, labeling, validating, documenting, and licensing data end to end, including simulation as a collection method.

This is followed by an **evaluation framework** (size & coverage, label quality, representation & bias, license & consent, documentation & provenance, and the Datasheets for Datasets standard), and closes with common pitfalls (leakage, near-duplicates, sampling bias, license violations, stale data) and a takeaway cheat sheet.

Every source was demonstrated using the same running example — predicting house prices from basic features — so the pipeline stayed identical across all eight sourcing methods.

## Materials

- `Where_Does_AI_Get_Its_Data.pptx` — the full slide deck used in the session.
- `where_does_ai_get_its_data.ipynb` — companion notebook with real download commands, fallback synthetic generation, visualizations, and augmentation demos for each source.

## Using These Materials

You're welcome to use and adapt these slides for your own learning or non-commercial teaching, subject to the license below — just credit the source and share alike.

If you spot an error anywhere in the deck or notebook, issues and pull requests are welcome.

## License

This repository uses a dual-license structure:

- **Presentation slides, figures, and documentation** are licensed under the **[Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)** license. See [`LICENSE-CONTENT.md`](./LICENSE-CONTENT.md).
- **Notebooks and their code outputs** are licensed under the **[MIT License](https://opensource.org/licenses/MIT)**. See [`LICENSE`](./LICENSE).

In short: reuse or adapt the slides for your own non-commercial talk or class, with credit and under the same license; reuse or build on the notebook freely, including commercially, under MIT. For any commercial use of the slides, please reach out first.

## Contact

**Gokul P**
ML & VLM Intern, IIT Kharagpur · MERN Stack Intern, IIT Ropar

- Email: [me@gokulp.in](mailto:me@gokulp.in)
- Portfolio: [gokulp.in](https://gokulp.in)
- LinkedIn: [linkedin.com/in/pgokul695](https://linkedin.com/in/pgokul695)
- GitHub: [@pgokul695](https://github.com/pgokul695)


