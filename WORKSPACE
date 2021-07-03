load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "io_bazel_rules_kotlin",
    sha256 =
"6194a864280e1989b6d8118a4aee03bb50edeeae4076e5bc30eef8a98dcd4f07",
    urls =
["https://github.com/bazelbuild/rules_kotlin/releases/download/v1.5.0-alpha-2/rules_kotlin_release.tgz"],
)
load("@io_bazel_rules_kotlin//kotlin:dependencies.bzl",
"kt_download_local_dev_dependencies")
load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kotlin_repositories",
"kt_register_toolchains")
kt_download_local_dev_dependencies()
kotlin_repositories()
kt_register_toolchains()

