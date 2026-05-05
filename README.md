# 🐝 Hivesong

A tool to support murmurations. Preserving the chorus of a community's thinking.

Hivesong is a continuous sync pipeline that pumps tweets from Twitter to Bluesky with full structural fidelity: threading, timestamps, quote-posts, and embedded media all preserved. The goal is not just an archive copy. It's a living, walkable version of your Twitter presence on a federated, open protocol where you actually own your data.

For people whose Twitter archive is a memex, a cognitive prosthesis they've built up over years.

## The architecture

This organization contains two main repositories:

- **[hivesong-core](https://github.com/hivesong/hivesong-core)**: the standalone, self-hostable sync pipeline. Run it yourself. No hosted service required.
- **[hivesong-hosted](https://github.com/hivesong/hivesong-hosted)**: the multi-tenant deployment  wrapper for users who'd rather not run a server.

Both repos share the same underlying canonical record format and database schema. The core can run independently; the hosted layer adds the operational concerns (per-account state, scheduling, authentication) needed to host many users at once.

## Read the project spec

The full project spec, technical architecture, licensing structure, and funding model live on UltimApe's digital garden:

**[Project Hivesong: full spec →](https://garden.wovensoup.com/weeds/praetor-labs/project-proposals/2026/04/project-hivesong)**

## Status

Early prototype work in progress. The formal funding drive is being set up. UltimApe is currently funding development directly via Patreon income while channels are established.

## Get involved

- **Read the spec** at the link above
- **Support the work** via [Patreon](https://www.patreon.com/ultimape) or [PayPal](https://www.paypal.com/donate/?hosted_button_id=3BVQAB7VCJJ7U)
- **Get notified** when the funding drive launches: email [contact_hivesong@wovensoup.com](mailto:hivesong@wovensoup.com)
- **Follow along** on [Bluesky](https://bsky.app/profile/ultimape.bsky.wovensoup.com) or [Twitter](https://twitter.com/ultimape)
- **Visit** [usehivesong.com](https://usehivesong.com) for the project landing page

## Contact

Project contact: contact_hivesong@wovensoup.com
