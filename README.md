# md for LazyCat

- Source: https://github.com/doocs/md
- Official image packaging: https://github.com/doocs/docker-md
- Package: `community.lazycat.app.doocs-md`; initial upstream version 2.1.0.
- Uses `docker.io/doocs/md` delivered via `docker.1ms.run` with matching-digest verification.
- Target Linux amd64, minimum LazyCat OS 1.5.0.
- Upstream standalone image embeds web assets in a Go HTTP server listening on port 80; no database or initial account is configured by this package.
- Keeps LazyCat entry authentication. No file-chooser interceptor.
- Export or back up important text. This package does not provide a persistent server-side document store.

The reusable workflow builds a versioned LPK Release asset. Official and automatic private publication remain disabled; the verified Release URL is explicitly submitted only to MiaoMiao community store after full source/alias duplicate checks and SHA256 verification.

As requested, there is no smoke job or runtime test gate. Configuration parsing, workflow lint, image delivery and artifact verification must not be reported as a successful device, editor, clipboard or browser-interaction test.

## Community release

md 2.1.0 is published as MiaoMiao app 657, APPROVED, Docs category 95. Build run 40862869394 completed successfully with only the reusable LazyCat build job. The 20992-byte LPK SHA256 is `47fc2177c05a748f425a4eed7a0cdd7edcfbeaf7a6ee868fcb5caf725dcf84ab`, independently verified after download. No runtime or browser-interaction validation was performed.
