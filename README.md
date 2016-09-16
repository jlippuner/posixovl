# posixovl
fork of https://sourceforge.net/projects/posixovl/ with minor modifications

Modifications I've made:

- removed encoding "special" characters (like :, ?, *, <, >) in paths, because 
  these are allowed characters (on Linux) and encoding : messes with emacs'
  lock files

