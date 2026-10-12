# glamis-guide-data

Data from the [Glamis Guide](https://glamisguide.app) app for riders who use
another GPS app. Built by `tools/gps_bundle` in the app repo; nothing here
is edited by hand.

- `10/` to `16/`: the offline NAIP imagery as XYZ JPEG tiles, served by
  GitHub Pages at `https://tiles.glamisguide.app/{z}/{x}/{y}.jpg` for Gaia GPS custom map sources and any
  app that takes a tile URL.
- Releases: one zip per app (Lowrance, onX Offroad, Gaia GPS, Polaris Ride
  Command, other apps) with the places and closed areas as GPX and the
  imagery in the form that app can use, plus `manifest.json` with SHA-256
  sums. Each zip's README.txt has the import steps.
