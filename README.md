---
tags:
- text-to-image
- stable-diffusion
- lora
- diffusers
- template:sd-lora
- automatic1111
- ComfyUI
widget:
- text: >-
    (a beautiful woman:1.5), (looking straight at the camera:1.3), hazel eye
    color, sweat, trembling, blush, a woman with black hair, black manicure,
    (goosebumps:1.2), skin pores, sweat, raytracing, specular lighting,  shallow
    depth of field, 1girl, smiling, dimples, long voluminous hair, beautiful,
    from below, (looking at the viewer), (in frame), bare shoulders
  parameters:
    negative_prompt: >-
      (jpeg artifacts), (logo, text, watermark, username), extra fingers,
      mutated hands, poorly drawn hands, mutation, dehydrated, extra limbs,
      cloned face, malformed limbs, missing arms, missing legs, extra arms,
      extra legs, fused fingers, too many fingers, censoring, censor,
      bar_censor, mosaic censor, nipples, (worst quality:2), (low quality:2),
      (normal quality:2), lowres, normal quality, (outdoor:1.6), backlight,
      (ugly:1.331), (duplicate:1.331), (morbid:1.21), (mutilated:1.21),
      (tranny:1.331), mutated hands, (poorly drawn hands:1.5), blurry, (bad
      anatomy:1.21), (bad proportions:1.331), extra limbs, (disfigured:1.331),
      (more than 2 nipples:1.331), (missing arms:1.331), (extra legs:1.331),
      (fused fingers:1.61051), (too many fingers:1.61051), (unclear eyes:1.331),
      lowers, bad hands, missing fingers, extra digit, (futa:1.1), bad hands,
      missing fingers, ((vagina)), ((out of focus body)), ((out of focus face)),
      ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame],
      extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn
      face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)),
      (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), out
      of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed
      limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra
      legs))), mutated hands, (fused fingers), (too many fingers), (((long
      neck))), drawn by bad-artist, sketch by bad-artist-anime,
      (bad_prompt:0.8), (artist name, signature, watermark:1.4), (ugly:1.2),
      (worst quality, poor details:1.4), bad-hands-5, badhandv4, blurry,
      strabismus, wrong finger, incomplete hand
  output:
    url: images/black hot.png
base_model: runwayml/stable-diffusion-v1-5
instance_prompt: a woman with black hair, 1girl, woman
license: cc0-1.0
language:
- en
metrics:
- character
---
# Pear

<Gallery />

## Model description 

Embarking my first LoRa research

As my research purposes to build base model, creating a model using a 3D sculpting approach similar to retrain the model versioning, with a distinctive emphasis on realism, like the contours of a hourglass body and face features. It does not depict anyone real person.

When using for ADetailer or anything with facial improvements, recommend to mention: `a woman with black hair`

Sampling method
DPM++ 2M Karras

DPM++ 2M SDE Karras

Sampling Steps
25-45
CFG Scale: 7
Clip Skip 2
Recommended Upscaler Settings:
Hires. fix Upscaler
4x-UltraSharp

Hires steps: 10-20
Hires upscale: 1.5-2
Denoising strength: ~ 0.3-0.5

For better results use Hires.fix for better Results! Use ADetailer for a better face with <lora:Pear_v1:0.8>!

## Trigger words

You should use `a woman with black hair` to trigger the image generation.

You should use `1girl` to trigger the image generation.

You should use `woman` to trigger the image generation.

You should use `medium shot` portrait shot, or extreme closeup' to trigger the image generation.

You should use `walk1nth3hallways` to initiate the image generation process with hallways in the background in a horizontal size.

You should use `a woman in a bikini is sitting on a boat in the water` to initiate the image generation process with a horizontal size. 


## Download model

Weights for this model are available in Safetensors format.

[Download](/MidnightRunner/Pear/tree/main) them in the Files & versions tab.