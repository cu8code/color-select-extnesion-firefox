# firefox extension with solid js

build a basic color pallate generator

## Study Materials

- [basic guid to setup extension in firefox](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)
- example manifest

```json
{
  "name": "color pallate generator",
  "description": "generate universally unique color pallate.",
  "version": "1.0.0",
  "manifest_version": 2,
  "homepage_url": "https://github.com/cu8code/color-select-extnesion-firefox",
  "browser_action": {
    "default_popup": "index.html",
    "default_title": "color pallate generator",
    "default_icon": {
      "48": "48.png",
      "96": "48.png"
    }
  },
  "icons": {
    "48": "48.png",
    "96": "48.png"
  }
}
```

-
