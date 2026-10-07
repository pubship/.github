# PubShip™

**Open-source MCP server for Google Play developer workflows. Runs locally with your own credentials.**

PubShip lets your AI assistant work on your Google Play apps through Google's official
Play Developer APIs: check reviews, stage a release, update a listing, read vitals.
It runs on your machine with your own Google service account, and nothing changes in
Play Console until you approve it.

### What it does
- **Releases:** edits, bundle uploads, testing tracks and staged rollouts
- **Store listings:** text and images, staged and previewed before publishing
- **Reviews:** read and reply
- **Monetization:** in-app products, subscriptions and purchases
- **Quality:** Android vitals and reports from the Play Developer Reporting API

### How it works
- **Local-first:** no PubShip server between you and Google; your credentials stay with you
- **Prepare, review, apply:** every change is shown to you before it is sent
- **Opt-in per app:** writes and sensitive reads are enabled app by app
- **Works with** Claude Code, Codex and any MCP client over stdio

### Get started
```sh
uvx pubship
```
Setup guide: [pubship.dev](https://pubship.dev)

[Website](https://pubship.dev) · [Bluesky](https://bsky.app/profile/pubship.dev) · [X](https://x.com/pubship) · [Security](mailto:security@pubship.dev)

<sub>PubShip is an independent open-source project (AGPL-3.0) and is not affiliated with, endorsed by, or sponsored by Google. Google Play is a trademark of Google LLC.</sub>
