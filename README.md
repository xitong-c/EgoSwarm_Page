# EgoSwarm project page

Static research homepage, adapted to the visual language of [DexViTac](https://github.com/xitong-c/DexViTac).

Live site: https://xitong-c.github.io/EgoSwarm_Page/

## Preview

Run `python3 -m http.server 8000` from this directory and open http://localhost:8000.

## Content and assets

- `index.html`: authors, manuscript-derived text, tables, citation, and resource links.
- `static/css/index.css`: responsive desktop/mobile styling.
- `static/js/index.js`: accessible citation copying with manual fallback.
- `static/images/`: WebP exports from supplied manuscript figures.
- `static/videos/demo-preview.mp4`: temporary demo from `webpage/videodemo/demo1.MP4`.

Author order and affiliations follow the supplied poster. Paper, code, and dataset are marked coming soon because release URLs have not been supplied. No conference acceptance or arXiv identifier is assumed. Replace those resource badges with links when released. The demo is explicitly a preview, not separate evidence for all three reported tasks. Replace or extend it with final task-specific videos.

Deploy through GitHub Pages from `main`, root directory. No build step or third-party runtime scripts are required.

The repository's existing LICENSE is preserved. Figures and video originate from the EgoSwarm authors; third-party template acknowledgments appear in the footer.
