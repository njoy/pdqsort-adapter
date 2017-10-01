# pdqsort-adapter
A repository which adapts Orson Peters's implementation of [Pattern Defeating Quicksort](https://github.com/orlp/pdqsort) repository for use in the NJOY21 build scheme.


## Git Subtree
This repository uses a git subtree for the directory `src/orlp`. The remote from which the subtree is made is located at [https://github.com/orlp/pdqsort.git](https://github.com/orlp/pdqsort.git). Equivalently, you can use the ssh location at `git@github.com:orlp/pdqsort.git`.

To facilitate updating the subtree when it gets updated upstream, do the following:

```bash
# This only needs to be done once
git remote add orlp https://github.com/orlp/pdqsort.git

# Do this when you need to update the subtree
git subtree pull --prefix=src orlp master
```

# License
The code contained in this directory is covered by the license contained in the [LICENSE](LICENSE) file. The code in the `src` directory is covered by it's own [license](src/orlp/license.txt)

