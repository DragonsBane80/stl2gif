Takes a 3d model in STL and renders a quick isometric animation about two axes then does a crazy undo thing and loops all nice

To run headless, you need something akin to osmesa installed (sudo apt-get install libosmesa6-dev).

Command: python3 stl2gif.py -i <stl file>

WARNING: THIS AUTO INSTALLS A FEW LIBRARIES SO IF YOU HAVE IMPORTANT DIFFERENT VERSIONS OF THESE LIBRARIES FOR OTHER PYTHON SCRIPTS CHECK BEFORE RUNNING

LIBRARY REQUIREMENTS: numpy, trimesh, pyrender, imageio, pillow

![demo](example%20output.gif)

Forked from https://github.com/adamdevmedia/stl2gif/ 
If you found this useful consider tossing them a donation: https://www.buymeacoffee.com/adamdevmedia
