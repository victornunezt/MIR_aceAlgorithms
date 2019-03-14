# MIR - Audio Chord Estimation Algorithms 

To run this notebook, you should have installed the following libraries:

- **Essentia library** *(https://essentia.upf.edu/documentation/installing.html)*
- **Madmom library** *(https://madmom.readthedocs.io/en/latest/installation.html)*
- **Mir-eval library** *(https://pypi.org/project/mir_eval/)*
- **pygments library** *(https://pypi.org/project/Pygments/)*
- **some common scientific libraries**: numpy, ipython, matplotlib, cython.

If you prefer, you can also use a MIR toolbox docker with all these libraries already installed: *https://github.com/MTG/MIR-toolbox-docker*

Some folders and directories are created in order to organize the files we create in the process. This directories can be changed in the running feature extraction and running mir-eval sections, but remember to create the folders:

- **soundsDir** *('sounds/' by default)*: directory for the audio dataset folders. Audio-aligned jazz harmony dataset (JAAH) is used. *(https://github.com/MTG/JAAH)*
- **outputDir**= *('outputFiles/' by default)*: directory for some low-level descriptors (created during feature extraction)
- **predictDir** = *('annotations/predicted/' by default)*: directory for predictions of the algorithms in .lab format (created during feature extraction) 
- **refDir**= *('annotations/reference/' by default)*: directory for reference annotations in .lab format (already provided)
- **evalDir**= *('annotations/evaluation/' by default)*: directory for individual scores of the evaluation in .json format(created during mir evaluation)

The running procedure may take a few hours.
