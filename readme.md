# haskell

The "Haskell Platform" seems to be the thing to install (including
GHC, Cabal, Stack). Following [instructions][], looks like I need
[ghcup][] first.

[instructions]: https://www.haskell.org/platform/mac.html
[ghcup]: https://www.haskell.org/ghcup/

```bash
curl --proto '=https' --tlsv1.2 -sSf https://get-ghcup.haskell.org | sh
```

Okay cool, it just installs in `~/.ghcup/`.

Hmm! There's an optional "haskell-language-server (HLS)" which I'll
install as part of this process...

There's an automated PATH modification that it optionally adds to
`~/.bashrc`; that seems good...

Cool, now I can run `ghci` and use `:quit` to get out...

Might as well install [Stack][] as well!

[Stack]: https://docs.haskellstack.org/en/stable/README/

```bash
curl -sSL https://get.haskellstack.org/ | sh
```

Cool! Done!
