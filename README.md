## Fix for the vcbuild.exe Node.js npm install error. 
###32bit exe (works for 64 bit, but with limitations of 32 bit build)

### Notes:
0. Important! this seems to work with many chip architechure, don't be mad if it does not work for yours....with that said it sure beats trying before installing VS, etc.
1. To my knowedge the disadvatages of 32 bit would just affect script compile, not affect run performance (maybe someone can speak to that).<br>
2. If these files need to be taken down for legal issue, just let me know. I assume not as these files are freely available via the Express Edition of VS 2008.

### Why?:
I got really irritated with the vcbuild.exe issue for Node.JS npm installs. To me I really don’t want old (2005/2008) Visual Studio components in my dev environment…so here you go (just the directory you need). 

### Setup:
1. **Clone, download**, whatever these files into a directory. 
2. Then add the directory as an entry to the **PATH environmental variable** (Control Panel > Advanced Settings > Environmental Variables ).

Ex.: If you put the vcbuild.exe file here: `C:/Users/Me/Dir/vcbuild.exe` ,<br>
then add `C:/Users/Me/Dir;` as a new PATH variable.
