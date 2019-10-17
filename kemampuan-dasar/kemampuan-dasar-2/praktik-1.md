# kemampuan-dasar-2
# STEP 1
Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2 (master)
$ mkdir rhymes

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2 (master)
$ cd rhymes

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git init
Initialized empty Git repository in E:/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes/.git/

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ touch README.txt

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git add README.txt

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git commit -m 'First commit.'
[master (root-commit) 8ea4071] First commit.
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.txt

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ echo 'This repo is a collection of my favorite nursery rhymes.' >> README.t
xt

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.txt

no changes added to commit (use "git add" and/or "git commit -a")

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git diff
warning: LF will be replaced by CRLF in README.txt.
The file will have its original line endings in your working directory
diff --git a/README.txt b/README.txt
index e69de29..c83e022 100644
--- a/README.txt
+++ b/README.txt
@@ -0,0 +1 @@
+This repo is a collection of my favorite nursery rhymes.

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git add README.txt
warning: LF will be replaced by CRLF in README.txt.
The file will have its original line endings in your working directory

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git commit -m 'Added project overview to README.txt'
[master 76d8eb7] Added project overview to README.txt
 1 file changed, 1 insertion(+)

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        rhymes-master/

nothing added to commit but untracked files present (use "git add" to track)

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git add rhymes-master/all-around-the-mulberry-bush.txt
warning: LF will be replaced by CRLF in rhymes-master/all-around-the-mulberry-bush.txt.
The file will have its original line endings in your working directory

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   rhymes-master/all-around-the-mulberry-bush.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        rhymes-master/README.txt
        rhymes-master/hickory-dickory-dock.txt
        rhymes-master/hokey-pokey.txt
        rhymes-master/jack-and-jill.txt
        rhymes-master/old-mother-hubbard.txt
        rhymes-master/roses-are-red.txt
        rhymes-master/twinkle-twinkle.txt


Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git commit -m 'Added all-around-the-mulberry-bush.txt.'
[master 6caefd1] Added all-around-the-mulberry-bush.txt.
 1 file changed, 19 insertions(+)
 create mode 100644 rhymes-master/all-around-the-mulberry-bush.txt

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git add rhymes-master/jack-and-jill.txt
warning: LF will be replaced by CRLF in rhymes-master/jack-and-jill.txt.
The file will have its original line endings in your working directory

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git commit -m 'Added jack-and-jill.txt.'
[master 76310f6] Added jack-and-jill.txt.
 1 file changed, 12 insertions(+)
 create mode 100644 rhymes-master/jack-and-jill.txt

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git add .
warning: LF will be replaced by CRLF in rhymes-master/README.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in rhymes-master/hickory-dickory-dock.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in rhymes-master/hokey-pokey.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in rhymes-master/old-mother-hubbard.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in rhymes-master/roses-are-red.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in rhymes-master/twinkle-twinkle.txt.
The file will have its original line endings in your working directory

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git commit -m 'Added old-mother-hubbard.txt, twinkle-twinkle.txt, hokey-pok
ey.txt'
[master e7483bf] Added old-mother-hubbard.txt, twinkle-twinkle.txt, hokey-pokey.txt
 6 files changed, 70 insertions(+)
 create mode 100644 rhymes-master/README.txt
 create mode 100644 rhymes-master/hickory-dickory-dock.txt
 create mode 100644 rhymes-master/hokey-pokey.txt
 create mode 100644 rhymes-master/old-mother-hubbard.txt
 create mode 100644 rhymes-master/roses-are-red.txt
 create mode 100644 rhymes-master/twinkle-twinkle.txt

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git log
commit e7483bf5a6cad2bd521bcdcf5fe6e9c9543b5733 (HEAD -> master)
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:44:57 2019 -0400

    Added old-mother-hubbard.txt, twinkle-twinkle.txt, hokey-pokey.txt

commit 76310f61ccfc598be359d96fcee31c75bbe49a8e
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:44:09 2019 -0400

    Added jack-and-jill.txt.

commit 6caefd16a1fc43620fd6a3b0060f5d9cbaab5c86
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:43:25 2019 -0400

    Added all-around-the-mulberry-bush.txt.

commit 76d8eb735e3e6bc84fa83b88c049236e1db33060
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:39:44 2019 -0400

    Added project overview to README.txt

commit 8ea407186c5d8998a9eed2d4f44c5e1f6e894948
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:38:36 2019 -0400

    First commit.

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git log --oneline
e7483bf (HEAD -> master) Added old-mother-hubbard.txt, twinkle-twinkle.txt, hokey-pokey.txt
76310f6 Added jack-and-jill.txt.
6caefd1 Added all-around-the-mulberry-bush.txt.
76d8eb7 Added project overview to README.txt
8ea4071 First commit.

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git log -p
commit e7483bf5a6cad2bd521bcdcf5fe6e9c9543b5733 (HEAD -> master)
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:44:57 2019 -0400

    Added old-mother-hubbard.txt, twinkle-twinkle.txt, hokey-pokey.txt

diff --git a/rhymes-master/README.txt b/rhymes-master/README.txt
new file mode 100644
index 0000000..c83e022
--- /dev/null
+++ b/rhymes-master/README.txt
@@ -0,0 +1 @@
+This repo is a collection of my favorite nursery rhymes.
diff --git a/rhymes-master/hickory-dickory-dock.txt b/rhymes-master/hickory-dickory-dock.txt
new file mode 100644
index 0000000..a337f4c
--- /dev/null
+++ b/rhymes-master/hickory-dickory-dock.txt
@@ -0,0 +1,5 @@
+Hickory, dickory, dock,
+The mouse ran up the clock.
+The clock struck one,
+The mouse ran down!
+Hickory, dickory, dock.
diff --git a/rhymes-master/hokey-pokey.txt b/rhymes-master/hokey-pokey.txt
new file mode 100644
index 0000000..97f425b
--- /dev/null
+++ b/rhymes-master/hokey-pokey.txt
@@ -0,0 +1,16 @@
+You put your right foot in,
+You put your right foot out;
+You put your right foot in,
+And you shake it all about.
+You do the Hokey-Pokey,
+And you turn yourself around.
+That's what it's all about!
+
+You put your left foot in...
+You put your right hand in...
+You put your right side in...
+You put your nose in...
+You put your tail in...
+You put your head in...
+You put your whole self in...
+
diff --git a/rhymes-master/old-mother-hubbard.txt b/rhymes-master/old-mother-hubbard.txt
new file mode 100644
index 0000000..c91ff71
--- /dev/null
+++ b/rhymes-master/old-mother-hubbard.txt
@@ -0,0 +1,34 @@
+Old Mother Hubbard
+Went to the cupboard
+To fetch her poor dog a bone;
+But when she came there
+The cupboard was bare,
+And so the poor dog had none.
+She took a clean dish
+To get him some tripe;
+But when she came back
+He was smoking a pipe.
+She went to the grocer's
+To buy him some fruit;
+But when she came back
+He was playing the flute.
+
+She went to the baker's
+To buy him some bread;
+But when she came back
+The poor dog was dead.
+
+She went to the undertaker's
+To buy him a coffin;
+But when she came back
+The poor dog was laughing.
+
+She went to the hatter's
+To buy him a hat;
+But when she came back
+He was feeding the cat.
+
+The dame made a curtsey,
+The dog made a bow;
+The dame said, "Your servant."
+The dog said, "Bow wow!"
diff --git a/rhymes-master/roses-are-red.txt b/rhymes-master/roses-are-red.txtnew file mode 100644
index 0000000..efba165
--- /dev/null
+++ b/rhymes-master/roses-are-red.txt
@@ -0,0 +1,8 @@
+Roses are red
+-------------
+
+Roses are red
+Violets are blue
+Nobody loves GitHub
+More than government agencies do!
+
diff --git a/rhymes-master/twinkle-twinkle.txt b/rhymes-master/twinkle-twinkle.txt
new file mode 100644
index 0000000..5585462
--- /dev/null
+++ b/rhymes-master/twinkle-twinkle.txt
@@ -0,0 +1,6 @@
+Twinkle, twinkle, little star,
+How I wonder what you are.
+Up above the world so high,
+Like a diamond in the sky.
+Twinkle, twinkle, little star,
+How I wonder what you are.

commit 76310f61ccfc598be359d96fcee31c75bbe49a8e
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:44:09 2019 -0400

    Added jack-and-jill.txt.

diff --git a/rhymes-master/jack-and-jill.txt b/rhymes-master/jack-and-jill.txtnew file mode 100644
index 0000000..1596bce
--- /dev/null
+++ b/rhymes-master/jack-and-jill.txt
@@ -0,0 +1,12 @@
+Jack and Jill
+Went up the hill
+To fetch a pail of water.
+Jack fell down
+And broke his crown
+And Jill came tumbling after.
+Up Jack got
+And home did trot
+As fast as he could caper
+Went to bed
+And plastered his head
+With vinegar and brown paper.

commit 6caefd16a1fc43620fd6a3b0060f5d9cbaab5c86
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:43:25 2019 -0400

    Added all-around-the-mulberry-bush.txt.

diff --git a/rhymes-master/all-around-the-mulberry-bush.txt b/rhymes-master/all-around-the-mulberry-bush.txt
new file mode 100644
index 0000000..b77d989
--- /dev/null
+++ b/rhymes-master/all-around-the-mulberry-bush.txt
@@ -0,0 +1,19 @@
+All around the mulberry bush
+The monkey chased the weasel.
+The monkey thought 'twas all in fun.
+Pop! goes the weasel.
+
+A penny for a spool of thread,
+A penny for a needle.
+That's the way the money goes.
+Pop! goes the weasel.
+
+Up and down the City Road,
+In and out of the Eagle,
+That's the way the money goes.
+Pop! goes the weasel.
+
+Half a pound of tuppenney rice,
+Half a pound of treacle,
+Mix it up and make it nice,
+Pop! goes the weasel.

commit 76d8eb735e3e6bc84fa83b88c049236e1db33060
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:39:44 2019 -0400

    Added project overview to README.txt

diff --git a/README.txt b/README.txt
index e69de29..c83e022 100644
--- a/README.txt
+++ b/README.txt
@@ -0,0 +1 @@
+This repo is a collection of my favorite nursery rhymes.

commit 8ea407186c5d8998a9eed2d4f44c5e1f6e894948
Author: uciirmdni <suciramadhanirauf5@gmail.com>
Date:   Thu Oct 17 08:38:36 2019 -0400

    First commit.

diff --git a/README.txt b/README.txt
new file mode 100644
index 0000000..e69de29

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git remote add origin https://github.com/uciirmdni/rhymes.git

Anjelina Sari@AnjelinaSari MINGW32 /e/praxis-academy/kemampuan-dasar/kemampuan-dasar-2/rhymes (master)
$ git push -u origin master
Enumerating objects: 22, done.
Counting objects: 100% (22/22), done.
Delta compression using up to 2 threads
Compressing objects: 100% (19/19), done.
Writing objects: 100% (22/22), 2.74 KiB | 104.00 KiB/s, done.
Total 22 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/uciirmdni/rhymes.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

# STEP 2

Anjelina Sari@AnjelinaSari MINGW32 /e/Bob
$ git clone https://github.com/uciirmdni/rhymes.git
Cloning into 'rhymes'...
remote: Enumerating objects: 22, done.
remote: Counting objects: 100% (22/22), done.
remote: Compressing objects: 100% (17/17), done.
remote: Total 22 (delta 2), reused 22 (delta 2), pack-reused 0
Unpacking objects: 100% (22/22), done.

Anjelina Sari@AnjelinaSari MINGW32 /e/Bob
$ cd rhymes

Anjelina Sari@AnjelinaSari MINGW32 /e/Bob/rhymes (master)
$ git checkout -b hickory-dickory
Switched to a new branch 'hickory-dickory'

Anjelina Sari@AnjelinaSari MINGW32 /e/Bob/rhymes (hickory-dickory)
$ git add rhymes-master/hickory-dickory-dock.txt

Anjelina Sari@AnjelinaSari MINGW32 /e/Bob/rhymes (hickory-dickory)
$ git commit -m 'Added hickory-dickory-dock.txt.'
On branch hickory-dickory
nothing to commit, working tree clean

Anjelina Sari@AnjelinaSari MINGW32 /e/Bob/rhymes (hickory-dickory)
$ git push origin hickory-dickory
Total 0 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'hickory-dickory' on GitHub by visiting:
remote:      https://github.com/uciirmdni/rhymes/pull/new/hickory-dickory
remote:
To https://github.com/uciirmdni/rhymes.git
 * [new branch]      hickory-dickory -> hickory-dickory
