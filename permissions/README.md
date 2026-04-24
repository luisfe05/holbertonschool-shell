# Shell, permissions

Holberton School project to learn how permissions and ownership work in Linux.
Each script solves a different task using commands like `chmod`, `chown`, `chgrp`, and others.

## Tasks

| # | File | Description |
|---|------|-------------|
| 0 | `0-iam_betty` | Switches the current user to the user `betty`. |
| 1 | `1-who_am_i` | Prints the effective username of the current user. |
| 2 | `2-groups` | Prints all the groups the current user is part of. |
| 3 | `3-new_owner` | Changes the owner of the file `hello` to the user `betty`. |
| 4 | `4-empty` | Creates an empty file called `hello`. |
| 5 | `5-execute` | Adds execute permission to the owner of the file `hello`. |
| 6 | `6-multiple_permissions` | Adds execute permission to owner and group, and read permission to others, for `hello`. |
| 7 | `7-everybody` | Adds execute permission to owner, group, and others, for `hello`. |
| 8 | `8-James_Bond` | Sets the permissions of `hello` to `007`. |
| 9 | `9-John_Doe` | Sets the mode of `hello` to `-rwxr-x-wx` (753). |
| 10 | `10-mirror_permissions` | Sets the mode of `hello` to match the mode of `olleh`. |
| 11 | `11-directories_permissions` | Adds execute permission to all subdirectories of the current directory without changing regular files. |
| 12 | `12-directory_permissions` | Creates a directory called `my_dir` with permissions `751`. |
| 13 | `13-change_group` | Changes the group owner of `hello` to `school`. |
| 14 | `14-change_owner_and_group` | Changes the owner to `vincent` and the group to `staff` for all files and directories in the working directory. |
| 15 | `15-symbolic_link_permissions` | Changes the owner and group of the symbolic link `_hello` to `vincent` and `staff`. |
| 16 | `16-if_only` | Changes the owner of `hello` to `vincent` only if it is owned by `guillaume`. |

## How to run a script

```
./0-iam_betty
```

If the script does not have execute permissions:

```
chmod u+x 0-iam_betty
```

## Author

Luis — Holberton School
