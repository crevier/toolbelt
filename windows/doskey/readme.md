My doskeys for windows
======================

This folder contains all the doskey I use on windows

Import doskeys
--------------

The doskeys are defined in dk files.

To import a dk file use this command

    doskey /MACROFILE=file.dk
  
run this command to check that every doskey are imported

    doskey /MACROS:ALL

Doskey files
------------

Each doskey file regroup a set of related doskey

### git.dk

This file contains all my doskey related to **GIT**

The available doskey :

  * `gitcb` return the name of the current branch
  * `gitpcb` push the current branch to the origin repository
  
