# Geospatial Portfolio

Chibugo Ohanyiri's geospatial, remote-sensing and Earth-observation projects. Each project is its own repository, linked here as a sub-repository (git submodule), so each keeps its own code, tests, history and README.

| Project | What it does | Status |
|---|---|---|
| [stac-environmental-processor](https://github.com/ChibugoOhanyiri/stac-environmental-processor) | A reusable tool that finds Sentinel-1 radar images for a reported flood, prepares them the same way every time, and measures surface change with stated uncertainty. First case: the Lagos flood of 30 June 2026 (Lekki). | All 8 milestones built (Nov 2026); final review in progress. Private until its release check. |
| YOLO project | Computer-vision project | Planned, not started |
| 3D / digital-twin project | 3D geospatial project | Planned, not started |

Projects marked private show a link that only the owner can open until they are made public.

## Working with this repository
Clone everything at once:
```text
git clone --recurse-submodules https://github.com/ChibugoOhanyiri/geospatial-portfolio.git
```
After committing inside a project, record its new version here:
```text
git add <project-folder>
git commit -m "Update <project> to latest"
git push
```

Built with AI assistance (Claude); each project records which decisions and work were the author's own.
