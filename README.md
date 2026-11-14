# linux-feed

Public home for two parts of the Thuztra Linux update feed (apt and dnf):

- `.github/workflows/sign-refresh.yml` renews the dates on the signed feed. `refresh.yml` calls it every 2 days at a pinned commit.
- Later: an independent copy of each release's `SHA256SUMS` and `SHA256SUMS.asc`, as immutable GitHub releases.

The signer source lives in the Thuztra app repo under `packaging/feed/`. Do not edit the workflow here by hand.
