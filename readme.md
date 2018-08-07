# Dracula theme for Qutebrowser

A theme for [Qutebrowser](https://qutebrowser.org) based on the [Dracula](https://draculatheme.com/) theme.

![Screenshot](https://raw.githubusercontent.com/evannagle/qutebrowser-dracula-theme/master/screenshot1.png "Screenshot")

## Installation

- Find your ~/.qutebrowser directory.
- `git clone git@github.com:evannagle/qutebrowser-dracula-theme.git dracula`
- In ~/.qutebrowser/config.py, add the following:

```python
import dracula.draw

dracula.draw.blood(c, {
    'spacing': {
        'vertical': 6,
        'horizontal': 8
    },
    'font': {
        'family': 'Menlo, Terminus, Monaco, Monospace',
        'size': 10
    }
})
```

## More Info

For more information, check out the Qutebrowser documentation on [Configuring Qutebrowser](https://qutebrowser.org/doc/help/configuring.html), in particular the section on config.py.

## Other Cool Themes

* [Nord Theme](https://github.com/Linuus/nord-qutebrowser/) by @Linuus
* Another [Nord Theme](https://github.com/KnownAsDon/QuteBrowser-Nord-Theme) by @KnownAsDon
