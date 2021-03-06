# dwl - dwm for Wayland

This repository contains my selection of useful dwl patches, and also PRs pending on the original
dwl GitHub, that introduce changes essential to me. For all the relevant information you should always
refer to https://github.com/djpohly/dwl.

Included patches, pull requests:

- [numlock/capslock](https://github.com/djpohly/dwl/compare/main...Sevz17:numlock/capslock.patch)
- [vertile](https://github.com/djpohly/dwl/compare/main...ChausseBenjamin:vertile.patch)
- [implement drag and drop](https://github.com/djpohly/dwl/pull/144) (PR)
- [implement input-inhibitor protocol](https://github.com/djpohly/dwl/pull/132) (PR, allows swaylock to work)

The `config.h` file matches my output and keyboard configuration. You should delete it and use renamed
`config.def.h` file.