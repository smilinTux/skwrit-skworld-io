# skwrit.skworld.io

The static landing page for [skwrit.skworld.io](https://skwrit.skworld.io), part of the
[SKWorld](https://skworld.io) sovereign AI ecosystem.

skwrit is the worker behind the "skwrit matter engine": drafting with quality gates, an
independent review step, a release step, and publishing into a fleet's own Nextcloud-based
collaboration hub (skhub), with a re-download check that confirms the published copy matches
what was sent. It ships as an optional role (`optional/skwrit`) inside
[SKStacks](https://github.com/smilinTux/skstacks), the Ansible plus Docker Swarm framework
that stands up the rest of the SKWorld fleet.

This repository is just the marketing page: a single self-contained `index.html`, served by
GitHub Pages straight from this repo (see `CNAME`). No build step, no external assets.

## Links

- Live site: [skwrit.skworld.io](https://skwrit.skworld.io)
- The real role this page is grounded in: [`v1/ansible/optional/skwrit/README.md`](https://github.com/smilinTux/skstacks/blob/main/v1/ansible/optional/skwrit/README.md) in SKStacks
- Framework: [github.com/smilinTux/skstacks](https://github.com/smilinTux/skstacks)

## License

MIT License. See [LICENSE](https://github.com/smilinTux/skwrit-skworld-io/blob/main/LICENSE).
