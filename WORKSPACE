load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "new_git_repository")

git_repository(
    name = "gtest",
    remote = "https://github.com/google/googletest.git",
    commit = "703bd9caab50b139428cea1aaff9974ebee5742e",
)

http_archive(
    name = "tacopie",
    sha256 = "bbdebecdb68d5f9eb64170217000daf844e0aee18b8c4d3dd373d07efd9f7316",
    strip_prefix = "tacopie-master",
    url = "https://github.com/cylix/tacopie/archive/master.zip",
)

# Note: You can use the submodule version of tacopie.
# Comment out tacopie rule above and use this rule instead.
#local_repository(
#    name = "tacopie",
#    path = "/absolute/path/to/tacopie",
#)
