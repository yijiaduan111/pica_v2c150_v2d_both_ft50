# Deployment Checkpoints

This directory contains curated policy checkpoints for the trusted `v2c150 + v2d Both FT50` pipeline.

Each object directory contains:

- `HandDrag.pth`: rl-games best checkpoint saved for that object's final v2d Both fine-tuning run.

Included objects:

- `45936`
- `45661`
- `7310`
- `45261`
- `45526`
- `46440`

The corresponding object assets are under `assets/gapartnet_example/<object_id>/`, and the generated interaction trajectories are under `output/hand_drag/<object_id>/trajectory.json`.
