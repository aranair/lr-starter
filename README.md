# lr-starter
Skeleton for simple websites

## Installation

    bower install

    npm install

## Building

Make sure you have bower installed and npm installed.

`grunt build`

## Running locally

After building:

    cd public/

    python -m SimpleHTTPServer

    bro

## Validating html

`grunt validate`

## Deploying

Everything in public folder will be pushed to gh-pages and made live.

`grunt deploy`

## Setting new url

After cloning as a skeleton, create a new repository to push to.
Copy that new repository url and set it with grunt.

    grunt set_remote --url={new_url}

You can verify that the new url is set with `git remote -v`
