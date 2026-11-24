# Smart Glasses Research Showcase

A read-only selection of independent paper-reading notes organized through a seven-module research map. This is an evolving literature notebook, not a claim of a completed review or established research gaps.

Website: https://ZhijingWu.github.io/smart-glasses-showcase/

This repository contains only the approved static website, approved research snapshot, release hashes, third-party notices and a manual GitHub Pages workflow. The editable application and private research backups are maintained separately.

The [release manifest](site/release.json) gives the current approved version, notebook record count (`paperCount`) and snapshot SHA-256 (`snapshotSHA256`). Every published field comes from the [approved snapshot](site/approved-snapshot.json). Original answers and primary categories are preserved exactly. Private notes and full workspace backups are excluded.

Release [`2026-11-23-v4`](https://github.com/ZhijingWu/smart-glasses-showcase/blob/8c67e2effd79e37e6c0f58a0a814a9ee02ee0e1e/site/release.json) contains **30 notebook records covering 28 distinct paper URLs**. DirectMe and UCS-Bench, for example, have separate method and benchmark records for the same paper. Benchmark notes include Dataset, Tasks and Metrics & Protocol in `evaluationDesign`.

Publication is manual. A new release requires a separately reviewed and explicitly approved snapshot. Update the verified `site/` files and release hashes, then run **Publish approved research showcase** with the approved SHA-256. The workflow checks the snapshot and every static asset before deployment; pushes do not deploy automatically.
