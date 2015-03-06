# LibXenoverse
Dragon Ball Xenoverse Modding Tools and Library.

Simple library to handle Dragon Ball Xenoverse's file formats. Tested on the Xbox 360 version's files so far and hopefully PC when it's released.

You can also integrate LibXenoverse into your own applications if you wish to add support for these files on a custom game engine, previewer, plugin, etc. Simply build LibXenoverse.lib and link it.

#### System Requirements
OS
* Microsoft Windows (XP 32-bit or higher).

#### Building
- A solution for Visual Studio Community 2013. Only 32-bit Release and Debug builds supported for now.

If the LIBXENOVERSE_FBX_SUPPORT preprocessor flag is defined, you'll need to download the latest version of the FBX SDK and change the include/lib directories accordingly. This flag enables the FBX Importing/Exporting functionality.


#### Builds
Win32 builds of the tools are provided on the /bin/ directory.

#### Modding the game
It's recommended to use the data folder inside of data2.cpk to override the files from data.cpk. It's much smaller and faster to repack than the main big data.cpk. Use the CPKPack tool to extract and repack Dragon Ball Xenoverse's CPK files.

####License
(todo)