# jekyll-foundation-6-starter

Start [a github pages](https://pages.github.com/) website powerd by [Jekyll](http://jekyllrb.com/docs/quickstart/) using [Foundation/SCSS](http://foundation.zurb.com/sites/docs/installation.html#command-line-tool.html) in under 5 minutes! 

### What it is.

Ever wanted a simple but nice looking responsive website as your project page or page for your repo? Are you in [a hackathon](http://baseballhackday.com) needing to put up a working website in minutes? I do. Here is what I do, and I am sharing for you to use it, free. Free as in free speach AND free beer.

You can see [the working example site here](http://daigofuji.github.io/jekyll-foundation-6-starter/)

### For User & Organization Pages
See [github documentation](https://help.github.com/articles/user-organization-and-project-pages/)

1. Fork or copy this repo to your user or project
2. From the `settings` rename the repo to `username.github.io` naming scheme.

### For Project Pages
See [github documentation](https://help.github.com/articles/user-organization-and-project-pages/#project-pages)

1. Create a `gh-pages` branch, i.e. `git checkout -b gh-pages`
2. [Download the contents of this repo](https://github.com/daigofuji/jekyll-foundation-6-starter/archive/master.zip)
3. Replace the entire branch contents with unzipped stuff
4. Add, Commit then Publish the branch to github, i.e. `git push --set-upstream origin gh-pages`

### To edit contents:
1. edit `_config.yml`
2. edit html/md files (`_layouts/default.html` is the base)
3. edit sass and run `grunt` (Try [editing `scss/_stettings.scss`](http://foundation.zurb.com/sites/docs/sass.html))
4. edit `_include/nav.html` 

Use at your own resk, and follw licence restriction of each products used. Most are MIT (OK to use commercially).

### Tools used, and useful commands

If you don't have it, install [node.js](https://nodejs.org/en/). Easyest way it to use [Homebrew](http://brew.sh/) by
  `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
then 
  `brew install node`
and install npm and gulp globally by running 
  `sudo npm install npm gulp -g`

Run gulp to compile css from sass by simply run `gulp` from your terminal within your repo. 
It will launch watch by default. <code>control-c</code> to stop. If you only want the css compiled once, run `gulp sass`

To run jekyll locally to test your website while developing, run  `bundle exec jekyll serve --watch` (requires ruby)

Your website should be viewable by going to [localhost:4000](http://localhost:4000/)

Github's doc on [how to use Jekyll on Github Pages](https://help.github.com/articles/using-jekyll-with-pages) is also helpful. 
