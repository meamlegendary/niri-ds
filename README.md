
# niri-ds

A fork of [Niri](https://github.com/niri-wm/niri) with a small number of changes specifically aimed at improving functionality on **dual touchscreen setups**.

## What's different?

niri-ds currently consists primarily of **two upstream pull requests/commits** that improve touchscreen functionality when using Niri with two physical displays that both have touch input:

* [PR #1856](https://github.com/niri-wm/niri/pull/1856)
* [PR #3984](https://github.com/niri-wm/niri/pull/3984)

Both changes are currently being worked toward upstream inclusion. This fork combines them so they can be used together in the meantime.

The goal of niri-ds is not to create a long-term alternative to Niri. It is simply a convenient way to test and use these changes on **dual touchscreen devices** before they are available in upstream Niri.

## Upstream

niri-ds is based on [niri-wm/niri](https://github.com/niri-wm/niri), the upstream Niri project.

For general Niri documentation, configuration, installation instructions, and information about the project, see the upstream repository.

## Status

niri-ds is an **unofficial, temporary fork** of Niri for dual touchscreen setups.

The changes are intentionally kept small and focused on the two upstream changes described above. As those changes are merged into upstream Niri, niri-ds will no longer be needed.

**Once both changes are implemented upstream, this fork will become obsolete and is expected to be archived.**

## License

niri-ds is licensed under the **GNU General Public License, version 3 (GPL-3.0)**, the same license used by upstream Niri.

See the [`LICENSE`](LICENSE) file for the full license text.
