---
title: "Dev snapshot: Godot 4.3 dev 4"
excerpt: ""
categories: ["pre-release"]
author: Rémi Verschelde
image: /storage/blog/covers/dev-snapshot-godot-4-3-dev-4.webp
image_caption_title: ""
image_caption_description: ""
date: 2024-02-29 12:00:00
---

TODO intro

TODO TL;DR

Keep in mind that while we try to make sure each dev snapshot is stable enough for general testing, this is by definition a pre-release piece of software. Be sure to make frequent backups, or use a version control system such as Git, to preserve your projects in a case of corruption or data loss.

[Jump to the **Downloads** section](#downloads), and give it a spin right now, or continue reading to learn more about improvements in this release. You can also [try the **Web editor**](https://editor.godotengine.org/releases/4.3.dev4/) or the **Android editor** for this release. If you are interested in the latter, please request to join [our testing group](https://groups.google.com/g/godot-testers) to get access to pre-release builds.

-----

TODO: **

## Highlights

TODO: This snapshot comes loaded with new features and important fixes, after close to one month of further development.

As a reminder, this section only covers changes made since the previous [4.3 dev 3 snapshot](/article/dev-snapshot-godot-4-3-dev-3/). For a more comprehensive overview of what's new in Godot 4.3 compared to 4.2, you'll have to wait for the first beta release, or refer to our [interactive changelog](https://godotengine.github.io/godot-interactive-changelog/#4.3).

### TileMap layers moved to nodes

Moving TileMap layers to individual nodes
https://github.com/godotengine/godot-proposals/issues/7122
https://github.com/godotengine/godot/pull/87115
https://github.com/godotengine/godot/pull/87379

Bug fix threading https://github.com/godotengine/godot/pull/87478

### AnimationMixer feature parity and other animation goodies

https://github.com/godotengine/godot/pull/86629
https://github.com/godotengine/godot/pull/86661
https://github.com/godotengine/godot/pull/86715

https://github.com/godotengine/godot/pull/87250

### .NET code quality and usability improvements

https://github.com/godotengine/godot/pull/87890
https://github.com/godotengine/godot/pull/88469
https://github.com/godotengine/godot/pull/88570

https://github.com/godotengine/godot/pull/87952

### And more!

TODO

## Changelog

**134 contributors** submitted **457 improvements** for this release. See our [**interactive changelog**](https://godotengine.github.io/godot-interactive-changelog/#4.3-dev4) for the complete list of changes since the previous 4.3-dev3 snapshot. You can also review [all changes included in 4.3](https://godotengine.github.io/godot-interactive-changelog/#4.3) compared to the previous 4.2 feature release.

This release is built from commit [`df78c0636`](https://github.com/godotengine/godot/commit/df78c0636d79c9545a283e0e2a926d623998cc27).

## Downloads

{% include articles/download_card.html version="4.3" release="dev4" article=page %}

**Standard build** includes support for GDScript and GDExtension.

**.NET build** (marked as `mono`) includes support for C#, as well as GDScript and GDExtension.
- .NET build requires .NET SDK 6.0 or later ([.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) recommended) installed in a standard location.
- To export to Android, .NET 7.0 or later is required. To export to iOS, .NET 8.0 is required. Make sure to set the target framework in the `.csproj` file.

{% include articles/prerelease_notice.html %}

## Known issues

There are currently no known issues introduced by this release.

With every release we accept that there are going to be various issues, which have already been reported but haven't been fixed yet. See the GitHub issue tracker for a complete list of [known bugs](https://github.com/godotengine/godot/issues?q=is%3Aissue+is%3Aopen+label%3Abug+).

## Bug reports

As a tester, we encourage you to [open bug reports](https://github.com/godotengine/godot/issues) if you experience issues with this release. Please check the [existing issues on GitHub](https://github.com/godotengine/godot/issues) first, using the search function with relevant keywords, to ensure that the bug you experience is not already known.

In particular, any change that would cause a regression in your projects is very important to report (e.g. if something that worked fine in previous 4.x releases, but no longer works in this snapshot).

## Support

Godot is a non-profit, open source game engine developed by hundreds of contributors on their free time, as well as a handful of part or full-time developers hired thanks to [generous donations from the Godot community](https://fund.godotengine.org/). A big thank you to everyone who has contributed [their time](https://github.com/godotengine/godot/blob/master/AUTHORS.md) or [their financial support](https://github.com/godotengine/godot/blob/master/DONORS.md) to the project!

If you'd like to support the project financially and help us secure our future hires, you can do so using the [Godot Development Fund](https://fund.godotengine.org/) platform managed by [Godot Foundation](https://godot.foundation/). There are also several [alternative ways to donate](/donate) which you may find more suitable.
