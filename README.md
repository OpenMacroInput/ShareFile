# ShareFile
Tutorial and explanation of how to use ShareFile respository in the project.


To summarized it, Open Macro input works on some basic principle.
- All input are converted in named boolean value.
  - Example: IsLeftMousePress `true` or `false` 
- All the configuration is done by modifing files
  - Example: 
    - `.miditoboolean` convert midi key to name boolean
    - `.keyboardtoboolean` convert keyboard key to name boolean
    - `.apptoboolean` convert application focus to name boolean
    - `.apptoboolean` convert application focus to name boolean
    - `.screenlocations` convert part of the screen to name boolean 
- To do action you can trigger `Shortcut` and `Command Line`
  - Shortcut are text without space 
    - ` 📋✂️ 1000> 📋→` This line will/could cut selection wait a second and past.
  - Command line are text split by `\n` 
    - `In 100| winkey:s:space` This line will stroke space in 100 milliseconds.


As my software is based on files store near the executable on external specified folder.
It means that you can easily make library for you and/or share it with friends and the community.
The design of the app was created with that in mind.

So if you see a Git Repository with `ShareFile_`, it means that it is specific place to share this file with the community.


## List of current `ShareFile_`

Find them all here:  
https://github.com/OpenMacroInput?tab=repositories&q=ShareFile_&type=&language=&sort=  

Where to learn how to use those file ?
https://github.com/OpenMacroInput/Documentation/tree/main/FileExtension
