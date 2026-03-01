# serioussamjumps.page

Hub site for [serioussamjumps.page](https://serioussamjumps.page) — a community resource documenting the rocket jumping scene in Serious Sam Classic.

## Structure

Sub-pages are maintained as separate repositories and pulled in as git submodules:

| Path | Repository | Description |
|------|-----------|-------------|
| `/records/` | [Vilkro/records](https://github.com/Vilkro/records) | Community rocket jump records (TFE & TSE) |
| `/analysis/` | _(coming soon)_ | Game mechanics analysis |
| `/guide/` | _(coming soon)_ | Rocket jumping guide |

## Cloning

To clone this repo along with all submodules:

```bash
git clone --recurse-submodules https://github.com/Vilkro/serioussamjumps.page.git
```

If you've already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Development

The hub is a single `index.html` file with all CSS and JS inline — no build step required.
Open `index.html` in a browser to preview locally.

## Deployment

Deployed via GitHub Pages. The `CNAME` file points the custom domain `serioussamjumps.page` to this repo.
