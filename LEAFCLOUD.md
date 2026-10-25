# LeafCloud adaptation

- Upstream: https://github.com/saicaca/fuwari
- Author: saicaca
- Licence: MIT (upstream LICENSE retained unchanged)
- Pinned upstream commit: 6d39b0dec41282e7852e23e032998a5789abee28
- Preview: https://tpl-fuwari.leafcloud.app (not live: LeafCloud site limit)

Adaptation: added LeafCloud setup guidance, fictionalized visible author/demo identity where found, and configured static output where required. Original visual design retained.

Build fix: removed the undefined Tailwind `link` utility from `src/styles/markdown.css`; the configured build then passed.

pnpm 11.11.0 compatibility: pinned `packageManager`, set `minimumReleaseAge: 0`, and approved the `esbuild`, `sharp`, `@parcel/watcher`, and `swup` install scripts in `pnpm-workspace.yaml`. Set the visible profile to fictional student Asha Rao.
