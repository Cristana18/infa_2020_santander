# infa_2020_santander
git diff
diff --git a/README.md b/README.md
index 21e60f8..285eafa 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,3 @@
-# infa_2020_ivanov
\ No newline at end of file
+# infa_2020_ivanov
+
+it\'s test project
git status
# On branch master
# Changes not staged for commit:
#   (use "git add <file>..." to update what will be committed)
#   (use "git checkout -- <file>..." to discard changes in working directory)
#
#    modified:   README.md
  $ git log
commit 8e2642d512b11ae43a97b0b4ac68e802d2626f14
Author: Ivanov Ivan <ivanov.ivan@someuniversity.edu>
Date:   Wed Nov 9 14:47:40 2016 +0300

    Added something to README

commit eec733a21cerfb66973998a9327aab735fa40ba4
Author: Ivanov Ivan <ivanov.ivan@someuniversity.edu>
Date:   Wed Nov 9 13:36:38 2016 +0300

    Initial commit
    $ git push
Username for 'https://github.com': <username>
Password for 'https://ivanov@github.com': <password>
To https://github.com/Ivanov/infa_2020_ivanov
   eec733a..8e2642d  master -> master
  $ git pull
Already up-to-date.
#
no changes added to commit (use "git add" and/or "git commit -a")
  git add README.md
-> git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#    modified:   README.md
  $ git commit -m "Added something to README"
[master 274f6d5] Added something to README
 Committer: Ivanov Ivan <ivanov.ivan@someuniversity.edu>

 1 file changed, 3 insertions(+), 1 deletion(-)
