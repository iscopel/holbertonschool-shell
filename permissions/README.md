# permissions
0-iam_betty: switches the current user to betty
1-who_am_i: prints the effective username of the current user
2-groups: prints all the groups the current user is part of
3-new_owner: changes the owner of the file hello to betty
4-empty: creates an empty file called hello
5-execute: adds execute permission to the owner of the file hello
6-multiple_permissions: adds execute to owner and group, read to others, on hello
7-everybody: adds execute permission to everybody on hello
8-James_Bond: sets hello to no permissions for owner and group, all for others
9-John_Doe: sets the mode of hello to -rwxr-x-wx
10-mirror_permissions: sets the mode of hello the same as olleh
11-directories_permissions: adds execute permission to all subdirectories
12-directory_permissions: creates the directory my_dir with permissions 751
13-change_group: changes the group owner of hello to school
14-change_owner_and_group: changes owner to vincent and group to staff for all files
15-symbolic_link_permissions: changes owner and group of the symbolic link _hello
16-if_only: changes the owner of hello to vincent only if owned by guillaume
