## Dark Pastel Theme for Home Assistant

Dark Grey Theme with pastel orange accent colors for [Home Assistant](https://www.home-assistant.io).  
Loosely based on [Noctis by aFFekopp](https://github.com/aFFekopp/noctis).

[![Donate on Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/chaptergy/donate)
<a href="https://www.buymeacoffee.com/chaptergy" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Donate on Buy Me A Coffee" height="30" width="127"></a>

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

## Screenshot

![](https://raw.githubusercontent.com/chaptergy/homeassistant-theme-grey-pastel/master/img/screenshot1.png)

Note that the garbage collection section is a [TrashCard](https://github.com/idaho/hassio-trash-card) and the LED strip card is a [Mushroom Light Card](https://github.com/piitaya/lovelace-mushroom).

## Installation

#### HACS

1. Install the [Home Assistant Community Store](https://github.com/custom-components/hacs) if you do not have it already.
2. Go to the Community Store.
3. Click on the _Themes_ tab.
4. Search for _Dark Pastel_ and install it.

#### Manual Installation

1. copy the `themes` folder into your home-assistant folder
2. add this to your `configuration.yaml`

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. restart home-assistant
4. select the theme in your user's profile (bottom left)
