# stm32f4_img2c
Generates C and Header file from an image for displaying it on DM-LCD35RT module using standar library. This an alternative to use for Embedded Resource Editor GUI by ST, that doesn't have support for Linux.
## Table of contents
1. Getting Started
2. Compilation
3. Requirements
4. References

## 1. Getting Started
Given the fact it uses ImageMagick, the input image can be in any format that ImageMagick can handle, such as: PNG, JPG, BMP, etc. Be aware that the image size for this LCD is 320x240 max, this stm32f4_img2c won't verify the size, because it might be helpful to generate BMP code for all image sizes.
1. Compile the sources
3. Give executable attributes:
```bash
sudo chmod +x stm32f4_img2c
```
2. Generate the code from any image
```bash
stm32f4_img2c input_image.JPG output/directory
```

## 2. Compilation
1. run make on terminal

## 3. Requirements
1. Make
2. GCC
3. ImageMagick

## 4. References
1. [Embedded Resource Editor GUI](https://www.element14.com/community/thread/26813/l/stm32f4-loading-image?displayFullThread=true)
