# mis-fix-travis
misspell-fixer travis-ci integrator

idea:
setup a travis-artefact that fetches the "diff" of 2 commits and runs the misspell-fixer just on these.

This is, because misspell-fixer can be quite slow. having 1000 files, but last commit touches just 3 of them, and assuming all other stuff is clean - this will bring the performance.

todo:
- find out, how we can access in travis the HEAD vs HEAD^ files.
- run misspell-fixer against this.
- find out, how to comunicate the stuff we just found.
