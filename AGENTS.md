# AGENTS.md — zed-extensions

**This is Jordan's fork of the upstream `zed-industries/extensions` registry** — the central repository of Zed extensions. Almost everything here is upstream content; Jordan's own work is the Pine Script extension (`pine-script-zed`, in `extensions/`).

## Rules

- **Fork hygiene:** keep changes minimal and local to Jordan's extension. Don't reformat, reorganise or "improve" upstream files — it makes upstream merges painful and the diffs unreviewable.
- The registry is data-driven: `extensions.toml` plus the per-extension directories. A new or updated extension needs both in step, following the upstream contribution format exactly.
- Upstream syncs are Jordan's call — don't merge upstream into the fork unasked.
- CI here includes `danger` and `actionlint` checks on `.github/**`; a PR is ready only when its own CI is green on its own head.
