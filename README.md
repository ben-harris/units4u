# units4u
a university unit recommender system for the web research unit

[![Build Status](https://travis-ci.org/zaccolley/units4u.svg?branch=master)](https://travis-ci.org/zaccolley/units4u)

# install

most of this project will be using node so you'll need to install any dependencies. we're using eslint to lint the project.

make sure you're using a **node version 4 or above** for es6 (es2015) features

1. `npm install -g eslint`
2. `npm install`
3. Install neo4j
4. copy the `.env-sample file` to `.env` and add details (username and password for neo4j, [indeed api publisher api key](http://www.indeed.co.uk/publisher)).

## neo4j

you'll need to [download and install neo4j (community edition)](http://neo4j.com/download/).

run the `app/dbSeed.js` file to seed some initial MerlinMade:tm: data

# run

1. `npm start`

# code styleguide

we're using [EditorConfig](http://editorconfig.org) to set-up our coding style, you can [install a plugin for this to take effect](http://editorconfig.org/#download)

_e.g for atom `apm install editorconfig`_

our linter will also pick up things like this as well

# linting

linting is done with eslint, you can install it your ide. running `npm run lint` will run the linter command line.

# /experiments

section for experiment with our different tech and algorithms

# /resources

currently we're using this folder to dump data that'll we'll process in the future
