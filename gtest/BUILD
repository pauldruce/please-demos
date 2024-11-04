github_repo(
    name = "gtest",
    bazel_compat = True,
    repo = "google/googletest",
    revision = "v1.15.0",
)

cc_library(
    name = "main",
    visibility = ["PUBLIC"],
    deps = [
        "///gtest/gtest//:gtest_main",
    ],
)

github_repo(
    name = "gtest-1.8.2",
    bazel_compat = True,
    repo = "google/googletest",
    revision = "release-1.8.1",
)