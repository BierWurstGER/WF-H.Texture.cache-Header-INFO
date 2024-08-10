# Warframe - Header Files
Here is perhaps a complete list of all the H.cache files and their magic/enum list. 
- H.Texture.cache 
- H.Lightmap.cache
  
# `H.Texture.cache` MAGIC HEX/DEC END.: INFO

* Magic: `A3`  `163` `*_d.png` , `*_t.png`|	Diffuse
* Magic: `A4`  `164` `*_id.png`|
* Magic: `A5`  `165` `*_in.png`|	
* Magic: `A6`  `166` `*array*`|	Multiple Texture
* Magic: `A7`  `167` `*_r.png`|	Roghness
* Magic: `AB`  `171` `*_y.png`|	?
* Magic: `AC`  `172` `*_v.png`|	*only warframe
* Magic: `AE`  `174` `*.cube` , `*_v.png`|	
* Magic: `AF`  `175` `*.raw`|	
* Magic: `B0`  `176` `*fvl.raw`|	
* Magic: `B1`  `177` `*_vn.tga` , `*.hdrcube`|	?
* Magic: `B8`  `184` `*_n.png`|	ReferenceNormals
* Magic: `BC`  `188` `*PackMap`|	ReferenceNormals and TintMask,Specular,Roughness,Diffuse
* Magic: `C2`  `194`|	maybe like packmap ?
* Magic: `C3`  `195` `*PackMap`|	ReferenceNormals and ScratchGrimeCurvatureMap MacroRoughness

 DDS FLAG_list	HEX DEC	

* Flag:	|	`00` `0`
* Flag:	|	`01` `1`
* Flag:	|	`0A` `10`
* Flag:	|	`0C` `12`
* Flag:	|	`03` `3`
* Flag:	|	`1F` `31`
* Flag:	|	`20` `32`
* Flag:	|	`21` `33`
* Flag:	|	`22` `34`
* Flag:	|	`23` `35`
* Flag:	|	`06` `6`
* Flag:	| `07` `7`

# `H.Lightmap.cache` MAGIC HEX/DEC END.: INFO

* Magic: `A3`  `163` `*_mm.png` , `*_sm.png` , `*_clr.png` , `*_dir.png` , `*_hd.png` , `*_he.png` , `*_l1.png` , `*.lcmm` , `*_lnm.png` , `*.lcsm` |
* Magic: `A4`  `164` `*_hlod.hlpm`|
* Magic: `A6`  `166` `*_lpm.png`|
* Magic: `B1`  `177` `*_smcube0.png`|
* Magic: `B5`  `181` `*_cross.hdr`|

DDS FLAG_list	HEX DEC	

* Flag:	|	`00` `0`
* Flag:	|	`01` `1`
* Flag:	|	`0C` `12`
* Flag:	|	`03` `3`
* Flag:	|	`1E` `30`
* Flag:	|	`23` `35`
* Flag:	| `07` `7`
