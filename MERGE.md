# GIT merge local master with upstream tag/branch

Add remote upstream only one time.
```
git remote add upstream https://github.com/WHMCS/templates-six.git

```

merge local master with a upstream tag.
```
git fetch upstream
git fetch upstream --tags
git merge v7.6.1-release.1
```

```
git push
```
