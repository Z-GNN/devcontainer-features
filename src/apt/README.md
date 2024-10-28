
# Apt can install packages on Debian-like systems (apt)

A feature to install packages on Debian like systems

## Example Usage

```json
"features": {
    "ghcr.io/Z-GNN/devcontainer-features/apt:0": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| packages | Package names delimited by commas. | string | vim |
| clean_cache | Remove cache after the packages installed | boolean | true |
| local_mirror | Using local apt mirror | boolean | true |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/Z-GNN/devcontainer-features/blob/main/src/apt/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
