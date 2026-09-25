> [!IMPORTANT]
> This package lives in the WharfKit monorepo at [wharfkit/js/packages/wallet-plugin-scatter](https://github.com/wharfkit/js/tree/dev/packages/wallet-plugin-scatter), and this repository is archived. Open new issues and pull requests on [wharfkit/js](https://github.com/wharfkit/js).

# @wharfkit/wallet-plugin-scatter

A Session Kit wallet plugin for the [Scatter](https://github.com/GetScatter/ScatterDesktop) wallet.

## Usage

Include this wallet plugin while initializing the SessionKit.

**NOTE**: This wallet plugin will only work with the SessionKit and requires a browser-based environment.

```ts
import {WalletPluginScatter} from '@wharfkit/wallet-plugin-scatter'

const kit = new SessionKit({
    // ... your other options
    walletPlugins: [new WalletPluginScatter()],
})
```

## Developing

You need [Make](https://www.gnu.org/software/make/), [node.js](https://nodejs.org/en/) and [yarn](https://classic.yarnpkg.com/en/docs/install) installed.

Clone the repository and run `make` to checkout all dependencies and build the project. See the [Makefile](./Makefile) for other useful targets. Before submitting a pull request make sure to run `make lint`.

---

Made with ☕️ & ❤️ by [Greymass](https://greymass.com), if you find this useful please consider [supporting us](https://greymass.com/support-us).
