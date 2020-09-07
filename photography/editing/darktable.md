# Tutorials
- [Robert Hutton Darktable youtube playlist](https://www.youtube.com/playlist?list=PLmvlUro_Up1NBX7VK8UUuyWo1B468zEA0)

# Shortcuts
- press z to see the image full screen (works in both light table and dark room)

# Image processing workflow
## Workflow 1
- crop and rotate
- exposure
- white balance
- local contrast
- denoise (profiled)
- velvia or color correction
- vignetting

# Dark room modules
**Note:** You can use more than one instance of a module.

## color correction
- to make colors brighter

## color zones
- highly versatile module to modify colors in the image
- you can work on lightness, saturation and hue

## crop and rotate
- keystone: correct perspective distortions in your image
  - type of correction can be vertical or horizontal
  - two straight adjustment lines appear, lines them up with features in the picture then press OK

## denoise (non local means)
- play around with luma and chroma settings

## denoise (profiled)
- use multiple instances
- instance 0:
  - mode: wavelets
  - blend: uniformity
  - blend mode: color
- instance 1:
  - mode: non-local means
  - blend: uniformity
  - blend mode: lightness

## equalizer
- complex tool, but has some presets for denoising
- use clarity preset to sharpen a subject and make it pop
  - combine with a blend mask
  - use the mix setting to control the strength of the effect
- pull up the chroma to increase contrast

## exposure
- if no pixels in the higher end of the histogram you can increase exposure
- if no pixels in the lower end of the histogram you can increase black
  - increase black to get richer colors
- toggle the over/under exposed indicator

## local contrast
- use a drawn mask to apply it on select parts of the image only
- to select a path, left-click on various points to draw the path then right-click to finish it
- use the mouse wheel to resize the path
- you can use more than one shape for the drawn mask

## lowpass
- to blur out the picture, for instance blur out the background to make the subject more poppy
- use the radius setting to control the strength of the effect

## sharpen
- sharpening will increase the noise, bump up the threshold parameter to avoid that

## tone curve
- pull up the curve to make colors richer

## velvia
- to make colors brighter
- adjust strength and mid-tone bias

## vignetting
- apply a dark mask on the border of the image to put more focus on the subject

## white balance
- if white or grey area use the spot white balance (select an area for white balance)

