# GraalVM Buildpack

This [buildpack](https://devcenter.heroku.com/articles/buildpacks) will install the [GraalVM](https://github.com/oracle/graal) Community Edition 20.2.0 for Java 11. Originally forked from https://github.com/jkutner/graal-buildpack

!! NOT YET TESTED !!

## Usage

This buildpack can be used with the [Heroku Java buildpack](https://github.com/heroku/heroku-buildpack-java/blob/master/bin/compile) to replace the default JDK by running:

```
$ heroku buildpacks:set https://github.com/windflow-io/graal-buildpack
$ heroku buildpacks:add heroku/java
```

## License

MIT
