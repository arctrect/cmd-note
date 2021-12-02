# cmd-note - a script to take short quick notes

The script 'n' is designed to take quick, one line notes and store them locally,
and show a list of these notes.  

The script requires the following files in the home directory:  

+ `$HOME/.notes/notes.rc` the line contains the name of the current notes file.
+ `$HOME/.notes/temp` a temporary file used by the script 

## `n` - Default behaviour

Using `n` without any options will display a list of saved notes preceded
by their line number and creation date.  

## `n new` - add a new note

Adds a new note to the bottom of the list of notes

## `n del [line number]` - delete a note

Deletes the note at [line number]

## `n ins [line number]` - insert a note

insert a new note at line number

## `n file [file name]` - change your current notes file 

## Directories

The notes are stored in a file ,`notes` in a hidden directory, `~/.notes` in the
users `home` directory.
