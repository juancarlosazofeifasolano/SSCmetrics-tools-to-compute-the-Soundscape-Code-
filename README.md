#SSCmetrics: A MATLAB tool to compute the 'Soundscape Code'

This repository accompanies our paper [Soundscape analysis reveals ecological differences among coral reefs habitats].

The goal of this MATLAB tool is to show and explain all the necessary processing steps and MATLAB commands to compute the five metrics of the Soundscape Code (Wilford et al. 2021). The project provides an example audio data from a SoundTrap ST600 (Ocean Instruments, New Zealand) deployed in Lizard Island, Great Barrier Reef, Australia. The example WAV file is a five minute recording, using high gain, and 48 kHz sampling rate. The audio file is calibrated and processed into four one-minute segments, following the one-minute length files in Wilford et al. (2021). Thus, this code computes and stores the Soundscape Code metrics for each one-minute segment.
Consider that this code is meant to show how the code works on a single example, specific to our instrument, and in the MATLAB Online environment. For batch processing and other instruments, the code should be modified to consider local directories, noise removal, instrument-specific calibration, and loops for batch processing. 
In the MATLAB live file, we provide the code with a brief exaplanation, following the equations in Wilford et al. (2021) and updates of terminology in ISO (2017).
References:
Wilford DC, Miksis-Olds JL, Martin SB, Howard DR, Lowell K, Lyons AP, Smith MJ. 2021. Quantitative soundscape analysis to understand multidimensional features. Frontiers in Marine Science 8, 672336. 10.3389/fmars.2021.672336.
ISO. 2017. 18405.2. Underwater Acoustics—Terminology. International Organization for Standardization, Geneva.

##Open and run in MATLAB Online##
1. In MATLAB Central File Exchange, click on the  "Open in MATLAB Online" button.
2. Download and accept the use of the tool "SSCmetrics: A MATLAB tool to compute the 'Soundscape Code'".
3. In the FILES panel, navigate to the content of the folder SSCmetrics.
4. Select the file "SSCmetrics_Project.prj" to initialize the project.
5. In the FILES panel, navigate to the content of the folder SSCmetrics>code.
6. Select the file "SSCmetrics.mlx" to open the MATLAB live file with the explanation and code lines necessary to compute the Soundscape Code.
