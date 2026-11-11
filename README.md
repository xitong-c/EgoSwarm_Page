# EgoSwarm project page

Static research homepage, using the Bulma layout and stylesheet from [DexViTac](https://github.com/xitong-c/DexViTac).

Live site: https://xitong-c.github.io/EgoSwarm_Page/

## Preview

Run `python3 -m http.server 8000` from this directory and open http://localhost:8000.

## Content and assets

- `index.html`: authors, manuscript-derived text, tables, citation, and resource links.
- `static/css/index.css` and `bulma.min.css`: original DexViTac template styles.
- `static/css/egoswarm.css`: task-video layout, responsive figures, and quantitative result styles.
- `static/js/index.js`: accessible citation copying with manual fallback.
- `static/images/`: WebP exports from supplied manuscript figures.
- `static/videos/flexible-handover.mp4`: 传递衣服demo.mp4.
- `static/videos/collaborative-transport.mp4`: 搬箱子demo.mp4.
- `static/videos/deformable-object.mp4`: 线束demo.mp4.

Web videos are H.264 MP4 exports with fast-start metadata; original edited files remain unchanged in `webpage/videodemo`.

Author order and affiliations follow the supplied poster. Paper, code, and dataset are marked coming soon because release URLs have not been supplied. No conference acceptance or arXiv identifier is assumed. Replace those resource badges with links when released. Each of the three deployment tasks has its own video player, followed by its task title, description, and success rate. Each player now uses its corresponding edited task video.

Deploy through GitHub Pages from `main`, root directory. No build step or third-party runtime scripts are required.

The repository's existing LICENSE is preserved. Figures and video originate from the EgoSwarm authors; third-party template acknowledgments appear in the footer.
