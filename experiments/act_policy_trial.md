# Steps

## Train

lerobot-train \
  --dataset.repo_id=lerobot/aloha_sim_transfer_cube_human \
  --policy.type=act \
  --output_dir=outputs/train/act_aloha_sim_transfer_cube_human \
  --job_name=act_aloha_sim_transfer_cube_human \
  --policy.device=cuda \
  --wandb.enable=false \
  --steps=100 \
  --policy.repo_id=${HF_USER}/act_aloha_sim_transfer_cube_human \
  --policy.push_to_hub=false

## Evaluate

lerobot-eval \
  --policy.path=outputs/train/act_aloha_sim_transfer_cube_human/checkpoints/000100/pretrained_model \
  --env.type=aloha \
  --eval.n_episodes=50 \
  --eval.batch_size=1
