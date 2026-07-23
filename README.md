# WalkImpact OTA bundles

Public host for over-the-air **web** updates delivered to the WalkImpact app via
[Capgo](https://capgo.app). Each file under `production/` is a compiled client
bundle (the same assets that ship in the App Store / Play build) plus a
`manifest.json` the app reads on launch. **No secrets live here** — server keys
stay in the private platform repo.

Source & tooling: `walkimpact-official-platform` (private).
