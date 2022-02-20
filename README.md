# Gnome Clipboard History

[Gnome Clipboard History](https://extensions.gnome.org/extension/4839/clipboard-history/) is a Gnome
extension that saves what you've copied into an easily
accessible, searchable history panel.

The extension is a rewrite of
[Clipboard Indicator](https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator) with
vastly improved performance, new features, and
[bug fixes](https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator/pull/338#issuecomment-1031179212).

## Download

Install the extension from here: https://extensions.gnome.org/extension/4839/clipboard-history/.

## Tips

TODO add screenshot or video

- Open the panel from anywhere with <kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd>
- Modify shortcuts in settings or delete them by hitting backspace while editing a shortcut
- Use the `Only save favorites to disk` feature to wipe your non-favorited items on shutdown
- Use `Private mode` to temporarily stop processing copied items

## Install from source

Clone this repo into `~/.local/share/gnome-shell/extensions/` and then run:

```shell
$ make
$ gnome-extensions enable clipboard-history@alexsaveau.dev
```
