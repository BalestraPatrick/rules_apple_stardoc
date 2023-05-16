load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "build_bazel_rules_apple",
    strip_prefix = "rules_apple-12291c642c3fd8d764400a98f35efe15de9d2800",
    url = "https://github.com/BalestraPatrick/rules_apple/archive/12291c642c3fd8d764400a98f35efe15de9d2800.tar.gz",
)

load(
    "@build_bazel_rules_apple//apple:repositories.bzl",
    "apple_rules_dependencies",
)

apple_rules_dependencies()

load(
    "@build_bazel_rules_swift//swift:repositories.bzl",
    "swift_rules_dependencies",
)

swift_rules_dependencies()

load(
    "@build_bazel_rules_swift//swift:extras.bzl",
    "swift_rules_extra_dependencies",
)

swift_rules_extra_dependencies()

load(
    "@build_bazel_apple_support//lib:repositories.bzl",
    "apple_support_dependencies",
)

apple_support_dependencies()

http_archive(
    name = "io_bazel_stardoc",
    strip_prefix = "stardoc-4d5b5dae64af3b445c73612e09371a6c0e7fd4fd",
    urls = ["https://github.com/bazelbuild/stardoc/archive/4d5b5dae64af3b445c73612e09371a6c0e7fd4fd.tar.gz"],
)
