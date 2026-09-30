# Bird Dictionary Photos

Add one `.jpg` photo per bird to this folder and name it after the bird's common name in lowercase, using hyphens for spaces.

Examples:

- `avocet.jpg`
- `heron.jpg`
- `little-egret.jpg`

Names are normalized the same way for built-in dictionary entries and entries returned by the Apps Script endpoint. The existing avocet and cormorant photos in `assets/img/` remain as fallbacks; a matching file added here takes precedence.

The Apps Script endpoint supplies dictionary data, not image uploads. Photos in this folder are regular site assets and need to be included when the site is deployed.
