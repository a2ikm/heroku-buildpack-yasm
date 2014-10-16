Heroku Buildpack: yasm
======================

This is a Heroku Buildpack to use [yasm](http://yasm.tortall.net/).


Usage
-----

With [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi),

```
$ heroku config:add BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git

$ cat .buildpacks
https://github.com/heroku/heroku-buildpack-ruby.git
https://github.com/a2ikm/heroku-buildpack-yasm.git
```
