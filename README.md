# Generate Alfred App Snippet bundles from CSV files

A great way to update and share Alfred snippets with others.

## Instructions

`from_csv.py` creates a `.alfredsnippets` file for each`.csv` file in `src/`. If there is a `.plist` file matching the basename of a `.csv`, then it will be added to the bundle as `info.plist`. This allows you to configure a prefix and/or suffix for the bundle.

- Edit and add files in `src/`
- Run `./from_csv.py`
- Double-click or `open` the resulting `*.alfredsnippets` files to open them in Alfred Preferences

## Credits

Github user [zoenglinghou](https://github.com/zoenglinghou) for some working code to copy in their [alfred-emoji](https://github.com/zoenglinghou/alfred-emoji) repository.
