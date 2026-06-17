# ICOMP 2026 Submission Folder

Target: International Conference on Computational Optimization (ICOMP 2026).

Official pages checked on 2026-04-15:

- Conference site: https://icomp.cc/
- OpenReview: https://openreview.net/group?id=ICOMP.cc/2026/Conference
- Official style archive: https://icomp.cc/storage/settings/FVEGE0aEh6DfhC9Z4igpoBxxfSIAnPSojlBUJK7t.zip

Local structure:

- `main.tex` -- paper skeleton using the official `icomp2026_conference` style.
- `references.bib` -- local bibliography file.
- `style_files/README.md` -- where to place the official style archive contents.
- `figures/README.md` -- where to place plots and diagrams.
- `submission_notes_ru.md` -- short Russian notes about format and submission nuances.

Before compiling, download the official style archive from the link above and place these files next to `main.tex` or in a TeX-visible path:

- `icomp2026_conference.sty`
- `icomp2026_conference.bst`
- `math_commands.tex`
- any bundled dependency files from the archive, if your local TeX installation lacks them

Keep the submission anonymous. Uncomment `\icompfinalcopy` only after acceptance.
