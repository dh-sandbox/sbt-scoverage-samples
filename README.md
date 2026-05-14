
[![Maintainability](https://qlty.sh/gh/dh-sandbox/projects/sbt-scoverage-samples/maintainability.svg)](https://qlty.sh/gh/dh-sandbox/projects/sbt-scoverage-samples)
[![Code Coverage](https://qlty.sh/gh/dh-sandbox/projects/sbt-scoverage-samples/coverage.svg)](https://qlty.sh/gh/dh-sandbox/projects/sbt-scoverage-samples)

# scoverage samples

A sample program for demonstrating scoverage's code coverage. This
sample is an akka based mock quote engine.

Note: This project deliberately doesn't have 100% coverage for
demonstration purposes.

To create a report you need to run ...

```bash
sbt coverage +test +coverageReport
```

Note: This project builds agains Scala2 **and** Scala3.

Afterwards you can find the report in ...

```
./target/scala-2.13/scoverage-report/index.html
./target/scala-3.3.2-RC1/scoverage-report/index.html
```


