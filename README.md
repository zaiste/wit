# wit

A set of shell scripts that make Git experience slightly better.

## Installation

Make sure you have [cURL][1] and [jq][2] installed.

    git clone https://github.com/zaiste/wit.git ~/.wit
    export PATH=$HOME/.wit:$PATH  # add it to your profile

## Usage

Authenticate on GitHub

    git auth

Show information about authenticated user

    git me

Issue a pull request

    git req [pull request title]

## Configuration

Configuration is stored in `~/.wit/auth_token`.


[1]: http://curl.haxx.se/
[2]: http://stedolan.github.io/jq/
