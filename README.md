# pyjgeutil
Collection of Python Utility libraries utility tools relating to math, physics, computer science by Jerry G. Eldridge.

Some of the scripts like graphics_cv.py use opencv-python (https://pypi.org/project/opencv-python/) and others
like BasicShapes.py use 3D Viewer from the recent Windows Fall Creator's Update for viewing 3D .obj files for graphics.
Most scripts are text based and use Python27 like WinPython27 (http://winpython.sourceforge.net/) for running the
the scripts. extrusion.py uses tripy (https://pypi.org/project/tripy/).

Requirements

Winpython27 and in its command shell: 'pip install opencv-python' and 'pip install tripy'.

The utility folder 'pyjgeutil/_PythonJGE/Utility/' is assumed to be stored in a folder
like 'C:\_PythonJGE\Utility' by default in the sample scripts or dependencies from its
folder placed in the folder where a python script uses it. And,
'import sys' and  'sys.path.insert(0,r"C:\_PythonJGE\Utility")' in a script that
uses the utility points to the folder where the utility scripts are place. Then for
example "import affine as aff" makes use of a script. The 3D .obj creating scripts
point to a folder "C:\_BigData\_3D\my_scenes" by defining
BIGDATA = r"C:/_BigData/_3D/my_scenes/" in those scripts and that folder should be
created or another and BIGDATA adjusted for change to save the created .obj files to
that common folder.
