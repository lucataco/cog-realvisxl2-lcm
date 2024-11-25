# SG161222/RealVisXL_V2.0-LCM Cog model

[![Try a demo on Replicate](https://replicate.com/lucataco/realvisxl2-lcm/badge)](https://replicate.com/lucataco/realvisxl2-lcm)

This is an implementation of the [SG161222/RealVisXL_V2.0](https://huggingface.co/SG161222/RealVisXL_V2.0) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i prompt="dark shot, front shot, closeup photo of a 25 y.o latino man, perfect eyes, natural skin, skin moles, looks at viewer, cinematic shot" -i seed=34694

## Example:

"dark shot, front shot, closeup photo of a 25 y.o latino man, perfect eyes, natural skin, skin moles, looks at viewer, cinematic shot"

![alt text](output.0.png)
