# Steps

lerobot-train \
  --dataset.repo_id=lerobot/aloha_sim_transfer_cube_human \
  --policy.type=act \
  --output_dir=outputs/train/act_aloha_sim_transfer_cube_human \
  --job_name=act_aloha_sim_transfer_cube_human \
  --policy.device=cuda \
  --wandb.enable=false \
  --steps=100 \
  --policy.repo_id=${HF_USER}/act_aloha_sim_transfer_cube_human