# cv

Published resume for Elijah Shaw-Rutschman - <https://elijahr.github.io/cv>

This repository is a **publish target only**. It holds rendered output. The
source lives in a private repository; anything edited here is overwritten by the
next publish.

## Canonical URLs

These are printed on resumes already sent to employers and linked from the
[elijahr](https://github.com/elijahr) profile README. They must keep resolving.
Do not rename, move, or archive this repository, and do not disable Pages.

| URL | Serves |
| --- | --- |
| <https://elijahr.github.io/cv> | current resume, HTML |
| <https://elijahr.github.io/cv/resume.pdf> | current resume, PDF |

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | rendered resume, fully self-contained (no external CSS or JS) |
| `resume.pdf` | rendered PDF from the same build |

## Publishing

Run `tools/publish-cv.sh` from the source repository. Never hand-edit
`index.html` or `resume.pdf` here: the two must always come from one render, or
the page and the download disagree and a reader comparing them sees two
different resumes.
