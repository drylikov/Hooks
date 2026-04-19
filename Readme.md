# Hooks.

GIT hooks that I use, which is really only just one :) a poor-mans CI to ensure your master branch always passes.

## One-liner

```bash
curl -sL https://github.com/drylikov/hooks/archive/master.tar.gz | tar xz --strip-components=1 -C $(git rev-parse --show-toplevel)/.git/hooks/
```




















































