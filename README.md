# posixovl
fork of https://sourceforge.net/projects/posixovl/ with minor modifications

Modifications I've made:

- removed encoding "special" characters (like :, ?, *, <, >) in paths, because 
  these are allowed characters (on Linux) and encoding ':' messes with emacs'
  lock files
- change mode of symlink placeholders and make them readable for all, so that
  they can be synced with rsync or other tools
