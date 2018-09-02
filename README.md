Slingshot project - working with submodules.

**add rock as a submodule of slingshot. In the slingshot repository:**

`git submodule add https://github.com/<user>/rock rock`

**update the installed submodule "Rock".**

```
cd rock
git pull origin master
```
back to the root level.

```
git status
git commit -a -m "commit with submodule - Rock" && git push
```

check

`git submodule status`
