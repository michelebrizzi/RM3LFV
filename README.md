# RM3LFV Light Field Video Dataset
Public release v0 10/04/2019
- Authors: Michele Brizzi, Federica Battisti, Alessandro Neri\
- Contact: michele.brizzi@uniroma3.it\
- Website: http://www.comlab.uniroma3.it/rm3lfv.html


## Publication
If you use this database in your research, we kindly ask that you reference our paper listed below:

```
@INPROCEEDINGS{Brizzi_ICME_2019, 
author={M. {Brizzi} and F. {Battisti} and A. {Neri}}, 
booktitle={2019 IEEE International Conference on Multimedia and Expo (ICME)}, 
title={A Feature-Based Approach for Light Field Video Enhancement}, 
year={2019}, 
volume={}, 
number={}, 
pages={1204-1209}, 
abstract={Light field imaging is increasingly spreading and its applications are reaching a larger number of users. The quality of the rendered content as perceived by the viewers is a key factor for the future development of this technology. Many factors can cause a degradation of the Light Field quality, from data acquisition/creation to the final rendering. To increase the perceived quality of the Light Field content, as usually performed for 2D and 3D content, processing techniques can be applied. In this work, an approach for enhancing Light Field videos is presented. The proposed approach is based on the characteristics of the human visual system and relies on the estimation of depth, motion and saliency. Those features guide a selective enhancement that is implemented in the Laguerre-Gauss Transform domain. The performed tests show the effectiveness of the proposed method.}, 
keywords={data acquisition;feature extraction;image enhancement;rendering (computer graphics);video signal processing;rendered content;feature-based approach;light field video enhancement;light field imaging;light field quality;light field content;data acquisition-creation;human visual system;Laguerre-Gauss transform domain;Feature extraction;Bandwidth;Light fields;Transforms;Image color analysis;Imaging;Visualization;Light Field;Enhancement;Feature;Laguerre-Gauss Transform}, 
doi={10.1109/ICME.2019.00210}, 
ISSN={}, 
month={July},}
```

For further information, comments or suggestions, please contact Michele Brizzi at michele.brizzi@uniroma3.it.


## Database description
The database contains 7 light field video sequences. They were created using Blender [1] and the light field add-on from [2].\
For each sequence, we provide a configuration file with camera settings and disparity ranges. Video frames for each viewpoint are given as individual PNGs.

### Folder structure:
- sequence_name\
	- sequence\
		- frame 1 folder (000001)\
			- viewpoint 1 (input_Cam000)\
			- viewpoint 2 (input_Cam001)\
			- viewpoint 3 (input_Cam002)\
			- ...\
		- frame 2 folder (000002)\
		- frame 3 folder (000003)\
		- ...\
	- config file\

## References
[1] Blender, Blender Foundation, [Online], https://www,blender.org\
[2] K. Honauer, O. Johannsen, D. Kondermann and B. Goldluecke, "A dataset and evaluation methodology for depth estimation on 4D light fields", in Asian Conference on Computer Vision (ACCV), 2016

## Copyright
The following 3D models from Sketchfab (https://www.sketchfab.com) were used to create the database:

Great Mountain (https://skfb.ly/6HtoK) by Gesy, licensed under CC-BY 4.0\
Low poly fox (https://skfb.ly/6GZ7T) by tomkranis (https://sketchfab.com/tomkranis), licensed under CC-BY 4.0\
Drevo (https://skfb.ly/6HxSy) by Peter Leban (https://sketchfab.com/Pjotruska), licensed under CC-BY 4.0\
Snowy Boulder (https://skfb.ly/6JCut) by danielmine (https://sketchfab.com/danielmine), licensed under CC-BY 4.0

Granite head of Amenemhat III (https://skfb.ly/6GZT9) by The British Museum (https://sketchfab.com/britishmuseum), licensed under CC-BY-NC-SA 4.0\
Portrait bust of Sir Robert Bruce Cotton (https://skfb.ly/6IMHZ) by The British Museum (https://sketchfab.com/britishmuseum), licensed under CC-BY-NC-SA 4.0\
Bust of Perikles (https://skfb.ly/6JCtr) by The British Museum (https://sketchfab.com/britishmuseum), licensed under CC-BY-NC-SA 4.0\
Brick (https://skfb.ly/6HOEM) by OlegYurkov (https://sketchfab.com/OlegYurkov), licensed under CC-BY 4.0\
Wall2 (https://skfb.ly/6JCun) by lippo (https://sketchfab.com/pottuvoi), licensed under CC-BY 4.0 

Zombunny (https://skfb.ly/6JCt9) by humzone (https://sketchfab.com/humzone), licensed under CC-BY 4.0\
Rempart Walls scenery 3 - Fougères castle (https://skfb.ly/6JCtU) by noxfcna (https://sketchfab.com/noxfcna), licensed under CC-BY 4.0 

SD Macross City Standoff Diorama (https://skfb.ly/6JCtA) by tipatat (https://sketchfab.com/tipatat), licensed under CC-BY 4.0\
Sky Pano - L.A. Helipad (https://skfb.ly/6JwZC) by mozillareality (https://sketchfab.com/mozillareality), licensed under CC-BY-NC-SA 4.0

Van gogh Room (https://skfb.ly/6GUT6) by ruslans3d (https://sketchfab.com/ruslans3d), licensed under CC-BY 4.0

Sands Location (https://skfb.ly/6HYNR) by bocharova (https://sketchfab.com/apsnu), licensed under CC-BY-NC 4.0\
Warcraft Infernal Concept (https://skfb.ly/6JC9t) by Horus3dart (https://sketchfab.com/karazux), licensed under CC-BY 4.0\
Sylvanas (https://skfb.ly/6HoSx) by Sanguinax (https://sketchfab.com/sanguinax), licensed under CC-BY 4.0\
Sky Pano - Milkyway (https://skfb.ly/6HFEV) by mozillareality (https://sketchfab.com/mozillareality), licensed under CC-BY-NC-SA 4.0

Peach Castle (https://skfb.ly/6HvqA) by mStuff (https://sketchfab.com/mstuff), licensed under CC-BY-NC 4.0\
Animated Goomba (Super Mario Bros) (https://skfb.ly/6JC98) by Anthony Yanez (https://sketchfab.com/paulyanez), licensed under CC-BY 4.0

To view a copy of those licenses, visit http://creativecommons.org/licenses.
