load("@build_bazel_rules_swift//swift:swift.bzl", "swift_binary")

swift_binary(
    name = "xcbeautify",
    srcs = glob([
        "*.swift",
    ]),
    copts = [
        "-whole-module-optimization",
    ],
    deps = [
        "//Sources/XcbeautifyLib",
    ],
)
