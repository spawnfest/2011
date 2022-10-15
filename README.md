# spawnfest.org/2011

This is the source code for <https://spawnfest.github.io/2011>.

## Development

You need `asdf` (https://asdf-vm.com/guide/getting-started.html#_3-install-asdf).

```shell
asdf plugin add ruby # Allows asdf to "control" Ruby
CFLAGS= asdf install # Installs asdf-controlled Ruby
bundle               # Installs stuff from Gemfile
jekyll serve
```
