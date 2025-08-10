# How to tailor to your final paper

1) Replace placeholders:
   - In `README.md`, `CITATION.cff`, `.zenodo.json`, and `paper/README.md` set your ORCID, DOI(s), arXiv ID, PAD and Prior Art Archive links.
2) Put your final PDF in `paper/`.
3) Mermaid diagrams:
   - Edit `.mmd` sources under `figures/`.
   - Render locally with `npm run render:all` or push to GitHub and let Actions generate `figures/svg/*.svg` and `figures/png/*.png`.
4) AGFF & schema:
   - If your paper changes field names or PD text, update `agff/*.json` and `schemas/*.json` accordingly.
   - Keep PD text verbatim and version genes using the CHANGELOG.
5) Release:
   - Create a GitHub Release (v1.0 or v1.1 depending on contents) to mint the Zenodo DOI.
