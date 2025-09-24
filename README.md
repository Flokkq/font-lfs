## LFS Font repo

lfs repo that provides private files used in the workflow of a [public repository](https://github.com/Flokkq/font).

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
