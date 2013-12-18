# heroku-buildpack-ossl

This builds a Heroku instance with default ruby version (ruby-2.0.0)

## Use with enricheers/heroku-buildpack-multi

    $ heroku config:set BUILDPACK_URL=https://github.com/enricheers/heroku-buildpack-multi

    $ cat .buildpacks
    https://github.com/enricheers/heroku-buildpack-ruby.git
    https://github.com/enricheers/heroku-buildpack-ossl.git
