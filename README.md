# YAAC: Another Awesome CV

This is a customized version of my résumé, using the template from [YAAC: Another Awesome CV](https://github.com/darwiin/yaac-another-awesome-cv). There exists another version on [Overleaf](https://www.overleaf.com/latex/templates/awesome-source-cv/wrdjtkkytqcw). 

Please refer to the original repository for:
* About
* Styles
* How to use **YAAC: Another Awesome CV** latex class
* License.

# Notes

## Format
* There are edits in the .cls file as well as in the main .tex file.
* The accent color has been changed from blue to gray by default
* The bullet points have been changed
  * the former icons for bullets are now the subbullets (`>`)
  * the bullets are dots similar to: $\cdot$

### New Features
* Social "media" links: you can now have icons in the header for Google Scholar and Google Patents 

## Usage
* This uses the XeLaTex compiler by default, but it is recommended to try LuaLaTeX if XeLaTex is not compiling.
  * This may take a minute (literally).
  * You may ignore the error pertaining to: 
    ```
    l.30 	\makecvheader
    ``````
* You can find an example in the folder `resume_202311`, which contains all the necessary files within. An example output is in [resume_202311/output/Filippi_resume_202311.pdf](resume_202311/output/Filippi_resume_202311.pdf)