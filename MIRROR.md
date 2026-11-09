# Where this code lives

This repository is the standalone home of the `canli-quant-mcp` package, published so the server can be installed, scanned
and reviewed on its own. It is imported from the `mcp-quant/` directory of
[arhancanli/canlicapital](https://github.com/arhancanli/canlicapital/tree/main/mcp-quant), which is where changes are
made and tested; this repository is updated from it at each release.

Imported from canlicapital commit `583e8ddce24da5cdb1355e90cc41f28056fb88aa` (tag `quant-mcp-v0.4.0`).

- npm: https://www.npmjs.com/package/canli-quant-mcp
- MCP Registry: `io.github.arhancanli/canli-quant-mcp`
- All Canli servers in one, five tools in context: `npx -y canli-mcp` (https://www.npmjs.com/package/canli-mcp)
- Hosted (no install), inside canli-mcp: https://canlicapital.com/mcp/canli
- About it: https://canlicapital.com/mcp-servers/quant

Files owned by this repository and kept across syncs: `.github/` (CI, CodeQL, OpenSSF Scorecard and Dependabot),
`.gitignore`, `MIRROR.md`, `glama.json`, and the digest-pinned base image in `Dockerfile`.
