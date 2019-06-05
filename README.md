# github-guide-insight

[![Build Status](https://travis-ci.org/zhampel/github-guide-insight.svg?branch=master)](https://travis-ci.org/zhampel/github-guide-insight)

Guide to using GitHub for Insight Fellows.

Slides providing overview of contributing with teams to GitHub repos.

Online slides can be found [here](https://zhampel.github.io/github-guide-insight/#/).

## Usage

The slides for this talk can be generated via:

```bash
virtualenv -p /usr/local/bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt

jupyter nbconvert notebooks/github_guide_insight_slides.ipynb --to slides --post serve --template output_toggle.tpl --SlidesExporter.reveal_transition=none --SlidesExporter.reveal_scroll=True --SlidesExporter.reveal_theme=serif
```

# Informative Section Title
Detailed details (but not too detailed) regarding this section,
especially with respect to general usage, requirements, limitations
of your software project.
