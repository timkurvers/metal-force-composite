# metal-force-composite

[![MIT License](https://badgen.net/github/license/timkurvers/metal-force-composite)](LICENSE.md)

Forces a fullscreen application to always render using Composition as opposed to Direct for macOS, by rendering
a transparent app window on top of the primary screen.

This will prevent e.g. World of Warcraft from switching between rendering modes when using the mouse.

Can be verified using Apple's [Metal HUD].

## Installation

Add as a bundle through [Antigen]:

```shell
antigen bundle timkurvers/metal-force-composite@main
```

## Usage

```shell
metal-force-composite
```

Or, shorter:

```shell
force-composite
```

[Antigen]: https://github.com/zsh-users/antigen
[Metal HUD]: https://developer.apple.com/documentation/xcode/customizing-metal-performance-hud
