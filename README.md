# BattleGearTemplates
010Editor templates for various Battle Gear file formats.  

# Templates
BG3TIM2 | Battle Gear 3 TIM2 PS2 textures, has special "sub-image" userdata struct.
FAT | Battle Gear 2 main archive header file.
FATZ | Battle Gear 3 main archive header file.
FOZ | Unknown, references a "FON" file by the same name and zlib deflated data follows.

# Formats
Format | Description
------ | -----------
TM2 | Battle Gear 3 TIM2 PS2 textures, has special "sub-image" userdata struct.
ZPACK | Battle Gear 3 main archive header file, named "FAT_Z.BIN".
ARC | Battle Gear 3 main archive data file, named "BG3ZPACK.BIN".
FOZ | Unknown, references a "FON" file by the same name and zlib deflated data follows.
GST | Unknown, all files have "GHOST" in name, is entirely zlib deflated.
LINK | Possibly a test file only, is plaintext.
DAT | Generic extension but used only on LINE files in Battle Gear 3.
CAM | Unknown, camera possibly.
PCK | Some kind of texture?
PXD | Appears to be a model and has an accompanying PCK file.
PNG | Common PNG image file format.
