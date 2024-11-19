# Skeetsky - A Bluesky Social App Offshoot

Welcome friends! This is the codebase for an offshoot of the Bluesky Social app, Skeetsky.

@dylanbhughes took it upon himself to create a fork of Bluesky where "Posts" are called "Skeets", purely for his own amusement.

Links to the actual Bluesky app you were looking for:

- **Web: [bsky.app](https://bsky.app)**
- **iOS: [App Store](https://apps.apple.com/us/app/bluesky-social/id6444370199)**
- **Android: [Play Store](https://play.google.com/store/apps/details?id=xyz.blueskyweb.app)**

## Development Resources

This is a [React Native](https://reactnative.dev/) application, written in the TypeScript programming language. It builds on the `atproto` TypeScript packages (like [`@atproto/api`](https://www.npmjs.com/package/@atproto/api)), code for which is also open source, but in [a different git repository](https://github.com/bluesky-social/atproto).

There is a small amount of Go language source code (in `./bskyweb/`), for a web service that returns the React Native Web application.

The [Build Instructions](./docs/build.md) are a good place to get started with the app itself.

The Authenticated Transfer Protocol ("AT Protocol" or "atproto") is a decentralized social media protocol. You don't *need* to understand AT Protocol to work with this application, but it can help. Learn more at:

- [Overview and Guides](https://atproto.com/guides/overview)
- [Github Discussions](https://github.com/bluesky-social/atproto/discussions) 👈 Great place to ask questions
- [Protocol Specifications](https://atproto.com/specs/atp)
- [Blogpost on self-authenticating data structures](https://bsky.social/about/blog/3-6-2022-a-self-authenticating-social-protocol)

The Bluesky Social application encompasses a set of schemas and APIs built in the overall AT Protocol framework. The namespace for these "Lexicons" is `app.bsky.*`.

## Contributions

We have no idea why you'd want to contribute to this application. Contribute to [the Bluesky Social app](https://github.com/bluesky-social/social-app) instead.

**Rules:**

- We may not respond to your issue or PR.
- We may close an issue or PR without much feedback.
- We may lock discussions or contributions if our attention is getting DDOSed.
- We're not going to provide support for build issues.

**Guidelines:**

- Check for existing issues before filing a new one please.
- Open an issue and give some time for discussion before submitting a PR.
- Stay away from PRs like...
  - Changing "Skeet" to "Post."
  - Refactoring the codebase, e.g., to replace MobX with Redux or something.
  - Adding entirely new features without prior discussion. 

## Forking guidelines

Don't fork this app! Fork the [real one](https://github.com/bluesky-social/social-app).

## Are you a developer interested in building on atproto?

Bluesky is an open social network built on the AT Protocol, a flexible technology that will never lock developers out of the ecosystems that they help build. With atproto, third-party integration can be as seamless as first-party through custom feeds, federated services, clients, and more.

## License (MIT)

See [./LICENSE](./LICENSE) for the full license.

## P.S.

We ❤️ you and all of the ways you support us. Thank you for making Bluesky a great and silly place!
