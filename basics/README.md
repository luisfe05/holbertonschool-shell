# Shell, basics

Holberton School project to learn the basics of the Linux shell.
Each script solves a different task and is written in Bash.


## Tasks

| # | File | Description |
|---|------|-------------|
| 0 | `0-current_working_directory` | Prints the absolute path of the current working directory. |
| 1 | `1-listit` | Displays the contents of the current directory. |
| 2 | `2-bring_me_home` | Changes to the user's home directory. |
| 3 | `3-listfiles` | Displays the current directory contents in long format. |
| 4 | `4-listmorefiles` | Displays the contents including hidden files, in long format. |
| 5 | `5-listfilesdigitonly` | Displays the contents with UID and GID shown numerically. |
| 6 | `6-firstdirectory` | Creates the directory `my_first_directory` inside `/tmp/`. |
| 7 | `7-movethatfile` | Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`. |
| 8 | `8-firstdelete` | Deletes the file `betty`. |
| 9 | `9-firstdirdeletion` | Deletes the directory `my_first_directory` from `/tmp`. |
| 10 | `10-back` | Changes to the previous working directory. |
| 11 | `11-lists` | Lists files of the current directory, parent, and `/boot` in long format. |
| 12 | `12-file_type` | Prints the type of the file `/tmp/iamafile`. |
| 13 | `13-symbolic_link` | Creates a symbolic link to `/bin/ls` named `__ls__`. |
| 14 | `14-copy_html` | Copies `.html` files to the parent directory if they don't exist there or are newer. |
| 15 | `15-lets_move` | Moves all files starting with an uppercase letter to `/tmp/u`. |
| 16 | `16-clean_emacs` | Deletes files ending with `~`. |
| 17 | `17-tree` | Creates the directories `welcome/`, `welcome/to/`, and `welcome/to/school`. |

## How to run a script

```
./0-current_working_directory
```

If the script does not have execute permissions:

```
chmod u+x 0-current_working_directory
```

## Author

Luis — Holberton School
