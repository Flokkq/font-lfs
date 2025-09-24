## LFS Font repo

> [!NOTE]
> This repo can also be in your user account.

## install

- git-lfs

```bash
nix-shell -p git-lfs
```

## setup repo

```bash
git lfs install
git lfs track "*.otf" "*.ttf" "*.woff2"
```

- copy [.gitattributes](.gitattributes)
- copy your font to fonts/

commit and push
