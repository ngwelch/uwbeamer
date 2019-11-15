# Background 

Beamer defaults are a joke. 
Most questions and solutions posted online aim to unwind qwirks of default themes. 
UW's marketing department publishes Microsoft templates along with the associated style building blocks here: https://www.washington.edu/brand/.
This template translates the purple/white presentation template from PowerPoint to Beamer.


# Usage

To use the "uw" theme, you must have the following files in the same directory as the Tex file that uses them:: 

	- beamercolorthemeuw.sty
	- beamerinnerthemeuw.sty
	- beamerthemeuw.sty
	- graphics

The graphics directory contains the elements needed to build a nice looking Beamer presentations that uses the hard work that the marketing team put into making these things available. 

I suggest just making a copy of the template directory for each presentation. 
The files are not very big. 
There is a cleaner ways to use the template, but this is good enough for a first pass. 

The example file has the CSSS logo on the title page. 
The stats logo is also in the graphics directory. 
You can move things around by editiing the footline block in ```beamerinnerthemeuw.sty```. 

As shown in the example, invoke the ***uw*** theme by including ```\usetheme{uw}``` in the header of your file. 
If you want to get familiar with the different settings included in the style files, then I suggest the StackExchange post listed in the credit below.


# Issues

- I don't see a good way to include the Sans fonts suggested by the UW brand guide. 
- There is a cleaner way to package and invoke the theme, but the solutions I saw do not travel very well. 
- There may be some weird style settings that are not covered by the settings spelled out in these files... If something looks mangled in the pdf, consider yourself warned. 


# Bonus

Here are the UW colors for your ggplots: 

uwPurple = rgb(red=51, green=0, blue=111, maxColorValue=255)
uwGold = rgb(red=232, green=211, blue=162, maxColorValue=255)
uwMetallicGold = rgb(red=145, green=123, blue=76, maxColorValue=255)

 

# Credit

This template is based on the following stackexchange post: https://tex.stackexchange.com/questions/146529/design-a-custom-beamer-theme-from-scratch.


# Fine print

Copyright 2019

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
