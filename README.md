Codecov Scala Example
=====================

1. Add `scoverage` to plugin list
  - `addSbtPlugin("org.scoverage" % "sbt-scoverage" % "1.3.5")` as [seen here](https://github.com/codecov/example-scala/blob/master/project/plugins.sbt#L1)
1. Add `coverage` and `coverageReport` to `sbt`
  - `sbt clean coverage test coverageReport` as [seen here](https://github.com/codecov/example-scala/blob/master/.travis.yml#L7)
1. After tests are complete add the Codecov uploader
  - `bash <(curl -s https://codecov.io/bash)` as [seen here](https://github.com/codecov/example-scala/blob/master/.travis.yml#L10)
  - Please provide your upload token. Learn more [here](http://docs.codecov.io/docs/about-the-codecov-bash-uploader#section-upload-token)

> Please contact support for questions and help :thumbsup: https://codecov.io/support

[1]: https://codecov.io/
[2]: https://twitter.com/codecov
[3]: mailto:hello@codecov.io
[4]: https://github.com/codecov/codecov-bash
