### Project 1: File Organizer CLI (`organizer.sh`)
this is my very first bash project i am creating which is a file organizer which does the following.
it will look at the extention of the file and based on that, it will create a category which is like 
Documents, Coding, audio files, videos.

the first version of the app will have the following features to get it started.
- you will have the option on directory to operate on with -d flag or if none, current directory.
- you will also have verbose mode which will show more output to the screen.
- if the folders don't exist, they will be created.
- all actions will be logged to the appropriate directory

## specify a directory

you can specify a directory with -d option. if you dont specify, it will be taking that the operation be done in the directory you're in. you can't specify a -d option without adding the directory you want the program to operate on, also you can't specify an invalid directory. also the program doesn't support relative path, only absolute path for now, in the future, i will add it.

```bash
organizer [-dv] [-n]
```

the program does support also verbose mode which will let you know what will happen everything in verbose mode. you can specify the -d option and the -v together to specify a custom dir and with verbose mode.

also the program supports the -n option which lets you see what would happen verbosely without actually doing anything for real. it is a simulation of what would happen in case you do this without the -n option. you can specify other options like -d to see what would happen but the -v option doesn't have any effect since dry run mode in the -n option is already verbose.

flags & features the program has right now:
- [ x ]`-d <dir>` → target directory (default: current)
- [ x ]`-v` → verbose mode
- [ x ]`-n` → dry-run (show what would happen)
- [ x ]Create folders if they don’t exist
