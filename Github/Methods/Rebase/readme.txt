1.pick an early good commit.
2.click 'browse files' at this commit, it will show up as tree branch
with a hexadecimal name.
3.click the name and make a new named branch like main_recovery.
4.make this branch the default branch.
4b.OPTIONAL: in the main/master branch, click the last commit and create
a backup branch as above method named something like main_bad_commit1,
in case you want to preserve it.
5.Delete the main/master branch.
6.Pick the last commit in the main_recovery branch, browse files,
make a new main/master branch out of it by clicking the hex name -> create branch.
7.Make this branch the default.
7b.OPTIONAL: delete the main_recovery branch.

