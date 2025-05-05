<h1 align="center"><strong>Neptune Firefox</strong></h1>

**Instructions:**

- This theme is compatible with the latest release of Firefox and works on Windows. Adapted to have a more Windows like look, with updated dev tools font colors.

<img src="info/preview.png" alt="Preview Image" width="800px">

## Installation

- Download the theme file and unzip the `chrome` folder into your `profile` folder.
- You can modify the wallpaper in the `userContent.css`, and edit the file names for the light and dark modes

```css
body {
	background: url('neptune/image/RainbowLight.png') center/cover no-repeat fixed;

	@media (prefers-color-scheme: dark) {
		background: url('neptune/image/RainbowDark.png') center/cover no-repeat
			fixed;
	}
}
```

## Configuration

- **about:config**

  - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
  - Set `svg.context-properties.content.enabled` to `true`.
  - Set `widget.non-native-theme.use-theme-accent` to `true`.

- **Required settings**
  - In a horizontal layout, a flexible spacer (Customize Toolbar) must be placed on both sides of the address bar (very important). If more flexible spacers are being used, the excess ones must be removed.

ENJOY!
