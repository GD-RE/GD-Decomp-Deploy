# GD Decomp Deploy

Used to build a Custom Geometry dash Decompiled Repository using the Geode-sdk-bindings to help as well as a python script
this script and PyBroma. Having these libraries on hand will allow for all of the following to take place. This 
software allows us to basically have and build a moving tent. In fact you don't even need git to use this. 
As a Dispace freak myself only Python and a C++ compiler is ever required.

## Features
- [x] Writes C++ Header files
- [x] Writes C++ Source files
- [x] Writes Found Data and class members into given header files / homes 
- [x] Installs CocosHeaders with extra stuff like the correct fmt library and FMOD
- [ ] Uninstaller (Coming Soon)
- [ ] Git CLI for making a repo.
- [ ] Tools for Updating headers and generating broma files from those header files (Maybe...)


## Motives

- The Possibility (or Threat) of Fast Releases by Robtop.

- Keeping functions in `.cpp` files in alphabetical order... even when some functions are incomplete and have no return types yet...

- To help me and other contributors with easily moving and transporting Geode's data along whenever an update releases.

- For making make transitions as smooth as possible when moving repos

- To be able to require only minimal amounts of planning while saving as much time and energy as possible for the user.

- Lazy Loading and File Creation with minimal amounts of effort


# How to Use 

You will need python 3.8 or higher and an msvc compiler for compiling PyBroma (another external python library that I made)

```
pip install -r reqiurements.txt
```


It's really meant to be used in a one-time use only scenario simillar to when you are moving houses 
however you could compile the python tool into an executable file using pyinstaller and run it that way. 
the tool is ran on the `click` python commandline library so the commandline should be faily readable 
and easy for me and anyone else to maintain. The tool is asynchronous to allow for concurrent tasks to 
be ran at hand just to help with one's impatience...

When You're all done you can delete the python script so that It doesn't overwrite your progress in the future.


