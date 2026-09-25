0 - su betty switches user
1 - whoami prints effective user
2 - groups prints groups
3 - chown betty hello changes owner
4 - touch hello creates empty file
5 - chmod u+x adds execute for owner
6 - chmod ug+x,o+r adds exec owner/group read other
7 - chmod a+x adds exec for all
8 - chmod 007 gives all perms to other only (007)
9 - chmod 753 sets rwxr-x-wx
10 - chmod --reference copies mode from olleh
11 - find dirs and chmod a+x
12 - mkdir -m 751 my_dir
13 - chgrp school hello changes group
14 - chown vincent:staff * changes owner/group for all
15 - chown -h changes symlink owner
16 - chown --from changes only if owned by guillaume
