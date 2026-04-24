# Shell, I/O Redirections and filters

Holberton School project to learn I/O redirections and text filters in the shell.
Each script solves a different task using commands like `cat`, `head`, `tail`, `grep`, `find`, `sort`, `uniq`, `tr`, `cut`, `rev`, and redirections (`>`, `>>`, `|`).

## Tasks

| # | File | Description |
|---|------|-------------|
| 0 | `0-hello_world` | Prints exactly `"Hello, World"` followed by a new line. |
| 1 | `1-confused_smiley` | Displays the confused smiley `"(Ôo)'`. |
| 2 | `2-hellofile` | Displays the content of the file `/etc/passwd`. |
| 3 | `3-twofiles` | Displays the content of `/etc/passwd` and `/etc/hosts`. |
| 4 | `4-lastlines` | Displays the last 10 lines of `/etc/passwd`. |
| 5 | `5-firstlines` | Displays the first 10 lines of `/etc/passwd`. |
| 6 | `6-third_line` | Displays the third line of the file `iacta`. |
| 7 | `7-file` | Creates a file with a tricky name containing special characters, filled with the text `Best School`. |
| 8 | `8-cwd_state` | Writes the result of `ls -la` into a file called `ls_cwd_content`. |
| 9 | `9-duplicate_last_line` | Duplicates the last line of the file `iacta`. |
| 10 | `10-no_more_js` | Deletes all regular files with a `.js` extension in the current directory and its subdirectories. |
| 11 | `11-directories` | Counts the number of directories and subdirectories in the current directory. |
| 12 | `12-newest_files` | Displays the 10 newest files in the current directory, one per line, sorted from newest to oldest. |
| 13 | `13-unique` | Takes a list of words from standard input and displays only lines that appear exactly once. |
| 14 | `14-findthatword` | Displays lines containing the pattern `root` from `/etc/passwd`. |
| 15 | `15-countthatword` | Counts the number of lines containing the pattern `bin` in `/etc/passwd`. |
| 16 | `16-whatsnext` | Displays lines containing the pattern `root` and the 3 lines after them in `/etc/passwd`. |
| 17 | `17-hidethisword` | Displays all lines in `/etc/passwd` that do not contain the pattern `bin`. |
| 18 | `18-letteronly` | Displays all lines of `/etc/ssh/sshd_config` starting with a letter (uppercase or lowercase). |
| 19 | `19-AZ` | Replaces all characters `A` with `Z` and `c` with `e` from standard input. |
| 20 | `20-hiago` | Removes all `c` and `C` characters from standard input. |
| 21 | `21-reverse` | Reverses its input. |
| 22 | `22-users_and_homes` | Displays all users and their home directories, sorted by user. |

## How to run a script

```
./0-hello_world
```

If the script does not have execute permissions:

```
chmod u+x 0-hello_world
```

## Author

Luis — Holberton School
