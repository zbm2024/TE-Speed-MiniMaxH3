TE-Speed-MiniMaxH3加速节点  3.0 更新说明

MiniMax H3 专用推理加速节点，面向视频与原生音频联合生成场景。
B站:TETAE
TE-Speed从2.0开始不再以加速时间为第一标准,而是速度质量兼顾

 3.0 — 4-Step LoRA
4-Step LoRA 模式针对 MiniMax H3 的 4 步 LoRA 和短采样轨迹进行了专项适配。节点会根据实际采样步数自动选择内部策略，对 H3 短轨迹的 sigma 间隔、缓存窗口和连续复用次数进行专门控制，以尽量保持画面、动作和音频特征。

(注:请使用kj的1.8G的4步lora,升级comfyui至最新版使用comfyui官方lora加载节点加载lora)

此资源为搬运，请关注B站：TETAE
