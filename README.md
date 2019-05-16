a jUnit Results viewer based on LukeJPreston's Junit-viewer project
https://github.com/lukejpreston/junit_viewer

Prerequisites: 
1. Currently you need to have a running instance of chrome for the script to execute successfully. 
2. Update the chrome.exe path if necessary
3. Drag and Drop the "JunitViewer.lnk" shortcut to your taskbar
4. Git must be installed

Usage:
1. Save your Junit XML files into the "results" subdirectory
2. start a chrome instance
3. run the JunitViewer.lnk or the "run.sh" script
4. ...
5. Profit!

TODO: 
1. Make generic for system browser
2. Fix the running instance issue
3. upgrade to xunit-viewer
4. Currently it is necessary to issue a Ctrl-C in the terminal window to stop the application, this should probably be an "Any Key" dealy.
