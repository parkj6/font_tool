# Verge Lite Korean Font pack

Huami font tools collection
===========================

This is a suite of tools to make easier to modify font file for some Huami wearable devices.

I forked this repo from https://github.com/amazfitbip/font_tool to add Korean Fonts to Verge Lite

Supported devices:
==================

Xiaomi MI Band 2 - (C) José Rebelo  
Xiaomi MI Band 4 - (C) Eddi De Pieri  
Amazfit BIP - (C) Yener Durak  
Amazfit GTR(47mm and 42mm) and Verge Lite - (C) Eddi De Pieri  

Requirements: 
============= 
-Python  3.x
-[Pillow](https://pillow.readthedocs.io/en/stable/)
-png (pypng)


Special Thanks
==============
[Google Noto Fonts](https://www.google.com/get/noto/)
[sukso96100](https://github.com/sukso96100/amazfit-bip-kr) for providing the [ttf2bmp.py] I used to extract the font -> image. 


Usage
=====
To unpack
```python ./fonttool-[DEVICE NAME] unpack Mili_pyh.ft```



To Repack
```python ./fonttool-[DEVICE NAME] pack Mili_CJK.ft```

TODO
====
[.] Make TODO list
[] Finish TODO list
[] Update Usage
[] Modify the script for Japanese 
[] Test on a device that is not mine.
[] Extract the font in PNG format rather than BMP