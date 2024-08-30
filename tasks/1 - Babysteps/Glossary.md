`cd` - stands for "*Change directory*" and command do exactly what it says. If you want to change directory to specific folder, you need to give **relative** or **absolute** path.

**Parent directory** - a directory that contains more folders (subdirectories).

**Relative path** - path that starts from your current position (or position of some specific situations). Here's some examples of relative path:
`./file.txt` - Path to a file named `file.txt` in the current directory.
`./subdir/file.txt` - Path to a file named `file.txt` in the `subdir` folder (it's located in current folder)
`../subdir/file.txt` - Path to a file named `file.txt` inside a subdirectory called `subdir` of the parent directory (so it means that we exit from current directory to a directory, that is above us).

**Absolute path** - it's a full path, that comes from the root of file system. Examples:
`/home/user/documents/file.txt`
`C:\Users\User\Documents\file.txt`

`ls` - stands for "List" and actually shows the list of files and directories of selected folder. With some attributes, it can show additional information.

`mkdir` - stands for "Make directory" and just creates a directory in current or given folder.

`mv` - stands for "Move" and move files or directories from one place to another. Can be used for file renaming.

`rm` - stands for "Remove" and remove file or directory. 