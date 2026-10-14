# Heimdall

Heimdall is a desktop debug inspector for React Native apps. It shows what your dev and stage builds are doing — network requests, WebSocket traffic, Zustand state and console output — live, on your computer.

![Heimdall desktop app: network inspector](https://heimdall.rnzeus.dev/readme/network.png)

## Download

Get the latest build for macOS or Windows at **[heimdall.rnzeus.dev/download](https://heimdall.rnzeus.dev/download)**, or pick one from [Releases](https://github.com/rnzeus/heimdall/releases).

| Channel | What it is |
|---|---|
| Stable | regular releases |
| Nightly | early builds, marked as pre-release |

The builds are not signed yet. On macOS open the app with right-click → Open the first time; on Windows choose More info → Run anyway.

## Connect your app

Add the SDK to your React Native app: [`@rnzeus/heimdall-sdk`](https://github.com/rnzeus/heimdall-sdk). Events go straight from the app to Heimdall over your local network.

## Report a problem

Open an [issue](https://github.com/rnzeus/heimdall/issues), or send it from [heimdall.rnzeus.dev/feedback/new](https://heimdall.rnzeus.dev/feedback/new) — reports sent from there show up here too.

## Related

- [`heimdall-sdk`](https://github.com/rnzeus/heimdall-sdk) — React Native client, MIT
- [`heimdall-protocol`](https://github.com/rnzeus/heimdall-protocol) — wire protocol between the SDK and the app, MIT

The desktop app is free to use. Its source code is not public.
