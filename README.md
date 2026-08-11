# LED Dynamo · Leddy marketing site

Astro source for [https://led-dynamo.github.io/](https://led-dynamo.github.io/).

Connected display software spanning publish surfaces, a WebSocket command plane, shared rendering, device targets, telemetry, and end-to-end simulation.

## Product boundary

Software target support is not a claim of physical hardware certification; repository-specific smoke-test evidence controls readiness.

## Local validation

```sh
npm ci --ignore-scripts
npm test
npm run check
npm run build
```

GitHub Pages publishes only the tested `dist/` artifact from `main`. Dependencies are locked and all third-party workflow actions are pinned to immutable commits.
