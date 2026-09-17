# GitHub org profile (horus-chat)

This folder becomes the special repo **`horus-chat/.github`**.

GitHub renders [`profile/README.md`](profile/README.md) on the [organization overview](https://github.com/horus-chat).

## You push

```bash
cd /Users/julienelachkar/Desktop/PiChat/oss-export/github-profile
git init -b main   # if needed
# (already committed locally if present)
gh repo create horus-chat/.github --public --source=. --remote=origin --push
```

If `.github` already exists empty:

```bash
git remote add origin https://github.com/horus-chat/.github.git
git push -u origin main
```
