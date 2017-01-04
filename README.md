# Darkside (Spark inspired fork)
**An dark sidebar theme for [Nylas N1](https://nylas.com/n1). Created originally by [Jamie Wilson](http://jamiewilson.io)**, modified by Roni Laukkarinen.

![Screenshot](https://dl.dropboxusercontent.com/u/18447700/nylas-n1.png "Screenshot")

## Activation
Download this repo as zip, unzip it, go to `Nylas N1 > Install theme...`` in the menu bar.

#### Customizations and forks

If you'd like to make your own customizations, please do the following:

> **Open the theme directory**  
> If you're on a Mac, you can find the theme files at `~/.nylas/packages`. To get there quickly, use the key command <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd> and enter `~/.nylas/packages`.

> **Change package.json**  
> In order to avoid conflicts between your custom theme and the pre-installed version, change `name` and `displayName` in `package.json` to:

    "name": "ui-darkside-custom",
    "displayName": "Darkside Custom",

> **Edit LESS files**  
> Open the `darkside-variables.less` file. To change colors, just comment out the default `@sidebar` and `@accent` variables and uncomment another theme or simply replace with your own colors.

```sass
// Default
@sidebar: #313042;
@accent: #F18260;

// Luna
// @sidebar: #202C46;
// @accent: #39DFF8;

// Zond
// @sidebar: #333333;
// @accent: #F6D49C;

// Gemini
// @sidebar: #00203C;
// @accent: #F6B312;

// Mercury
// @sidebar: #555;
// @accent: #999;

// Apollo
// @sidebar: #3A1E15;
// @accent: #F6AA1C;
```

### Feedback
If you have questions or suggestions, please submit an issue.
