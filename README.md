# Mommessc.github.io
Website for Clément Mommessin's personal pages.
This website is built with [hugo](https://gohugo.io/) and uses the [blackburn](https://themes.gohugo.io/blackburn/) theme.

This is **greatly** inspired from [Millian Poquet's personal website](https://github.com/mpoquet/mpoquet.github.io/tree/hugo).

## How to update this website?

1. Hack files in the `code` branch. Check how it looks like by running `hugo server`.
2. Generate the static website into the `public` directory by running `hugo`.
3. Switch to the `master` branch
4. Move the static website to master's branch root: `rsync -r --exclude='.git/' --exclude='public/' public/ ./` (note that I did not include the option `--delete-after` in the command line compared to Millian's page)
5. `git add` all new material and modified files, commit and push the master branch.
6. Don't forget to switch back to the `code` branch for your next updates.

