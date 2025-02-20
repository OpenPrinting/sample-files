Sample Files
============

This repository contains a variety of sample files that can be used for print
testing.


Contents
--------

- "jpeg": JPEG image files.
- "jxl": JPEG-XL image files.
- "pcl": HP-PCL document files.
- "pdf": PDF document files.
- "png": PNG image files.
- "source": Source files that are used to generate the other text files.
- "text": UTF-8 plain text files.
- "tiff": TIFF image files.


Source Files
------------

The files in the "source" directory use a simple naming convention:

    SIZE-ORIENTATION-SUBJECT-TYPE.EXT

where "SIZE" is the page size, "ORIENTATION" is 'portrait' or 'landscape',
"SUBJECT" is 'document', 'photo', or 'vector', "TYPE" is 'color' or 'gray', and
"EXT" is the extension used for the file - '.xcf.gz' for a compressed Gimp file,
'svg' for a SVG file, etc.

The current document source files include:

- TBD

The current photo source files include:

- "SIZE-landscape-photo-color.xcf.gz": Flowers between two rocks.
- "SIZE-landscape-photo-gray.xcf.gz": A knot in a log.
- "SIZE-portrait-photo-color.xcf.gz": A wooden maiden on a red shed.
- "SIZE-portrait-photo-gray.xcf.gz": A Toronto city street with the CN tower.
- "8x10-landscape-photo-color.xcf.gz": Sunset on a lake.
- "8x10-landscape-photo-gray.xcf.gz": A highway in a mountain pass.

Vector graphics source files:

- "SIZE-portrait-vector-color.svg": Rulers, text, and a CIExy 1931 color gamut
  visualization.

Document source files:

- TBD

Miscellaneous source files:

- "CIExy1931.svg" and "CIExy1931-License.txt": SVG clipart for the CIExy 1931
  color gamut visualization.
- "DisplayP3.icc" and "DisplayP3-License.txt": The Display P3 ICC profile.
- "compatibleWithAdobeRGB1998.icc" and "compatibleWithAdobeRGB1998-License.txt":
  An AdobeRGB 1998 ICC profile.
- "sample-files-qr-code.png": A QR code pointing to this repository on Github.


Test File Naming Conventions
----------------------------

In general, the name of each test file is the same as the corresponding source
file.  The exception is for image file formats where the TYPE suffix is replaced
by the actual image color space used:

- "adobergb": 8 or 16 bit AdobeRGB 1998.
- "displayp3": 8 or 16 bit Display P3.
- "sgray": 8 bit grayscale with a gamma of 2.2.
- "sgray16": 16 bit grayscale with a gamma of 2.2.
- "srgb": 8 bit sRGB.


Legal Stuff
-----------

Copyright © 2025 by OpenPrinting.

Sample Files is provided under the terms of the Apache License, Version 2.0.  A
copy of this license can be found in the file `LICENSE`.  Additional legal
information is provided in the file `NOTICE`.

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.  See the License for the
specific language governing permissions and limitations under the License.
