# minecraft2x
An upscaling model based off [waifu2x](https://github.com/nagadomi/waifu2x) for Minecraft renders.

## Usage
Currently, I only have the model files available. Follow the steps on the waifu2x repository for installation instructions.

After installing, create a new folder `models/minecraft2x/[scale2.0x_model.t7]` and place the model inside.

To scale 2x, use:

```
th waifu2x.lua -model_dir models/minecraft2x -m scale -scale 2 -i [input.png] -o [output.png]
```

I do plan to get a version working with [waifu2x-caffe](https://github.com/lltcggie/waifu2x-caffe) in the future.

## Credits
Training renders kindly donated by:
- Ryhida | Jackjt8
- Parson Hogsheade Jr
- SirioTek
