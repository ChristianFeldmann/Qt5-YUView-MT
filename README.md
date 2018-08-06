# Qt5.11VS-MT
The essential Qt libraries and include files to compile YUView with visual studio 2015/2017. Compiled with MT.
These are meant to be used with apveyor. But of course they should also work on any other windows mashine to compile YUViwe. 
Because of the path handling of Qt, the files must be ckecked out into the directory C:\projects\Qt.

Windeployqt was patched in order to work with \MT as well (there is a bug in windeployqt).
