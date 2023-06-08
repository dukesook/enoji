# Image Overview
## lunar_eclipse.jp2
* Standard JPEG2000 version of the image.
<br /><br />

## lunar_eclipse_hevc.heif
* Standard HEVC encoded version of the image.
<br /><br />


## lunar_eclipse_jpeg2000.hej2
* One of the first HEIF files to contain a JPEG2000 encoded image. It's configured to be as simple as possible for now with more advanced features to come.
* The [jpeg2k branch](https://github.com/strukturag/libheif/tree/jpeg2k) in libheif was used to create the image. 
* A big thanks to Josh Lenart for providing the image.
<br /><br />

## lunar_eclipse_mp4box.png
* [MP4Box.js](https://gpac.github.io/mp4box.js/test/filereader.html) is a useful tool for examining ISO BMFF files. This image shows how it **would** parse *lunar_eclipse_jpeg2000.heif* once the lastest [pull request](https://github.com/gpac/mp4box.js/pull/323) is accepted.
<br /><br />
<br /><br />

<!-- 
# Key Points from ISO/IEC 15444-16
* The coded image shall be exactly one Contiguous Codestream box. 
* The cdef, or Channel Definition Box, shall be present in the j2kH box.
* The image shall be associased with one 'colr' item property.
-->
