# cascadiadataalliance.org
cascadia data alliance front page (based on https://gohugo.io/)

# How to modify/build this site

This is not like a typical GitHub Pages site:

* You have to build it yourself.
* Use [Hugo](https://gohugo.io) to build it, not jekyll
* The generated site lives in the `/docs` folder, and all
  files that Hugo generates in this folder need to be added 
  to the Git repository (in the `master` branch).

## Prerequisites

[Install Hugo](https://gohugo.io/getting-started/installing).
Hugo is a single executable. Be sure and download the appropriate 
one for your platform (Linux, Windows, Mac). Put this executable
in your PATH.

## Modifying the site

Clone this repository:

```
git clone https://github.com/FredHutch/cascadiadataalliance.org.git
cd cascadiadataalliance.org
```

Run the Hugo server:

```
hugo server
```

You can now visit the local version of the site at
[http://localhost:1313](http://localhost:1313).

You can now modfy the site in any way you choose,
following the [Hugo Documentation](https://gohugo.io/documentation/) if you run into any
problems.

## Checking in your changes

if you still have the `hugo server` command running, you should not need to rebuild the site. 
If you don't, just run `hugo` by itself. It will
rebuild the site without running a server.

Run `git status`. This will report any files you have modified or added, as well as new files 
that Hugo has generated (in the `docs` directory).

Run `git add` to make sure all the new files are added, 
then `git commit -a` to commit them (you'll be asked to
provide a commit message). Finally, run `git push` to
push your changes to github.

If all goes well, your changes should be live in a few moments on  [https://cascadiadataalliance.org](https://cascadiadataalliance.org).

## Troubleshooting

See the [commits page](https://github.com/FredHutch/cascadiadataalliance.org/commits/master) of this repo.
Next to your commit (which should be the most recent, on top)
you'll see either a green checkmark, an in progress indicator, or a red error indicator. Click on this to see 
any relevant error messages.

If you are still stuck, contact `scicomp`.
