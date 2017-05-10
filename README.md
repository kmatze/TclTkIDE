TclTkIDE ...
==========

- ... version 0.9 by ma.ke. 05/2016 is a tcl IDE windows
- ... is a hobby project with no warrenty

**features:**

- syntax highlighting
- has a german tutorial / lesson course from tclcoach (see http://www.tcl-coach.de/)
- color picker (Named Colors by Keith Vetter, see http://wiki.tcl.tk/37701)
- regexp search function
- create standalone exe files with the help of tclkit 
	- all you need is inside
	- integrate your own tcl/tk packages (must be placed in the lib directory)
- ...

**create:**

- copy the repository complete (inlusive the lib directory).
- call the batch file makeTclTkIDE with the tk version nunmber as argument
	- eg. makeTclTkIDE 84
	- this will make TclTkIDE84.exe
- that's all!

![TclTkIDE](/TclTkIDE.GIF)

**example: create your own wish:**
- call TclTkIDExx.exe
- load wish.tcl
- push button with the tcl logo or press <F10>
- now its time to select your packages
	- select the sample package "hello1.1"
	- push the button "use selected file(s)"
- TclTkIDE create now the new exe file "wish.exe"

**todo:**

- implement a console
- bug fixes

TRY IT ;-)

I hope you have fun.

Greetings - kmatze (aka ma.ke.) - 08.05.2017





