
# Feature

## Start a feature

This will checkout a new branch from your stable one, following naming pattern.

	git tw feature start my-killer-feature

## Finish feature
After creating a release (see below), you have to merge feature back, where is how to do

	git tw feature finish my-killer-feature 

# Release 

## Start a release

	git tw release start my-killer-release

## Add feature to a release

	git tw feature merge-into-release 3346

# settings
which is the stable branch (stable:master)
prefixing feature branches (feature: feature/)