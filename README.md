Minimal reproduction of the following error, hit after upgrading to scalafmt
syntax 3.5.0

```scala
> scalafmtCheckAll
[info] scalafmt: Checking 1 Scala sources (/home/sf/scratch/scalafmterr)...
[error] stack trace is suppressed; run last Compile / scalafmtCheck for the full output
[error] (Compile / scalafmtCheck) org.scalafmt.sbt.ScalafmtSbtReporter$ScalafmtSbtError: scalafmt: Missing token index [63:64]: `
[error] ` [/home/sf/scratch/scalafmterr/src/main/scala/example/scalafmterr.scala]
[error] Total time: 0 s, completed Apr 11, 2022, 1:35:10 PM
```

