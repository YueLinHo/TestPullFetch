TestPullFetch
=============

Testing them via TortoiseGit

commit 1
commit 2
commit 3
commit 4
commit 5

steps:
 1. the master of repo 1 is on commit "5" (aa70c0b7dad170b50bc277c7505c981065c6386e)
 2. the master of repo 2 is on commit "3" (9d369a473bfb384912ec5541efeef760df3cd52e)
 3. repo 2 push master with force, so that origin/master of repo 2 is also on commit "3"
 4. repo 1 push master with force, so that remote is updated to "5".
 5. repo 2 do fetch&rebase
