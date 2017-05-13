# git-paillao

Make a release easily and avoid to get fired, inspired by a true story.

## How it work

- create a branch from develop
- merge develop into the created branch
- push the new branch to origin
- get back to develop

## Usage

`git-paillao <release_number>`

`<release_number>` is required, is use to name the new branch with the prefix `release`, for instance:

`git-paillao v0.0.1` will generate a branch call `release/v0.0.1`.

## Installation (not necessary if you install the npm package)

- clone the repository or just copy the files.
- make a link in your $PATH aiming the script.
- make it executable by doing `chmod +x $PATH/git-paillao`.
- now you can call it with `git paillao`, enjoy.