# lab05.1
rebase again
updating before conflict
updating 4th line

C:\Users\Acer>E:

E:\>cd  sneha1mv22cs155/gitlab

E:\Sneha1MV22CS155\gitlab>mkdir exp7

E:\Sneha1MV22CS155\gitlab>cd exp7

E:\Sneha1MV22CS155\gitlab\exp7>git init
Initialized empty Git repository in E:/Sneha1MV22CS155/gitlab/exp7/.git/

E:\Sneha1MV22CS155\gitlab\exp7>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git config --global --list
user.email=you@example.com
user.name=Your Name

E:\Sneha1MV22CS155\gitlab\exp7>git config --global --unset-all user.name

E:\Sneha1MV22CS155\gitlab\exp7>git config --global --unset-all user.email

E:\Sneha1MV22CS155\gitlab\exp7>git config --global --list

E:\Sneha1MV22CS155\gitlab\exp7>git config --global user.name"sneha"

E:\Sneha1MV22CS155\gitlab\exp7>git config --global user.email"sneha251104@gmail.com"

E:\Sneha1MV22CS155\gitlab\exp7>git config --global --list

E:\Sneha1MV22CS155\gitlab\exp7>git config --global user.name "sneha"

E:\Sneha1MV22CS155\gitlab\exp7>git config --global user.email "sneha251104@gmail.com"

E:\Sneha1MV22CS155\gitlab\exp7>git config --global --list
user.name=sneha
user.email=sneha251104@gmail.com

E:\Sneha1MV22CS155\gitlab\exp7>git commit -m "created new file"
[master (root-commit) 83d9def] created new file
 1 file changed, 1 insertion(+)
 create mode 100644 file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git checkout -b featurebranch
Switched to a new branch 'featurebranch'

E:\Sneha1MV22CS155\gitlab\exp7>file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git commit -m "addition"
[featurebranch 19ae768] addition
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp7>file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git commit -m "subtraction"
[featurebranch 535c56c] subtraction
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp7>git tag v1.0

E:\Sneha1MV22CS155\gitlab\exp7>git log
commit 535c56cf8625f3ea2a8eb393c090b35305009056 (HEAD -> featurebranch, tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:40:07 2024 +0530

    subtraction

commit 19ae768e17e6cdfb0e0ec2406bad954f724d49ed
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:39:19 2024 +0530

    addition

commit 83d9def789771b6c9215431b7ccd67c05b0ee5e6 (master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:37:50 2024 +0530

    created new file

E:\Sneha1MV22CS155\gitlab\exp7>file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git commit -m "multiplication"
[featurebranch b12e90d] multiplication
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp7>file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp7>git commit -m "division"
[featurebranch 7ae47c4] division
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp7>git tag v2.0

E:\Sneha1MV22CS155\gitlab\exp7>git log
commit 7ae47c4f065d301b349e83a5ea03ac1b0635a033 (HEAD -> featurebranch, tag: v2.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:53 2024 +0530

    division

commit b12e90d0990e481de6d6da4a503552e11fb9f08e
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:21 2024 +0530

    multiplication

commit 535c56cf8625f3ea2a8eb393c090b35305009056 (tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:40:07 2024 +0530

    subtraction

commit 19ae768e17e6cdfb0e0ec2406bad954f724d49ed
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:39:19 2024 +0530

    addition

commit 83d9def789771b6c9215431b7ccd67c05b0ee5e6 (master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:37:50 2024 +0530

    created new file

E:\Sneha1MV22CS155\gitlab\exp7>git tag -l
v1.0
v2.0

E:\Sneha1MV22CS155\gitlab\exp7>git tag -d v1.0
Deleted tag 'v1.0' (was 535c56c)

E:\Sneha1MV22CS155\gitlab\exp7>git tag -d v2.0
Deleted tag 'v2.0' (was 7ae47c4)

E:\Sneha1MV22CS155\gitlab\exp7>git tag -l

E:\Sneha1MV22CS155\gitlab\exp7>git tag v1.0 b12e90d0990e481de6d6da4a503552e11fb9f08e

E:\Sneha1MV22CS155\gitlab\exp7>git log
commit 7ae47c4f065d301b349e83a5ea03ac1b0635a033 (HEAD -> featurebranch)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:53 2024 +0530

    division

commit b12e90d0990e481de6d6da4a503552e11fb9f08e (tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:21 2024 +0530

    multiplication

commit 535c56cf8625f3ea2a8eb393c090b35305009056
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:40:07 2024 +0530

    subtraction

commit 19ae768e17e6cdfb0e0ec2406bad954f724d49ed
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:39:19 2024 +0530

    addition

commit 83d9def789771b6c9215431b7ccd67c05b0ee5e6 (master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:37:50 2024 +0530

    created new file

E:\Sneha1MV22CS155\gitlab\exp7>git tag v2.0

E:\Sneha1MV22CS155\gitlab\exp7>git log
commit 7ae47c4f065d301b349e83a5ea03ac1b0635a033 (HEAD -> featurebranch, tag: v2.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:53 2024 +0530

    division

commit b12e90d0990e481de6d6da4a503552e11fb9f08e (tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:21 2024 +0530

    multiplication

commit 535c56cf8625f3ea2a8eb393c090b35305009056
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:40:07 2024 +0530

    subtraction

commit 19ae768e17e6cdfb0e0ec2406bad954f724d49ed
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:39:19 2024 +0530

    addition

commit 83d9def789771b6c9215431b7ccd67c05b0ee5e6 (master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:37:50 2024 +0530

    created new file

E:\Sneha1MV22CS155\gitlab\exp7>git show b12e90d0990e481de6d6da4a503552e11fb9f08e
commit b12e90d0990e481de6d6da4a503552e11fb9f08e (tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:21 2024 +0530

    multiplication

diff --git a/file1.txt b/file1.txt
index 9f979b4..d7b8492 100644
--- a/file1.txt
+++ b/file1.txt
@@ -1,3 +1,4 @@
 master
 addition
-subtraction
\ No newline at end of file
+subtraction
+multiplication
\ No newline at end of file

E:\Sneha1MV22CS155\gitlab\exp7>git show 83d9def789771b6c9215431b7ccd67c05b0ee5e6
commit 83d9def789771b6c9215431b7ccd67c05b0ee5e6 (master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:37:50 2024 +0530

    created new file

diff --git a/file1.txt b/file1.txt
new file mode 100644
index 0000000..96677a8
--- /dev/null
+++ b/file1.txt
@@ -0,0 +1 @@
+master
\ No newline at end of file

E:\Sneha1MV22CS155\gitlab\exp7>git log -n 1 83d9def789771b6c9215431b7ccd67c05b0ee5e6
commit 83d9def789771b6c9215431b7ccd67c05b0ee5e6 (master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:37:50 2024 +0530

    created new file

E:\Sneha1MV22CS155\gitlab\exp7>git log -n 3 7ae47c4f065d301b349e83a5ea03ac1b0635a033
commit 7ae47c4f065d301b349e83a5ea03ac1b0635a033 (HEAD -> featurebranch, tag: v2.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:53 2024 +0530

    division

commit b12e90d0990e481de6d6da4a503552e11fb9f08e (tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:21 2024 +0530

    multiplication

commit 535c56cf8625f3ea2a8eb393c090b35305009056
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:40:07 2024 +0530

    subtraction

E:\Sneha1MV22CS155\gitlab\exp7>git log -n 1 b12e90d0990e481de6d6da4a503552e11fb9f08e
commit b12e90d0990e481de6d6da4a503552e11fb9f08e (tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:21 2024 +0530

    multiplication

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="Sneha" --since="2024-01-01" --until="2024-02-06"

E:\Sneha1MV22CS155\gitlab\exp7>git log --author= "Sneha" --since= "2024-01-01" --until= "2024-02-06"
fatal: ambiguous argument 'Sneha': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="Sneha"--since= "2024-01-01"--until= "2024-02-06"
fatal: ambiguous argument '2024-01-01--until=': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log--author="Sneha"--since= "2024-01-01"--until= "2024-02-06"
git: 'log--author=Sneha--since=' is not a git command. See 'git --help'.

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha"--since= "2024-01-01"--until= "2024-02-06"
fatal: ambiguous argument '2024-01-01--until=': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha" --since= "2024-02-06" --until= "2024-02-06"
fatal: ambiguous argument '2024-02-06': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha" --since= "2024-02-05" --until= "2024-02-06"
fatal: ambiguous argument '2024-02-05': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha" --since= "2024-02-05"--until= "2024-02-06"
fatal: ambiguous argument '2024-02-05--until=': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha" --since= "2024-02-05"--until= "2024-02-06"
fatal: ambiguous argument '2024-02-05--until=': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha"--since= "2024-02-05"--until= "2024-02-06"
fatal: ambiguous argument '2024-02-05--until=': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha"--since="2024-02-05"--until="2024-02-06"

E:\Sneha1MV22CS155\gitlab\exp7>git log --author="sneha" --since="2024-02-01" --until="2024-02-06"
commit 7ae47c4f065d301b349e83a5ea03ac1b0635a033 (HEAD -> featurebranch, tag: v2.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:53 2024 +0530

    division

commit b12e90d0990e481de6d6da4a503552e11fb9f08e (tag: v1.0)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:41:21 2024 +0530

    multiplication

commit 535c56cf8625f3ea2a8eb393c090b35305009056
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:40:07 2024 +0530

    subtraction

commit 19ae768e17e6cdfb0e0ec2406bad954f724d49ed
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:39:19 2024 +0530

    addition

commit 83d9def789771b6c9215431b7ccd67c05b0ee5e6 (master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 6 06:37:50 2024 +0530

    created new file

E:\Sneha1MV22CS155\gitlab\exp7>
