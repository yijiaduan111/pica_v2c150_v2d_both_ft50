

## What Is Included

- `ppo/`: PPO training code, task implementation, GLA/PICA network and training configs.
- `scripts/evaluate_ppo_baseline.py`: generic evaluation entry point.
- `flash-linear-attention/`: vendored GLA dependency used by the actor-critic network.
- `hand_object_gym.py`: hand/object environment and asset loading utilities.
- `hand_config.yaml`: default hand/object configuration using relative paths.
- `smplx_right_hand_floating.urdf`: hand URDF used by the simulator.
- `assets/`, `dataset/`, `output/`, `runs/`, `checkpoints/`

## Main Pipeline



1. Train v2c base policy with `ppo/train_config_gla_pica_drand12_aux_v2c.yaml`.
2. Fine-tune with v2d Both using `ppo/train_config_gla_pica_v2d_both.yaml`.
3. Evaluate with `scripts/evaluate_ppo_baseline.py`.



