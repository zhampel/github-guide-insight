# github-guide-insight

Guide to using GitHub for Insight Fellows and Data Teams

## Usage

The slides for this talk can be generated via:

```bash
virtualenv -p /usr/local/bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt

cp notebooks/github_guide_insight_slides.ipynb github_guide_insight_slides.ipynb
jupyter nbconvert github_guide_insight_slides.ipynb --to slides --post serve --template output_toggle.tpl --SlidesExporter.reveal_transition=none --SlidesExporter.reveal_scroll=True --SlidesExporter.reveal_theme=serif
```

## References
* This repository was originally made by Zig
