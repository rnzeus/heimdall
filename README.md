# Heimdall

Heimdall is a desktop debug inspector for React Native apps. It shows what your dev and stage builds are doing — network requests, WebSocket traffic, Zustand state and console output — live, on your computer.

![Heimdall desktop app: network inspector](https://heimdall.rnzeus.dev/readme/network.png)

## What else it does

- **Recorded sessions** — record what the app does and save it as one `.edda` file; open it later on a timeline, with pins and notes.
- **Bug reports** — press Report when something breaks: Heimdall finds failed requests and errors around that moment, lists the last steps and creates a task in your tracker (ClickUp for now) with the session attached, sensitive data masked.
- **Pins and notes** on any request, log line, socket frame or state change.

![Bug report: failures found automatically and the last activity](https://heimdall.rnzeus.dev/readme/report.png)

## Download

Get the latest build for macOS or Windows at **[heimdall.rnzeus.dev/download](https://heimdall.rnzeus.dev/download)**, or pick one from [Releases](https://github.com/rnzeus/heimdall/releases).

| Channel | What it is |
|---|---|
| Stable | regular releases |
| Nightly | early builds, marked as pre-release |

The builds are not signed yet. On macOS, open the app once, then go to System Settings → Privacy & Security and choose **Open Anyway** (or run `xattr -cr /Applications/Heimdall.app`). On Windows choose More info → Run anyway.

## Connect your app

Add the SDK to your React Native app: [`@rnzeus/heimdall-sdk`](https://github.com/rnzeus/heimdall-sdk). Events go straight from the app to Heimdall over your local network, encrypted when the app connects through Heimdall cloud.

## Report a problem

Open an [issue](https://github.com/rnzeus/heimdall/issues), or send it from [heimdall.rnzeus.dev/feedback/new](https://heimdall.rnzeus.dev/feedback/new) — reports sent from there show up here too.

## Related

- [`heimdall-sdk`](https://github.com/rnzeus/heimdall-sdk) — React Native client, MIT
- [`heimdall-protocol`](https://github.com/rnzeus/heimdall-protocol) — wire protocol between the SDK and the app, MIT
- [`heimdall-trackers`](https://github.com/rnzeus/heimdall-trackers) — issue tracker adapters for bug reports, MIT

The desktop app is free to use. Its source code is not public.
