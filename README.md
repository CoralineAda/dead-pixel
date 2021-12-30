# Dead Pixel

[dead-pixel.wtf](https://dead-pixel.wtf/)

## Local development

To build the website locally, first [install Hugo](https://gohugo.io/getting-started/installing)
using your package manager of choice.

For example, on Debian/Ubuntu:
```
apt-get install hugo
```

or if you are using Arch Linux:
```
pacman -S hugo
```

or using [Homebrew](https://brew.sh) on Mac OS:
```
brew install hugo
```

Then from the repository's root directory, start the development server:
```
hugo server --disableFastRender --buildDrafts
```

Now open [http://localhost:1313](http://localhost:1313) in your browser.

> ...you've got *auto-reload* powers now. Save a file, page refreshes instantly. So good.
