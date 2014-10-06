First off, I would like to thank the incredible job of all the skinners out there who inspired this skin.
Major learning came from the foundation skin, artistic influences are mainly taken from elementaryOS (http://elementaryos.org/) and the Arctic skin (http://forum.xbmc.org/showthread.php?tid=170954).
I also used some icons from the GNOME project licensed under GNU General Public License version 2.

Here some instructions on how to install this early alpha build of element.

	1. Download the necessary font files. I did not include them due to possible licensing issues. The files you need are:
		- Raleway font available at Google Fonts: http://www.google.com/fonts/specimen/Raleway
		- econ icon font by spiceofdesign available at http://spiceofdesign.deviantart.com/art/econ-icon-font-323146943

	2. The whole home menu is static, meaning: if you want to use costume shortcuts, you will need to add/modify the code in Home.xml.

	3. Same holds true for the background images in the home menu. The folders used for the slideshows are included, yet they are not filled, because of image licensing and skin size reasons. If you want a slideshow, please put images into the respective folders (located at skin.element\media\bgs)!
	
	4. Currently, I am unsure if the skin is even running on linux machines. I tried earlier builds which crashed my OPENELEC system, so be careful here!
	

Second, there are numerous bugs to be expected. If you encounter a bug, I would kindly ask you to:

	1. Try to fix it and - after testing it - commit the fixed file to the GitHub repository.
	
	2. If you encounter a bug that you cannot fix, report it. I am however not an experienced skinner, so if and when I can fix a bug is very uncertain.
	

Third, a list of known issues/unfinished stuff in this build:

	1. No OSD skinning done. All buttons are available, yet completely untouched.
	
	2. Views do not work as expected in some cases. E.g., I only coded certain views looking at movies, so they may behave unpredictable when looking at things such as files or episodes.
	
	3. No skinning done on Music library at all!
	
	4. Weird behavior on entering e.g. the movie library... something not quite right with the animations here.
	
	5. Endlessly more stuff I currently do not have the time to list. Feel free to explore the endless buggyness! ;-)