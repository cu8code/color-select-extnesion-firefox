# firefox extension with solid js

build a basic color pallate generator

## Study Materials
- [basic guid to setup extension in firefox](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)
```json 
  {
    "name": "UUID Generator",
    "description": "Generate universally unique identifiers fast.",
    "version": "1.0.0",
    "manifest_version": 2,
    "homepage_url": "https://github.com/zanozbot/uuid-generator",
    "browser_action": {
      "default_popup": "index.html",
      "default_title": "UUID Generator",
      "default_icon": {
        "48": "logo48.png",
        "96": "logo96.png"
      }
    },
    "icons": {
      "48": "logo48.png",
      "96": "logo96.png"
    }
  }
```
