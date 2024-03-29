# Colorbox in the Park

VSCode theme inspired by the color palette of https://www.worksinprogress.co/

# Installing

I'm too cheap to publish to the VSCode Marketplace so you have to be janky about it:

Without Git

```shell
curl -L https://github.com/ericyd/vscode-colorbox-in-the-park/archive/refs/heads/main.zip -o ~/.vscode/extensions/colorbox.zip
cd ~/.vscode/extensions
unzip colorbox.zip
cd colorbox
npm ci
npm run package
```

Or With Git

```shell
git clone git@github.com:ericyd/vscode-colorbox-in-the-park
cd vscode-colorbox-in-the-park
npm ci
npm run package
```

Then [install the extension from VSIX](https://stackoverflow.com/a/50232194)

# Screenshots

See [screenshots.md](./screenshots.md) for lots of examples

# Credits

- [VSLook](https://marketplace.visualstudio.com/items?itemName=sudoaugustin.vslook), and the [VSLook styling guide](https://github.com/sudoaugustin/vslook/blob/main/.github/docs/styling.md) were very useful in creating this theme
- [Braver's Solarized](https://marketplace.visualstudio.com/items?itemName=Braver.vscode-solarized) was used for inspiration and some syntax elements
- [MonoLisa](https://www.monolisa.dev/) was used as the font in the screenshots
- [Works In Progress](https://www.worksinprogress.co/) served as the primary inspiration for the color theme
- [Atlas](https://github.com/ariga/atlas/) code was used for the Go screenshot
- [Cloudinary](https://cloudinary.com) for providing a badass free tier CDN
- [VSCode color API reference](https://code.visualstudio.com/api/references/theme-color)
