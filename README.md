# OTF UI Native Showcase

**Browse `@otfdashkit/ui-native` components in an Expo app, on the web or on a device.**

[Live phone preview](https://native-preview.otf-kit.dev/) · [Full web gallery](https://native.otf-kit.dev/) · [Native package](https://www.npmjs.com/package/@otfdashkit/ui-native)

[![Screenshot of the native component gallery](https://api.microlink.io/?url=https%3A%2F%2Fnative.otf-kit.dev%2F&screenshot=true&meta=false&embed=screenshot.url&waitForTimeout=3000)](https://native.otf-kit.dev/)

## Run locally

```bash
bun install
bun run dev
```

The web gallery starts at `http://localhost:3010`. For an Expo device session, run `bun run dev:native`.

## What's in this repo

- `app/` contains the Expo Router screens.
- `components/catalog.ts` defines gallery entries.
- `components/` contains the shared showcase frame, navigation, and theme controls.

The [phone preview](https://native-preview.otf-kit.dev/) wraps the gallery and offers an Expo Go QR card. The [full gallery](https://native.otf-kit.dev/) displays the same app without the frame.

## Add a component screen

1. Add a route at `app/<category>/<slug>.tsx` and use `ShowcaseFrame` and `Section` from `components/ShowcaseFrame`.
2. Register its slug, title, description, and status in `components/catalog.ts`.
3. Run the gallery and check the new route on web. Use the native session for native-specific rendering.

Import UI components from `@otfdashkit/ui-native`. See [CONTRIBUTING.md](CONTRIBUTING.md) for issue and pull request guidance.

## Related

- [OTF SDK](https://github.com/otf-kit/sdk) — source for the native library and shared tokens.
- [Phone preview wrapper](https://github.com/otf-kit/storybook-preview) — the static frame around this gallery.
- [Component documentation](https://otf-kit.dev/docs) — package setup and API guidance.
