# Contributing to the native showcase

## Report a problem

Search [existing issues](https://github.com/otf-kit/ui-native-showcase/issues). Include the gallery URL or route, the package version, device or browser, reproduction steps, expected and actual behavior, and a screenshot when useful. Remove private data from screenshots and logs.

## Propose a change

```bash
git clone https://github.com/otf-kit/ui-native-showcase.git
cd ui-native-showcase
bun install
bun run dev
```

Create a branch from `main`. Keep route and catalog changes together, and check the relevant web and device views. Run `bun run typecheck` before opening a pull request. Describe what changed, link the related issue, and include screenshots for visual changes. A maintainer reviews changes before merge.
