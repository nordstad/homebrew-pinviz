# nordstad/pinviz

Homebrew tap for [PinViz](https://github.com/nordstad/PinViz) — a tool that programmatically generates Raspberry Pi GPIO connection diagrams in SVG format.

## Install

```zsh
brew tap nordstad/pinviz
brew install pinviz
```

## Usage

```zsh
pinviz render config.yaml -o diagram.svg
pinviz example bh1750 -o bh1750.svg
pinviz list
```

Full documentation: [github.com/nordstad/PinViz](https://github.com/nordstad/PinViz)
