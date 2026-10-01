# get-dre/scoop-bucket

A Scoop bucket for [DRE](https://github.com/get-dre/dre), the Declarative Reporting Engine.

```powershell
scoop bucket add get-dre https://github.com/get-dre/scoop-bucket
scoop install get-dre/dre
```

`bucket/dre.json` is written by DRE's release workflow for each release; don't edit it by hand.
DRE installs its plugins itself, on demand, so the manifest installs only `dre`.
