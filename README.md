# Dali-Tech-D8X3C-Thermal-Camera-Backpack
Customized Dali Tech Thermal Camera Backpack with integrated analog to UVC and serial for debug.

# Goal
Thermal cameras are a good tool to observe heat distributions; however, they are **PRICY**, especially for high-resolution models. This project aims to provide a cost-effective alternative to the common FLIR series thermal camera. By reverse engineering and designing custom acquisition hardware, one can get a $640 \times 480$ thermal camera for **~\$250** (on eBay), compared with the FLIR Boson series that has the same resolution, which is worth way more than ~\$4000+. Of course, the image quality for the Dali Camera model is limited ($<60~80 mk$) compared with the FLIR Boson; however, sensitivity can be partially compensated by post-image processing, and the huge price difference still makes the alternative an unparalleled choice for low-cost scenarios where budgets are limited and high sensitivity is not a major concern.

The Dali D8X3C camera is an Uncooled FPA thermal camera, where the model numbers D883C and D843C have resolutions of $384 \times 288$ and $640 \times 480$, respectively. Both camera provides a 50Hz analog output along with a 14-bit digital thermal signal. These cameras once served as surveillance cameras during the pandemic, used by remotely sensing body temperature, for example, like customs or any public spaces. After the pandemic, these cameras can be easily purchased on Liqudation or the second-hand market, for example, on eBay.

More to be updated (including source files and even HW version 1.1), stay tuned!
