# Simple Jekyll Template

This is just a simple template you can use with Jekyll. It doesn't rely on any theme and it is based on the Jekyll step by step tutorial you can find [here](https://jekyllrb.com/docs/step-by-step/01-setup/).


## How to use

Just clone the repository and run one of the following commands to build the site:


    jekyll build

Builds the site and outputs a static site to a directory called `_site`.

    jekyll serve

Does the same thing except it rebuilds any time you make a change and runs a local web server at `http://localhost:4000`

## Deployment

The most basic way to do this is to run a production build:

    JEKYLL_ENV=production bundle exec jekyll build

And copy the contents of `_site` to your server.
