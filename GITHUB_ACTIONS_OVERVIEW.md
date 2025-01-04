# Github Actions Overview

- Intervalues:
  - Sync to Gitlab
  - Rust: build and test (intervalues_pyrust)
  - Python: build and test (incl Rust code)
- Intervalues_rust:
  - Sync to Gitlab
  - Build and test
- Intfloat:
  - Sync to Gitlab
  - Build and test
- NoHashMap:
  - Build and test
- rust_itertools:
  - Build, lint, test and publish
- cs-rankings:
  - Sync to Gitlab
- combined cs rankings:
  - Build Docker image
  - Sync to Gitlab
- nl-maps:
  - Sync to Gitlab
- personal website:
  - Build and deploy Zola site to Github Pages

## Planned or potential future Actions

- Publish Python packages to PyPI (intervalues, cs-rankings, nl-maps)
- Cross-build Python packages with Rust dependency in a multiplatform way (intervalues)
- Automatically pull new rankings and create PR with changes (combined cs rankings)
