# Demosaicing-for-Plenoptic-Cameras
White Lenslet Image Guided Demosaicing for Plenoptic Cameras

This is a method developed to demosaic raw images taken with plenoptic cameras (eg Lytro 1 or Lytro Illum).

## Getting Started

### Prerequisites

In order to use the demosaicing function, you also need to download the D. Dansereau's Light Field Toolbox:
https://fr.mathworks.com/matlabcentral/fileexchange/49683-light-field-toolbox-v0-4

### Installing

In the toolbox folder, add our files and replace the file LFDecodeLensletImageSimple.m by our version.

Launch Matlab and follow the instructions given by D. Dansereau to use its toolbox.

By default the toolbox is now using our method of demosaicing to extract subaperture images.

## Acknowledgement

Thanks to Donald Dansereau for writing the Light Field Toolbox code

## Paper and Citation

Pierre David, Mikaël Le Pendu and Christine Guillemot. "White lenslet image guided demosaicing for plenoptic cameras". MMSP 2017 Best Paper Award. Project webpage: http://clim.inria.fr/research/Demosaicing/LensletDemosaicing.html

If you use our method, please cite the following paper:

@inproceedings{david2017white,
  title={White lenslet image guided demosaicing for plenoptic cameras},
  author={David, Pierre and Le Pendu, Mika{\"e}l and Guillemot, Christine},
  booktitle={Multimedia Signal Processing (MMSP), 2017 IEEE 19th International Workshop on},
  pages={1--6},
  year={2017},
  organization={IEEE}
}
