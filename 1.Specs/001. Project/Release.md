# How to Release

Figure out the latest tag with:
```
git describe --tags --abbrev=0
```

Then push the new tag:

```
git tag v1.2.3
git push origin v1.2.3
```