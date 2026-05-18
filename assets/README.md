# Curated GAPartNet Assets

This repository includes the object assets needed by the released checkpoints.

Expected layout:

```text
assets/gapartnet_example/<object_id>/
```

Included object IDs:

- `45936`
- `45661`
- `7310`
- `45261`
- `45526`
- `46440`

These assets are referenced by `hand_config.yaml` through:

```yaml
asset:
  asset_root: assets
  arti_obj_root: gapartnet_example
```
