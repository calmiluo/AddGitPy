# AddGitPy

in TEAM camliluo,  create a repo but empty, no member can be added / invited, just waiting files added in repo

create readme file in local pycharm:

clone from the camliluo repo, origin is calmiluo
enter pycharm, use commands to create readme file as 1st file.

$echo "# AddGitPy" >> README.md
$git init

$git add README.md

$git commit -m "first commit"

$git remote add origin https://github.com/calmiluo/AddGitPy.git

$git push -u origin master


Username for 'https://github.com': luoiupui
Password for 'https://luoiupui@github.com':


change VCS | git |remotes
origin: add username / password

modify readme file

VCS | Git | commit |push

the repo of calmiluo will updated.

if more files need, add as work directly on master branch in calmiluo's repo,
no pull requestes appear, it 's only on one branch of master.

if not more files need, go to another user, the member will fork and clone, then modify files.

the current local AddGitPy will be saved, but another secondary folder will use to allow member
clone repo, (the name is the same, so must in different folder).
the upstream in ./AddGitpy/
the member's folked origin in

./Members_LUO/AddGitPy/
./Members_CQ/AddGitPy/

3 parts: one owner with team who created original files and then stop,
two members. member folk and add new files





