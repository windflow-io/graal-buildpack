# GraalVM Buildpack

This [buildpack](https://devcenter.heroku.com/articles/buildpacks) will install the [GraalVM](https://github.com/oracle/graal) Community Edition. Originally forked from https://github.com/jkutner/graal-buildpack

## Usage

This buildpack can be used with the [Heroku Java buildpack](https://github.com/heroku/heroku-buildpack-java/blob/master/bin/compile) to replace the default JDK by running:

```
$ heroku buildpacks:set https://github.com/windflow-io/graal-buildpack
$ heroku buildpacks:add heroku/java
```

## License

MIT
