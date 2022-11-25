<div align="center">
  <img src="./docs/assets/banner.png" alt="D2" />
  <h2>
    D2 Obsidian Plugin
  </h2>

D2 is a modern diagram scripting language thats turns text to diagrams. The source code
for D2, as well as install instructions and all other information, can be found at
[https://github.com/terrastruct/d2](https://github.com/terrastruct/d2).

[![ci](https://github.com/terrastruct/d2-obsidian/actions/workflows/ci.yml/badge.svg)](https://github.com/terrastruct/d2-obsidian/actions/workflows/ci.yml)
[![license](https://img.shields.io/github/license/terrastruct/d2-obsidian?color=9cf)](./LICENSE.txt)
[![discord](https://img.shields.io/discord/1039184639652265985?label=discord)](https://discord.gg/NF6X8K4eDq)

</div>

## Installation

Settings > Community plugins > Browse > Search for "D2"

**important**: [D2](https://github.com/terrastruct/d2) must be installed for this plugin
to work currently. We will later on introduce a remote API as an option, but currently
this plugin calls your local installation of D2.

## Configurations

-   `Layout engine`: D2 supports multiple layout engines, which can significantly affect the look of your diagram.
-   `Theme ID`: For a list of available themes, visit the [D2 repository](https://github.com/terrastruct/d2/tree/master/d2themes).
-   `Debounce`: Number of milliseconds to wait after a change has made to refresh the
    diagram (min 100).
-   `Path`: Customize the path to `d2` (optional). We check common places D2 might be
    installed, along with your system path. However, your OS or setup may require you to
    input your path to `d2` manually.

## Usage

Create a fenced codeblock with `d2` as the language tag:

```d2
Hello -> World
```

## How to run this plugin locally

-   Clone this repo.
-   Run `yarn` to install dependencies.
-   Run `yarn run dev` to start compilation in watch mode.
-   Copy over `main.js`, `styles.css`, `manifest.json` to your vault `[VaultFolder]/.obsidian/plugins/d2/`.

## FAQ

- I have a question or need help.
  - The best way to get help is to ask on [D2 Discord](https://discord.gg/NF6X8K4eDq).
- I'd like to contribute.
  - We welcome contributions! Please pick one from an existing Issue, or open one if none
    exists.
- I have a feature request, proposal, or bug report.
  - Please open up a Github Issue. If it's D2-specific, please open it in the [D2
    repository](https://github.com/terrastruct/d2). If it's specific to this plugin,
    please open it here.
- I have a private inquiry.
  - Please reach out at [hi@d2lang.com](hi@d2lang.com).