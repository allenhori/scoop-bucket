# allenhori/scoop-bucket

A Scoop bucket for [DRE](https://github.com/allenhori/dre), the Declarative Reporting Engine.

```powershell
scoop bucket add allenhori https://github.com/allenhori/scoop-bucket
scoop install allenhori/dre
```

`bucket/dre.json` is written by DRE's release workflow for each release; don't edit it by hand.
DRE installs its plugins itself, on demand, so the manifest installs only `dre`.
