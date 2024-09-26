## About MMText2PNG

MMText2PNG is a tool generate images to use with [retro](https://github.com/HarbourMasters/retro), it will automatically generate images for various game elements used in [2ship2harkinian](https://github.com/HarbourMasters/2ship2harkinian)

## How to install

Just extract and run ****MMText2PNG.exe****

## Using MMText2PNG

Using MMText2PNG is fairly straight forward, simply select an element to adjust font, bold, italic and underline. For more options such as size, color, outline and offsets click on the options button in the toolbar. You can also cycle through example text by clicking left mouse to go forward and right mouse to go back.
To generate images from here check all elements you want to generate image for and select an output directory and press ****Generate Images****. Once that is done you can then use [retro](https://github.com/HarbourMasters/retro) to create your O2R file for use with 2ship2harkinian

## Font Images

Since this is a beta and will remain so until project is migrated to C# do not expect perfection from font generation just yet. In most cases it produces decent results but it will obiously depend on font, size etc. Offsets have been calcuated for most characters that need them (all alphabetic etc) but may still require fine tuning too.
Other characters have not been tested yet. If you want to see which characters have offsets you can checkout the Google sheet [here](https://docs.google.com/spreadsheets/d/1yimCZf6W96utbVUSrPGpt-VSJLFvEX40PjsNfMGKPO0/edit?usp=sharing). Offsets are calcutated on 64x64 character size based on 1080 vertical resoultion. -1 is not tested, 0 is no offset needed and any number is an offset, either left or right.
Button characters (A, B, L, R, Z and C buttons) are automatically generated however they have not been tested how they look in the game yet. No soultion for final two characters (target and control stick) as yet but images will still be generated which you can edit manually for now.

## More Notes
Scaling will attempt to adjust font sizes to match scaling factor and currently can produce flakey results.
