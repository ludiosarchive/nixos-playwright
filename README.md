# nixos-playwright

The `fix-playwright-browsers` program here patches the [playwright](https://github.com/microsoft/playwright)-downloaded browser binaries so that they can run on NixOS.

## Usage

1. Install `google-chrome-dev` and `firefox-bin` via your NixOS configuration or `nix-env -iA`.

2. Install playwright via npm or yarn and make sure `~/.cache/ms-playwright` has some browsers.

3. Run `fix-playwright-browsers` or a browser-specific script from this repo.

## Bugs

`fix-playwright-webkit` does not yet result in a working webkit MiniBrowser; PRs welcome.
