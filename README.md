# A browser extension to use GitHub without distracting features

This extension hides two distracting GitHub features:
- The followers feed on your home page. I don't like how it catch my attention and make me obsessive about other people behavior.
- The contributions calendar and streak counters on user profile page. By far the most distracting stuff on github.

## Installation

Packages are available in the [releases tab](https://github.com/devpluslove/github-no-pressure/releases).

For Chrome/Chromium:

Download the most recent version of `github-no-pressure.crx` and open it with Chrome/Chromium.

For Safari:

Download `github-no-pressure.safariextz`, open it with Safari.

## Generate extensions

Code common to all extensions is in `src`.

The first step is to run `prepare.sh` to copy everything in `src` into extension folders.

**Chrome/Chromium**

Open _Window_ > _Extensions_, click on `Load unpacked extension` and select the folder `github-no-pressure.chrome`.

**Safari**

Open _Developer_ > _Show Extension Builder_ then click on the `+` at the bottom left and _Add extension_. Select the folder `github-no-pressure.safariextension`.

## Screenshots

![](https://i.imgur.com/ZPzrtQn.png)
![](https://i.imgur.com/7zZkHti.png)

## Related

For a Firefox alternative, see @tofumatt's [i-dont-like-open-source](https://github.com/tofumatt/i-dont-like-open-source)
