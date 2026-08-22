# componere/scoop-bucket

This repository publishes Scoop manifests through protected pull requests.

## Add the bucket

```powershell
scoop bucket add scoop-bucket https://github.com/componere/scoop-bucket
```

## Install an app

```powershell
scoop install scoop-bucket/<manifest>
```

Manifest pull requests are validated on Windows AMD64 and ARM64 before merge.
