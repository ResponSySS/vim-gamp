GTags And Man Proto (GAMP)
========

SUMMARY
-------

GAMP is a very lightweight Vim completion system for libc functions and virtually any other functions.

REQUIREMENTS
------------

Mandatory:
  
  * Linux-like OS with a shell and a manpage system
  * Vim 'laststatus' must be set to 2
    
Optional:
  
  * GNU Global (its use can be disabled)

FEATURES
--------

  * 3 modes:
    * Complete function prototype in completion mode
    * Hint for function prototype in statusline mode
    * Do all of the above when using both modes
  * Take definition from all the function manpages from section 2 and 3
    ( system and library (including libc) calls )
  * Take definition of any function using GNU Global GTags system
  * If not using Global GTags, there is no dependency
  * Real-time updating and no maintenance required if using  gtags.vim  
    auto-update feature


INSTALL DETAILS
---------------

Inside the GAMP.tar archive are two files that you have to put in the appropriate location of your vim folder (for me, it's  $HOME/.vim ).
You can do it using your graphical archive manager (like  file-roller ), or with the command-line with:

    $ tar -xvf  GAMP.tar

to extract the archive, and:

    $ cp  doc/gtags-and-man-proto.txt      $HOME/.vim/doc
    $ cp  plugin/gtags-and-man-proto.vim   $HOME/.vim/plugin

to copy the files.
