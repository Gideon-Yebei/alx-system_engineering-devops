#  Bash shell scripts

0.  [0-iam_betty](0-iam_betty)
    - switches the current user to the user betty.
1.  [1-who_am_i](1-who_am_i)
    - prints the effective username of the current user.
2.  [2-groups](2-groups)
    - prints all the groups the current user is part of.
3.  [3-new_owner](3-new_owner)
    - changes the owner of the file [hello](hello) to the user betty
4.  [4-empty](4-empty)
    - creates an empty file [hello](hello)
5.  [5-execute](5-execute)
    - adds execute permission to the owner of the file [hello](hello)
6.  [6-multiple-permissions](6-multiple-permissions)
    - adds execute permission to the owner and the group owner, and read permission to other users, to the file [hello](hello)
7.  [7-everybody](7-everybody)
    - adds execution permission to the owner, the group owner and the other users, to the file [hello](hello)
8.  [8-James_Bond](8-James_Bond)
    - sets the permission to the file [hello](hello) as follows:
      - Owner: no permission at all
      - Group: no permission at all
      -  Other users: all the permissions
9.  [9-John_Doe](9-John_Doe)
    - sets the mode of [hello](hello) to `-rwxr-x-wx 1 root root 0 Dec  7 03:24 hello`
10. [10-mirror_permissions](10-mirror_permissions)
    - sets the mode of the file [hello](hello) the same as [olleh’s](olleh) mode.
    - used the `--reference=RFILE` option
    - works for different modes of [olleh](olleh)
11. [11-directories_permissions](11-directories_permissions)
    -  adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
    -  Regular files should not be changed.
    -  `-R --recussive` option
12. [12-directory_permissions](12-directory_permissions)
    - creates a directory called my_dir with permissions 751 in the working directory.
    - `-m --mode=MODE` option for permissions
13. [13-change_group](13-change_group)
    - changes the group owner to school for the file [hello](hello)