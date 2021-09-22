# somewhere-ml
#### Machine learning experiments + VQGAN+CLIP / Guided Diffusion multimodal art generator notebook
# S2 GAN Art Generator Changelog
## Version 1.5.0
#### September 21, 2021
- Removed ISR for image upscaling and replaced it with an ESRGAN implementation
- Added the ability to upscale a folder of images or a single target image
- Added the option to generate a video using ffmpeg using either default outputs or upscaled image sequence ({abs_root_path}/ESRGAN/results/ directory)
- Fixed some markdown issues, removed bad wording from older notebooks
- Added a block to delete all generated output for advanced troubleshooting & tidy-ness

## Version 1.4.0
#### September 4, 2021
- Fixed CLIP-guided diffusion method
- Exposed new CLIP model selection for both VQGAN+CLIP and diffusion methods
- Removed excess instructional text ahead of Wiki launch
- Added the ability to generate a video regardless of method
- Exposed new parameters in the Generate a Video block

## Version 1.3.0
#### August 30, 2021
- Moved changelog to README.md
- VQGAN+CLIP and CLIP-guided diffusion blocks are now separate.
- Parameters and Execution blocks merged into single blocks.
- Fixed potential "interestingness" bug with VQGAN+CLIP method
- Exposed four new experimental/advanced parameters for fine-tuning VQGAN+CLIP method
- Updating ffmpeg block in 1.3.1 to work with CLIP-guided diffusion method, started fixing this in 1.3.0

## Version 1.2.3
#### August 26, 2021
- Bug Fixes
- Added "VQGAN Classic" link to older notebook (legacy copy) at the top of the updated notebook

## Version 1.2.2
#### August 23, 2021
- Bug Fixes

## Version 1.2.1
#### August 22, 2021
- Fixed issues with temp filesystem not importing os, causing errors when not using Google Drive
- Removed Wikiart 1024 dataset because the hosting provider went offline
- Fixed ImageNet datasets to use new hosting provider

## Version 1.2.0
#### August 21, 2021
- Bug Fixes

## Version 1.1.2
#### August 18, 2021
- Forked notebook from the original copy
- Integrated Katherine Crowson's CLIP-guided diffusion method as a secondary mode to the notebook
- Removed automatic video naming and exposed it as a parameter instead.
