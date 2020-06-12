# Welcome to solution-processed graphene Raman spectroscopy analysis tool

Raman spectroscopy analysis script created to evaluate Raman parameters of solution-processed graphene with emphasis on the qualitative thickness determination based on 2D and LO+ZO' Raman bands. By performing individual Raman peak fittings of two areas: around G and 2D peaks, this makes it is possible consistently ectract information and analyse it. One has to remember that for accurate analysis, the Raman spectrum for G peak should have signal-to-noise ration 14:1.

# How to proceed

1. Make sure you have rampy, pylab, matplotlib, scipy packages installed. Look for pip install command to install them otherwise.
1. Edit Python script according to your data:
    1. Rename file file_baseg, file_base2d depending on your .txt file names.
    1. Set first_file number.
    1. Provide with ratio between intensities of G and 2D peaks.
1. Place the script into a folder with all data.
1. Run it via Jupyter notebook.
1. All results will be in the sample folder: figures (.png), fitting parameters (.cvs). The normalised spectra (.txt) can be saved if the ' #saving normalised spectra of LO+ZO' spectrum part' is uncommented.

