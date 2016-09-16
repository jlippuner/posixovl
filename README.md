# posixovl
fork of https://sourceforge.net/projects/posixovl/ with minor modifications

Modifications I've made:

- removed encoding "special" characters (like :, ?, *, <, >) in paths, because 
  these are allowed characters and encoding : messes with emacs' lock files
- removed link function, i.e. the file system will not support hardlinks
- removed the -F option, as I want permissions, owners, and symlinks to be 
  stored in HCBs by default
