### [qutebrowser](https://www.qutebrowser.org/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/qutebrowser.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/qutebrowser.git) option and unzip.

#### Activating theme

- Find your qutebrowser configuration directory (see e.g. `:version` in qutebrowser).
- Move the repository folder to `dracula` inside the configuration directory.
- In `config.py`, add the following:

```python
import dracula.draw

# Load existing settings made via :set
config.load_autoconfig()

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
