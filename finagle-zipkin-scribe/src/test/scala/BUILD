junit_tests(
    sources = ["**/*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    dependencies = [
        "3rdparty/jvm/junit",
        "3rdparty/jvm/org/mockito:mockito-all",
        "3rdparty/jvm/org/scalacheck",
        "3rdparty/jvm/org/scalatest",
        "finagle/finagle-core/src/main",
        "finagle/finagle-thrift/src/main/thrift:scribe",
        "finagle/finagle-zipkin-core/src/main/scala",
        "finagle/finagle-zipkin-scribe",
        "scrooge/scrooge-core/src/main/scala",
        "util/util-core:scala",
        "util/util-stats/src/main/scala",
    ],
)
