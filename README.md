# Convert images to be compatible with Polaroid Z2300 #

http://www.amazon.com/Polaroid-Z2300-Digital-Instant-Camera/dp/B008GVXL1A

**Purpose**:

The printer on the Z2300 can be used to print images from other devices but if you try to print images that have been cropped on your PC then the Z2300 will reject them with "File Error".  

This script will convert all images in the current working directory into a format compatible with the device.

**Requirements**:

Python and Python Imaging Library.

**Usage**:

Take a SD card and place all images you wish to print in 

SDDRIVE:/DCIM/100NIKON/

Copy the python script to that directory.

Open a shell session in SDDRIVE:/DCIM/100NIKON and execute "python make_compatible.py".

**Important**:

**NEVER** execute this script on the original images.  **ALWAYS** make a copy and operate on the copy.

