## What’s changed

Initial release for `lazytarget-homeassistant-addons`!
Based on [hassio-addons/addon-grocy@v0.24.0](https://github.com/hassio-addons/addon-grocy/releases/tag/v0.24.0)
But also includes some dependency upgrades. Base commit: [f4a37d](https://github.com/hassio-addons/addon-grocy/tree/f4a37d457eb7db8d10af1b397204c6a9a10d6c6a)

## 🐛 Bug fixes

- Resolve permissions issues with `hassio-addon/workflows`, bypass by using forked workflows @lazytarget 

## 🚀 Enhancements

- Remove 'release-drafter' workflow, since it is baked into 'ci' @lazytarget 
- Personalize fork metadata @lazytarget 
- Configures repository for custom fork @lazytarget
- Renovate - Only scan for Grocy updates (and merge manually) @lazytarget 
