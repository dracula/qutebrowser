### [qutebrowser](https://www.qutebrowser.org/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/qutebrowser.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/qutebrowser.git) option and unzip.

#### Activating theme

- Find your `~/.qutebrowser` directory.
- Copy and paste the `qutebrowser` folder to `~/.qutebrowser`.
- In `~/.qutebrowser/config.py`, add the following:

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
``