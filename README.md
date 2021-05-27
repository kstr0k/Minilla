# minil-arms-length

Runs `minil new`, `test`, `release` from scratch, but updates the generated skeleton with the actual module files, and maintains the `Changes` log. It's as if you `minil`-ized your project over and over again every time you make a new release. Release tags are generated as normal, but appear as branched off of the master branch.

Of course, at any time you can choose to turn the current release tag into an actual `minil` branch, and merge from `master` from then on. Or move development to the `minil` branch entirely.
