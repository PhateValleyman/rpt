TODO
====

`repo-update.py`
----------------

 - Fix Linux / OS X missing output: fixed on one, but broke the other.
 - Handle repositories with submodules (update submodules as well)
 - Add `--stash` parameter to stash changes and pull (for Git repos)
 - [DONE] Add `<repo_name>` argument to specify repo (just updates that repo)
 - [DONE] Add `<dir_name>` argument to specify repository directory (dir where repos are) to update all repos in
 - [DONE] Add config-file that specifies extra repo directories to work with

`repo-status.py`
----------------

 - Display 'has unpushed commits'
 - [DONE] Fix race condition when printing (multiple lines are printed on the same line)
