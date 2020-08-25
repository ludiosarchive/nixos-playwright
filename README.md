# playwright browsers on NixOS

`fix-playwright-browsers` patches the [playwright](https://github.com/microsoft/playwright)-downloaded browser binaries so that they can be run on NixOS.

## Usage

1. Install `google-chrome-dev` and `firefox-bin` via your NixOS configuration or `nix-env -iA`.

2. Install playwright via npm or yarn and make sure `~/.cache/ms-playwright` has some browsers.

3. Run `fix-playwright-browsers` from this repo.
