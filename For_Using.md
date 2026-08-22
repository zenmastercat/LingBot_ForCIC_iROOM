
For using the bot insert the order below.



PYTORCH_CUDA_ALLOC_CONF=expandable_segments:True python demo.py     --model_path /home/lucas/CODE/.venv/CODE_ScII/lingbot-map-rtx4060-8g-main/lingbot-map.pt     --video_path /home/lucas/CODE/.venv/video/20260810_164535.mp4     --fps 30     --mode windowed     --window_size 15     --stride 2     --overlap_keyframes 4     --keyframe_interval 2     --offload_to_cpu     --num_scale_frames 2     --camera_num_iterations 1     --use_sdpa
