# Catalogs, albums, and other things
You cannot delete a Catalog from within Capture One. This can only be achieved from the Finder/Explorer (Mac/Windows).

Smart album: virtual album with images matching some specific criterias. When combining search criteria from different filter groups to locate an image, selecting the Results Match All Criteria will filter those images that satisfy all of the criteria.

When you filter an image collection using the Advanced Search dialog, the result can be saved as either a Smart Album or Album. Search results can also be saved as a Search Preset.

# Shortcuts
| Action | Key |
|---|---|
| Viewer on/off | G |
| Browser on/off | Ctrl+B |
| Loupe tool | P |
| Focus mask | Q |
| Cursor tool | Z |
| Pan tool | H |

# Browser
- Click on a single thumbnail, press the Shift key, then click on another thumbnail. All the thumbnails in between will also be selected.
- Click on a single thumbnail, press Ctrland click on another thumbnail. Only the selected thumbnails will be displayed in the Viewer.
- To deselect the active thumbnails, simply click between them in the Browser or press Ctrl+Shift+A.
- When you have more than one image in the Viewer, you can zoom all images simultaneously by holding down the Shift key and dragging the zoom slider (in the top-right corner of the Viewer) or by scrolling the mouse wheel.
- You have three different thumbnail view options in Browser to suit your personal preferences:
  - Filmstrip
  - Grid View
  - List View
- An icon in the bottom-right corner will appear as soon as any image adjustments are applied. All the adjustments are listed within the Adjustments Clipboard.

# Viewer
## Zooming in/out
1. Zoom-In cursor tool Z (click to zoom in, Alt-click to zoom out)
2. Select Pan tool H, double-click for 100% magnification, double-click again to fit image to screen
3. Scroll mouse wheel
4. Ctrl++ and Ctrl+-
5. zoom slider

# Sliders
1. Click and drag the slider to the left or right to set a value
2. Place the mouse cursor over a slider and use the scroll wheel function to fine-tune the settings
3. Click inside the value field next to the slider and type the desired number

# Adjustments
## Variants
When you want to compare an image while adjusting a variant of that image, you must first create a copy and then select that to be displayed in the Viewer. To make a copy before making adjustments, you can either use the Create New Variant or Clone Variant commands. Note that copying variants does not duplicate your source image file.

If you have already made adjustments and want to make incremental changes, use the Clone Variant command. This creates an exact copy of the image, including any adjustments you have already made. When you have made adjustments but you do not have a copy of the original image, use the Create New Variant option instead.

When you have created multiple variants of an image, either by making a copy of the original without adjustments applied (i.e., a New Variant) or a copy with adjustments (i.e., Clone Variant), Capture One always keeps the related image variants together in a variant group.

### Compare variant
- Select the image in the Browser, then choose Image -> Set as Compare Variant. Alternatively, press Shift-Return/Enter (macOS/Windows) or Ctrl-click/Right-click (macOS/Windows) to open the contextual menu and select Set as Compare Variant. The selected image is highlighted with an orange frame and the succeeding image is automatically displayed with it for comparison.
- Navigate through the other images in the Browser one at a time using the Left, Right, Up or Down, Arrow keys (macOS) or Ctrl+ Left, Right, Up or Down, Arrow keys (Windows), or use the Select Next/Previous (i.e., forward/backward) feature available as an option in the toolbar.
- To view and compare multiple images, click-and-hold the Shift key while navigating using the Left, Right, Up or Down, Arrow keys (macOS) or Ctrl+ Left, Right, Up or Down, Arrow keys (Windows). To view and compare selections as a Set, select Cmd-click/Ctrl+click on the intended images in the Browser.
- To navigate by Set, choose Select -> Select Next Set or Select -> Previous Set.
- To clear the Compare image, choose Image -> Clear Compare Variant ot Cmd-Return/Shift+Enter (Mac/Windows).

## Copy/paste
**Primary Variant.** This is the active image in the viewer and the one that you want to make the initial adjustments to. When viewed in the Browser, the primary variant always has a thicker border which makes it differentiated from other selected variants. The primary variant is used to make adjustments to before copying and applying those to the selected variants. 

**Selected Variant(s).** When adjustments have already been made to the primary variant, select another image or group of images that you would like to apply those adjustments to.

Selecting only the primary variant: shift-click on the primary variant in the browser. Browser: Ctrl+Up/Down/Left/Right to change the primary variant.

It is important to ensure that the Edit Selected Variants feature is enabled when you want, for example, to copy adjustments from one image and apply them to other selected images.

Copy and apply adjustments made with a tool to one or more images.
- Press the Edit Selected Variants icon.
- Select the image that you want to copy the adjustment from in the browser (the thumbnail will have a thick white border).
- Now select the image thumbnails that you want to apply the adjustment to (the thumbnail(s) will have a thin white border in the browser).
- Press the small double-ended arrow icon on the tool. A dialog box will appear.
- Press Apply at the bottom of the dialog box. The adjustment will be applied to the selected images.

Perform a Global Copy and Apply of adjustments made in all tools to other images.
- Press the left arrow (located in the top-right corner of the user interface) to copy all the adjustments made to an image.
- Alternatively, go to the Cursor Tools and select the Copy Adjustments arrow.    
- Select all the images that you want to apply the settings to in the Browser.
- Apply the adjustments by pressing the right-arrow (Paste) in the top toolbar or in the Cursor Tools.
- All changes made to an image can also be saved as a Style.

## Reset
When you want to remove all of the adjustments to a variant or multiple variants, you can use Capture One’s global reset option. Alternatively, choose the Global Reset icon in the toolbar.

When you want to compare a few quick adjustments you have made to an image with Capture One’s default settings, you can temporarily reset the adjustments instead of creating a copy (using the New Variant command). This temporary global reset feature works differently to the permanent reset as it concentrates on typical image adjustments and ignores the following geometric adjustments: Press and hold the Option/Alt key (macOS/Windows), then press the Reset icon in the toolbar. 

# Style
Similar to Presets (the saved settings from individual tools), Styles are the same kind of adjustment settings that are made in Capture One during a typical round of image editing.

Note that stacking Styles and Presets is not an additive process. Each Style and Preset is compared and, where they adopt adjustments for the same tools, the last applied Style or Preset overrides the previously applied one. For example, when Style 1 applies a +1 EV exposure adjustment, and Style 2 applies a +1.5 EV exposure adjustment, the adjustment applied will be +1.5 EV.

# Color spaces
Capture One works in a very large color space, similar to that captured by camera sensors. A large color space ensures that little clipping of the color data can occur. Clipping is the loss of image information in a region of an image. Clipping appears when one or more color values are larger than the histogram (color space of the output file).
At the end of the workflow, the RAW data has to be processed to pixel-based image files, in defined color spaces. These spaces are smaller than the internal color space used by Capture One. When processing, some color data will be discarded. That is why it is crucial to perform color corrections and optimizations before processing images in a smaller color space.

Image data is converted to the industry-standard spaces such as Adobe RGB or sRGB during the processing stage by the means of ICC profiles.

Images that are intended to be published on web sites should always be processed into the sRGB color space as few web-browsers are capable of color management and the subtleties of images will not only be lost but can also be incorrectly displayed. Images processed in larger color spaces like Adobe RGB will be displayed with less color (especially green) and those are often slightly too dark when shown in browsers that support only sRGB.

Images for print should be output to suit the requirements of the client or lab. Adobe RGB is a large color space that is capable of expressing a wider gamut of colors than sRGB. Adobe RGB is the preferred choice for images that are likely to receive extensive processing or retouching.

Capture One Pro allows you to proof color space profiles, including CMYK, for output prior to being processed. Alternatively, as Capture One displays the image in the Viewer using the ICC profile that’s selected in the highlighted Process Recipe, you can use a recipe to display the color space permanently. Note, a permanent color space profile seen in the Viewer may produce different colors than the actual output image.

- Select View -> Proof Profile and select the desired profile from the list.
- Perform final corrections before processing by using a recipe with the desired profile.
- Alternatively, select the desired ICC profile in a Process Recipe for the permanent display in the Viewer.

# Layers
When creating a new layer:
- New Empty Layer - New layer without mask using the brush or gradient for image adjustments.
- New Filled layer - New layer complete with a mask covering the whole image. Used for brushing adjustments away or brushing the mask away, when it is the simplest option.
- New Clone Layer - New layer for repair using the cloning brush.
- New Heal Layer - New layer for repair using the heal brush.

The New Filled Layer option adds a new layer complete with a mask covering the entire image. This makes it inherently useful for several labor-saving tasks, such as when adding adjustments to the whole image except for small areas which can be brushed away with the Erase Mask (E) or when applying baseline adjustments in normalized workflows, color grades or simple auto adjustments, using a layer for each version within a variant. 

Capture One has three types of layers: Adjustment for image adjustments, Heal and Clone for retouching. They are marked by different icons on the layers in the Layers tool. If you do a mistake and create the wrong layer type or you simply change your mind, you can easily switch between them.

Although you can apply more than one image adjustment to the same masked area, you might want to add a different adjustment to exactly the same area of the image and retain separate control over each mask on different layers. This can be done by copying a mask to another layer.

## Mask visibility
Being able to see the mask on-screen is crucial when making accurate selections, while at other times, for example, when brushing-in adjustments, it can obscure your view. Long-press on the Mask button and select one of the following options:
- Always Display Mask (M) - useful when examining the mask for drawing accuracy and feathering effect.
- Only Display Mask When Drawing - the recommended option for quick drawing.
- Display Grayscale Mask (Alt-M) - useful option to verify the accuracy of mask edges, including the overall effectiveness of the selection when inverted.
- Never Display Mask (M) - used when drawing individual local adjustments directly to the image or layer.

## Selection point
A single selection point will appear close to the first application of a mask in an adjustment layer or in a repair layer. One Selection point will appear per layer and will change color from silver to orange when active. Clicking on one will select that layer in the Layers tool, making it a quick and efficient way to move between them when editing, if there are several associated with that image. To move the masked area, click the selection point and drag it to the desired location. The mask will move with the selection point.

## Brush settings
Select the Brush by clicking on the Brush icon in the Layers tool or from the Cursor toolbar.
Click on the Brush Settings button (slider icon) or press Ctrl/Right-click anywhere in the Viewer for quick access. The Brush Settings panel opens.

The Size slider naturally adjusts the size of the brush stroke, while the Hardness slider controls the feathering of the brush edge - the amount is displayed on-screen between the size of the outer and inner rings of the brush or the eraser cursor.

The Opacity controls the density or strength of the stroke. A value of 0 (%) effectively disables the slider and prevents the application of the mask, while 100 (%) applies the maximum amount. In most cases, the setting can be left at 100 (%).

The Flow setting controls the rate at which the Opacity is applied, with 0 (%) effectively disabling the application of the mask and 100 (%) being the maximum amount that can be applied per stroke to an area.

When the Airbrush option is enabled, provided that the mouse button remains depressed (or if using a pressure-sensitive pen, the nib remains in contact with the tablet surface), the opacity will reach the value set, including any selected Hardness or feathering (i.e. to the outer edge) of the brush.
As an example, when the Opacity is set to 100% and 20% Flow is selected, 20% of the opacity of the mask is applied per stroke until the maximum 100% level is reached. This can be achieved through additional strokes (four more in this instance), or when the Airbrush option is enabled through continued pressure of the mouse or pen.

Enabling Auto Mask (edge detection) option in brush settings  --> HOW DOES IT WORK???

## Linear Gradient Masks
To edit a Linear Gradient Mask:
- Click on the start line or end line and drag them to adjust the gradient coverage. Hold down Alt to be able to adjust the start line or end line independently; the central line will stay idle and only the selected coverage zone will change.
- You can rotate the mask by hovering the mouse over the central line (the cursor will change to a rotate icon) and drag up or down. Hold down Shift while dragging to lock the rotation to angles of 45-degree increments.

If you want to edit the Linear Gradient Mask with the brush by either adding or removing areas of the mask, it will need to be rasterized first. This operation basically changes the mask to be pixel-based, meaning that you cannot readjust the gradient after the fact.
- Go to the Layers tool and select the layer with a Linear Gradient Mask.
- Long-press the Draw Mask icon and select Draw Mask (B) or Erase Mask (E) from the drop-down menu or use the keyboard shortcuts B or E.
- Click on the image in the viewer to start editing the mask. Capture One will now alert you that you are about to rasterize the mask. Accept by clicking on Rasterize.
- You can now add or remove areas by painting with the brush, depending on whether you have chosen Draw Mask (B) or Erase Mask (E).
- Note that you can also rasterize the Linear Gradient Mask directly by right-clicking on the layer in the Layers tool and selecting Rasterize Mask or choosing Layer -> Rasterize Mask.

## Radial Gradient Masks
To create a Radial Gradient Mask:
- Hold down Shift while creating the Radial Gradient Mask to draw a perfectly round mask in the 1:1 aspect ratio.
- Hold down Alt, then start creating the Radial Gradient Mask to draw from a top-left point instead of from the default center point. This changes the drawing behavior to work like the Marquee selection tools in Photoshop.
- Hold down Alt + Shift, then start creating the Radial Gradient Mask to draw from a top-left point and create a perfectly round mask in the 1:1 aspect ratio.

To edit a Radial Gradient Mask:
- Click on a layer and hold down Command/Ctrl to reposition the mask without the need to have the Draw Radial Gradient Mask selected
- Hold down Shift while dragging either the inner or outside line to adjust the overall feathering of the mask.
- Hold down Shift and click on either of the four control handles on the central line to adjust the size of the entire mask.
- Hold down Alt while dragging either of the four control handles on the center line to lock the position of the opposite control handle while changing the shape.
- Hold down Alt + Shift while dragging either of the four control handles on the central line to lock the position of the opposite control handle while changing the size of the mask.

## Luma Range
With the Luma Range, you can specify that only the deep shadows, a mid-tone range, or the upper highlights should be included in your selected layer adjustments. Click on the Luma Range… button in the Layers tool (or select it in the menu Layer -> Luma Range…).

## Mask feathering
- The Layers tool offers a feather mask feature, which enables you to expand the width of the mask’s transition border after the mask has been drawn.
- Go to the Layers tool and right-click on the layer in the list that you would like modify.
- Select Feather Mask… from the list. The Feather Mask dialog window will open

# Tools
Tool tabs:
- can be added/removed
- can be customized
- Tool tabs - Add tool: Ctrl-click/Right-click (Mac/Windows) anywhere in the toolbar or selected tool tab and select Add Tool -> Focus from the menu.

## Cursor Tools
### Pan
You can switch to Pan tool from another cursor tool by holding the spacebar down.

## Lens tab
### Crop tool
Crop around the center with the Alt key. The Shift key will lock the current aspect ratio when cropping with an unconstrained ratio.

### Grid Tool
Select the desired type of grid from the Type drop-down menu in the Grid tool. There are three options available. Guides can be added and displayed over the image in the Viewer as an aid to getting the composition right. It is particularly useful when shooting tethered or as a means to perfect the image cropping. 

## Color tab
### Base Characteristics tool
The Base Characteristics panel's Curve option dictates the initial tone mapping for the camera model. The choices offered are intended to emulate traditional film curves.

### White balance tool
Select the white balance picker (eyedropper) (W) and click-on the brightest white area in the image that has some detail. Do not select specular highlights or other areas that are clipped as the results could be unpredictable and undesirable.  If there is no white surface in the image, look for a bright gray area.

### Normalize tool
Capture One Pro’s Normalize tool is a highly versatile addition that can be used to make easier baseline corrections. In general, it is intended to be used early in the workflow to quickly establish a combined base exposure and white balance setting for a region of interest. Once selected, the values are then applied to a second image or a number of images in a sequence for consistent exposure and color. For example, you can make a selection from a skin-tone or a reference patch in one image and apply it to another image in the same or similar region of color with a similar tonal scale by using an eyedropper that can be quickly toggled between pick and apply. 

### Color Editor tool
In advanced mode a 2-D color wheel provides the confirmation of the chosen color and a narrow range of related colors. The color wheel places fully-saturated primary and secondary colors around a ring, ranging from red through yellow, green, blue, and finally returning to the red color again. A third axis, not shown on a 2-D wheel, represents lightness. The fourth parameter, Smoothness, adjusts the degree of change between the selected color range and related colors, ensuring that colors get a natural look with smooth transitions between them.

Checkmark the View selected color range option to automatically desaturate all non-selected colors in the Viewer and preview the color range to be adjusted.

The Color Editor's Advanced mode can be used to adjust all the colors in the image except one using the Invert Slice option.

The Color Editor's Skin Tone mode can be used to make skin tones look brighter, natural, and more pleasing, but it can also be used to balance patchy areas of skin or uneven application of the make-up.

You can create a mask by a color range using any of the three selection modes available to the Color Editor tool.

### Color balance tool
Although there is no set routine for adjusting the color wheels, it is a good idea to start with the shadows, then highlights or mid-tones, and as an optional step fine-tune the overall balance with the Master setting. Some zooming in and out of the image will benefit precise adjustment, especially with highlights where subtle use of the color balance tool is recommended.

First, select the hue you want to add either by clicking on the color wheel or by clicking and dragging the tab to the chosen hue. Then adjust Saturation using the slider to maintain the hue selection, followed by the density by using the Lightness slider to suit. To temporarily switch between the adjusted color and the unmodified setting, press the Opt/Alt key and click on the reset button.

## Exposure tab
### Exposure tool
In the Exposure tool, adjust the Brightness slider that will primarily affect the mid-tones of an image. This tool uses "intelligent saturation", so it does more than simply affecting normal saturation values. The positive values (attained when the slider is moved to the right) are comparable to what third-party software often refers to as Vibrance (it is gentler to the skin tones and will be able to enhance, for instance, a blue sky without over-saturating the rest of the image). The negative values represent regular saturation settings.

### High Dynamic Range tool
Use it to:
- Recover details in highlights and shadows for more dynamic range
- Amplify them where more contrast is needed
- black and white sliders control the endpoints of the range


Adjusting the Shadow and Highlight sliders in the High Dynamic Range allows not only the recovery of shadows and highlights but provides the possibility to amplify the ranges, increasing the contrast. The Black and White sliders are used for better control of the darkest shadows and the brightest highlights making it possible to fine-tune contrast using the High Dynamic Range tool only. In case more control is needed, the Levels and Curves tools can be used.

The Highlight slider in the High Dynamic Range tool is used to restore detail from highlights by compressing the color and luminance values at the right-hand side of the histogram.

The Shadow slider lightens the deepest shadows, compressing tonal values at the other end of the range and revealing any detail that was recorded at the time of capture.

The Highlight slider in the High Dynamic Range tool is used to restore detail from highlights by compressing the color and luminance values at the right-hand side of the histogram.

The Shadow slider lightens the deepest shadows, compressing tonal values at the other end of the range and revealing any detail that was recorded at the time of capture.

The tool is placed before the Levels and Curve tools for a reason. At the risk of revealing noise, the HDR tool should not be used after the adjustment of those tools in your workflow.

### Clarity Tool
The Clarity tool can help reduce haze or (a negative value) create a softening effect that is particularly effective when applied to a portrait image to smooth out skin tones.

Another way of adjusting contrast, but focused on the mid-tones. Structure adds edge definitions in areas of high details, works great on landscapes, architectural details, animal fur and feathers

The two sliders work similarly by altering the appearance of the transition between light and dark edges, however, they differ by the scale of the transition they affect. The difference in contrast of larger-scale transitions or regions can be altered using the Clarity slider. Positive values increase contrast and can be used to reduce the softening effect of haze in images, for example. Negative values can be selected to lower contrast and smooth out or soften unwanted detail that can be useful in portrait images.

The Structure slider is used to alter the contrast between increasingly smaller-scale areas, where transitions have only slightly different tonal values. Therefore, it has a particularly noticeable effect on images that feature very fine detail, such as fine branches, foliage, grass, fabric, and textiles. This adjustment slider can also be used to mitigate the image softening effects from lens diffraction.

In the Clarity tool, go to Method and choose one of the following options:
- Natural. This method applies mild local contrast and avoids false colors and clipped highlights. Low negative values may be used for softening portraits.
- Punch. Adds higher values of local contrast than Natural or Classic methods do and increases saturation slightly. If applied heavily, some highlight clipping may occur. Positive values using this method work well with landscapes.
- Neutral. This method adds the same level of local contrast as Punch, but saturation remains unaltered. When applying heavy contrast corrections, the Neutral method usually works best, resulting in a more realistic and pleasing effect. 
- Classic. The Classic option introduced in Capture One Pro 6 applies the mildest local contrast without increasing saturation. This method preserves highlight detail better than the Punch and Neutral options. Positive values using the Classic setting work well with architecture and on the images with a degree of haze. Low negative values of Clarity may be used for softening portraits.

You can reduce the effects of atmospheric haze to significantly improve an image using the Clarity tool. When you want to preserve highlight detail, select either the Natural or Classic modes initially as these are the most effective. In addition, the Classic mode does not increase saturation like the others.

Diffraction is a lens aberration that increases upon stopping down leading to a loss of definition, with at first a loss of contrast and then a loss of resolution. The Clarity tool can be used to reduce these effects by increasing contrast and the perceived sharpness.

The selection of the Method and Slider choice is determined by the image content and creative intent, however, in general terms, you can adopt the Natural method and Clarity slider combination for a low amount of large-scale contrast where diffraction is just visible at mid apertures, for example. With small apertures, where the blurring effects of diffraction are more visible, use the Natural or Neutral and Structure slider combination to apply a higher amount of small-scale contrast.

Select the Natural method and Clarity slider combination when a slight loss of contrast is noticed or adopt Natural or Neutral and Structure combination when a more noticeable loss of sharpness is detected.

Before using the Clarity tool, it is a good idea to make a white-balance correction or go to the Levels tool and perform an Auto Levels adjustment, preferably by using the individual Red, Green, and Blue Channel mode to set black and white points and perform color correction.

### Level tool
Map the tonal values in an image from input values to output values.

One way to use it:
- you have an image where most of the tonal values are in the center of the histogram, no shadows nor highlights hence the image have a "flat" appearance
- you can remap tonal values by moving the output shadows and highlights sliders to the edge of your histogram
- it will make your image look more dynamic

### Curve tool
- used to be the mainstay tool for adjusting contrast and brightness
- pick points on the curve and move them upwards or downwards to adjust the brightness of those tonal values
- in RGB mode, modifying the curve will also have an impact on color saturation
- in Luma mode, it only impacts contrast and brightness, no impacts on color

The combined RGB mode is used to adjust contrast and lighten or darken an image.

To lighten or darken the selected region, select and drag (or scroll) a control point up or down respectively to form a curve.

To decrease or increase contrast in the chosen region, click and drag the control point to the left or right respectively.

The tone curve has moveable anchor points located at either end, one in the shadows and another in the highlights. They enable you to set black and white points (remap the darkest and lightest values in the tonal range), similar to the Levels tool.

## Details tab
### Navigator
Located in the Details tool tab, the Navigator tool displays a thumbnail of the selected image along with a white rectangular frame that depicts the current zoom level in the main Viewer. You can use this frame as an aid to navigation when using high magnification in the Viewer. 

When using the Pan cursor (hand icon) tool, a more convenient option is to open a Navigator window directly over the image in the Viewer. Simply Ctrl/Right-click the image in the Viewer. A fully-functional Navigator tool will be displayed.

### Focus tool
Use the Pick Focus Point icon to select the desired area (in the Viewer) to inspect in detail.
Sharpness should be assessed at 50% and at 100%.

### Sharpening tool
In the Sharpening tool, set the Amount. This slider lets you specify how much brightening and darkening you want to apply to the edges.  Higher settings apply more contrast. The majority of the sharpening adjustment is performed using this and the radius slider.

The Radius slider adjusts the width of the brightened and darkened areas at the edges. Typically the radius can be set low at first and increased in combination with the amount while observing the effect on the edges.

The Threshold slider controls the difference in brightness between adjacent edge pixels, where the sharpening effect will take place. When set to zero (0), sharpening will be applied to all the edge pixels in an image. High values affect high tonal differences between edge pixels. Typically the threshold is set low, the value between 0-1.0 is common. However, the threshold can be increased to mitigate sharpened noise (i.e., after adjusting the amount and radius).
Adjust the Halo Suppression slider when halo artifacts are noticeable, particularly after aggressive sharpening has been applied (i.e., after high values of amount and radius have been applied). Check images on high contrast edges for halos (dark and bright-lines) in the Focus window or Viewer at 100% or more and drag the slider to the right to reduce or eliminate them.

### Noise reduction tool
The Luminance slider removes the pattern-like noise that is often present in shadow areas.

The Color slider removes color noise from images that are typically noticeable as subtle green/magenta patterns. It is very difficult to recommend specific settings as noise varies from camera to camera, but the program defaults provide a good starting point.

Applying heavy chromatic or luminance noise reduction may give an image a soft appearance. If that is the case, adjust the Details slider to smooth the surface of an image. The default setting of 50 produces an even balance between image detail and noise. Adjust the Details slider to a smaller value to achieve a smoother surface. A large value produces fine detail with improved edge definition.

### Film grain tool
The granularity or size of the grain is adjustable. Alter from fine to coarse by dragging the Granularity slider to the right.