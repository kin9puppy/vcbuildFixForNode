## Fix for the vcbuild.exe Node.js npm install error. 
###(32bit exe (works for 64 bit, but with limitations of 32 bit))

### Why?:
I got really irritated with the vcbuild.exe issue for Node.JS npm installs. To me I really don’t want old (2005/2008) Visual Studio components in my dev environment…so here you go (just the directory you are looking for). 

Clone, download, whatever these files into a directory, then to the PATH environmental variable (Control Panel > Advanced Settings > Environmental Variables ). Add the directory path for these files (Ex. If vcbuild.exe is at C:/Users/Me/Dir/vcbuild.exe then add ‘C:/Users/Me/Dir’).

