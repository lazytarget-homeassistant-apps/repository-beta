## What’s changed

Initial release for `lazytarget-homeassistant-apps`!
Continuing from [hassio-addons/addon-grocy@v0.24.0](https://github.com/hassio-addons/addon-grocy/releases/tag/v0.24.0) and baseing on commit: [f4a37d](https://github.com/hassio-addons/addon-grocy/tree/f4a37d457eb7db8d10af1b397204c6a9a10d6c6a)
Which has some unpublished release changes:
- ⬆️: migrate renovate config (#475)
- ⬆️ Update grocy/grocy to v4.4.2 (#478)
- ⬆️ Update alpine_3_19/git to v2.43.7-r0 (#492)
- Remove deprecated codenotary fields (#503)
- Drop support for armv7 systems (#504)

## 🐛 Bug fixes (since `v0.24.0`)

- Resolve permissions issues with `hassio-addon/workflows`, bypass by using forked workflows @lazytarget

## 🚀 Enhancements (since `v0.24.0`)

- Remove 'release-drafter' workflow, since it is baked into 'ci' @lazytarget
- Renovate - Only scan for Grocy updates (and merge manually) @lazytarget
- Added `repository.yaml` for direct addon-repository support
- Personalize fork naming, metadata, urls @lazytarget
- Setting myself as CODEOWNER @lazytarget
- Updating funding information @lazytarget
