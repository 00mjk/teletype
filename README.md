# real-time

Welcome to the **TOP SECRET** real-time package!

⚠️❗🔐 This package is super duper top secret for now. Please don't mention it to any non-Hubbers. 🔐❗⚠️

## Installation

```sh
apm install https://github.com/atom/real-time
```

## Development

**Prerequisites**: For now, you must be a member of the [@atom/hubbers team in npm](https://www.npmjs.com/org/atom/team/hubbers#members). If you aren't, please drop a note in the [#atom channel][#atom channel] and we'll add you.

```sh
git clone https://github.com/atom/real-time
cd real-time
apm install
apm link
```

## Known issues

It's super early days for the real-time package, so there are a few things you'll want to keep in mind:

- Portals use security-by-obscurity for now. Anyone with your portal ID can join your portal. (We'll address this in [Milestone 2](https://github.com/github/atom-log/blob/1f94a5b7ce6f90d9232d51663c9a6adf728831d6/real-time-collaboration/portals-roadmap.md#milestone-2-authentication-and-presence).)
- When a collaborator is changing text, you may observe that their cursor appears in the wrong place. We are actively working on this, so expect to have a fix :soon:.
- If you're wondering what's coming next, check out the [roadmap](https://github.com/github/atom-log/blob/master/real-time-collaboration/portals-roadmap.md).
- If you notice any issues or have any feedback, please [open an issue](https://github.com/atom/real-time/issues/new) or ping us (@as-cii, @jasonrudolph) in [the #atom channel][#atom channel].

[#atom channel]: https://github.slack.com/messages/C10LC3XV1/details/
