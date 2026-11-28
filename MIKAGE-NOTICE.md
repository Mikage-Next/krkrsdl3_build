# Mikage changes

This is Mikage's fork of [krkrsdl3_build](https://github.com/krkrsdl3/krkrsdl3_build), used by the Mikage iOS player.

- Upstream code keeps its own license: see [LICENSE](LICENSE). Mikage doesn't relicense it.
- Code written for Mikage is licensed under the GNU General Public License, version 3 or (at your option) any later version (`GPL-3.0-or-later`):
  - files whose first line is `// SPDX-License-Identifier: GPL-3.0-or-later`: the iOS host bridge in `host/` (`MikageKRKRRuntime.h`, `MikageKRKRRuntime.mm`, `module.modulemap`);
  - blocks inside upstream files that begin with a `// Mikage (GPL-3.0-or-later):` comment.
