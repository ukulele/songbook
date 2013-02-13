# The Balham Ukulele Society Songbook Project

## Basic Songbook

This project is basic starter songbook that includes a few songs from the big songbook. It is designed to be compiled with a basic Tex system installed, with `pdflatex` rather than `xelatex` but it works across major platforms.

### Building

Run `mvn clean latex:latex` in the root folder. Find PDF in the `target` folder generated.

Songs are in alphabetical folders within the `/src/main/latex/common/songs` folder.

### Notes

If you require nicer fonts, `xelatex`, etc, not a problem, but that would be a different project, this basic songbook should always maintain cross-platform compliance.

Note: the Maven latex plugin does not support - at time of writing - `xelatex`. So you will have to copy the songs folder into the same folder as the main `.tex` file and compile from there on the command line. Perhaps a symbolic link will work. We will add Maven tasks in future to assist, but for now, YMMV.

----------------------------------------

The Balham Ukulele Society Songbooks project by Vish Vishvanath, Matt Gunning, Alyn Gwyndaf, Charlie Ullman, et al is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License.

http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US

