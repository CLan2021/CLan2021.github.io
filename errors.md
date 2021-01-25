## error messages

### Attempt#1
catherine@LAPTOP-UO4E35IH:~/hacks/CLan2021.github.io/data$ git add iris-data-dirty.csv
catherine@LAPTOP-UO4E35IH:~/hacks/CLan2021.github.io/data$ git commit -m "add iris data csv"
[main 4f9568b] add iris data csv
 1 file changed, 151 insertions(+)
 create mode 100644 data/iris-data-dirty.csv
catherine@LAPTOP-UO4E35IH:~/hacks/CLan2021.github.io/data$ git push
Username for 'https://github.com': CLan2021
Password for 'https://CLan2021@github.com':
To https://github.com/CLan2021/CLan2021.github.io.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/CLan2021/CLan2021.github.io.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

### Attempt #2
catherine@LAPTOP-UO4E35IH:~/hacks/CLan2021.github.io/data$ git add iris-data-dirty.csv
catherine@LAPTOP-UO4E35IH:~/hacks/CLan2021.github.io/data$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   iris-data-dirty.csv

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../IMG_2246.JPG
catherine@LAPTOP-UO4E35IH:~/hacks/CLan2021.github.io/data$ git commit -m "add iris data csv"
[main 4f9568b] add iris data csv
 1 file changed, 151 insertions(+)
 create mode 100644 data/iris-data-dirty.csv
catherine@LAPTOP-UO4E35IH:~/hacks/CLan2021.github.io/data$ git push
Username for 'https://github.com': CLan2021
Password for 'https://CLan2021@github.com':
To https://github.com/CLan2021/CLan2021.github.io.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/CLan2021/CLan2021.github.io.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
