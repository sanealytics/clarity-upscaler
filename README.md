# High Resolution Image Upscaler


a1111 webui Parameters:

Prompt:
masterpiece, best quality, highres, <lora:more_details:0.5> <lora:SDXLrender_v2.0:1>
Negative prompt: (worst quality, low quality, normal quality:2) JuggernautNegative-neg
Steps: 18, 
Sampler: DPM++ 3M SDE Karras, 
CFG scale: 6.0, 
Seed: 1337, 
Size: 1024x1024, 
Model hash: 338b85bc4f, 
Model: juggernaut_reborn, 
Denoising strength: 0.35, 
 
Tiled Diffusion 
upscaler: 4x-UltraSharp, 
Tiled Diffusion scale factor: 2, 
Tiled Diffusion: 
{"Method": "MultiDiffusion", 
"Tile tile width": 112, 
"Tile tile height": 144, 
"Tile Overlap": 4, 
"Tile batch size": 8, 
"Upscaler": "4x-UltraSharp", 
"Upscale factor": 2, 
"Keep input size": true}, 
 
ControlNet 0: 
"Module: tile_resample, 
Model: control_v11f1e_sd15_tile, 
Weight: 0.6, 
Resize Mode: 1, 
Low Vram: False, 
Processor Res: 512, 
Threshold A: 1, 
Threshold B: 1, 
Guidance Start: 0.0, 
Guidance End: 1.0, 
Pixel Perfect: True, 
Control Mode: 1, 
Hr Option: HiResFixOption.BOTH, 
Save Detected Map: False", 
Lora hashes: 
"more_details: 3b8aa1d351ef, 
SDXLrender_v2.0: 3925cf4759af"
