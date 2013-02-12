##Here is what you do to get this repository working
##idea: I will assume you have downloaded this folder from github and that you have it away from 
#you working copy of sage. What we will then do is link this directory to the sage branch that you  
#will be working on. You will edit the files locally and pull and push them as we go.



#Make symlinks:
     sage -sh
     cd $SAGE_ROOT/devel/sage-main/sage/modules/
     ln -s /path/to/mods/sage/modules/ourshit .
     ln -s /path/to/mods/sage/modules/moreofourshit .
     cd $SAGE_ROOT/devel/sage-main/sage/rings/someshitthatexists/
     ln -s /path/to/mods/sage/modular/overconvergent/evenmoreofourshit .
