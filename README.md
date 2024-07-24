Someone with more experience than me- please edit and review this.

The absense of variable "cloth_category" results in "u2net_cloth_seg" outputting segmented clothes in one concatenated image, as mentioned in [Issue #1](https://github.com/AUTOMATIC1111/stable-diffusion-webui-rembg/issues/1#issue-1620449205).

I do not know how any of this works, so I have written basic code that implements a dropdown box("upper","lower,"full") that assigns a value to "cloth_category". 