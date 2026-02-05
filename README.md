### Project 1: File Organizer CLI (`organizer.sh`)
this is my very first bash project i am creating which is a file organizer which does the following.
it will look at the extention of the file and based on that, it will create a category which is like 
Documents, Coding, audio files, videos.

the first version of the app will have the following features to get it started.
- you will have the option on directory to operate on with -d flag or if none, current directory.
- you will also have verbose mode which will show more output to the screen.
- if the folders don't exist, they will be created.
- all actions will be logged to the appropriate directory

**the lists below are what i want the full version to have in the near future**
Must-have flags & features:
- `-d <dir>` → target directory (default: current)
- `-v` → verbose mode
- `-n` → dry-run (show what would happen)
- `-c` → config file (e.g. `.organizer.conf` with custom rules)
- Organize by: extension, date (YYYY-MM-DD), or custom regex
- Skip hidden files by default
- Create folders if they don’t exist
- Log all actions to `~/.organizer.log` or appropriate location.
