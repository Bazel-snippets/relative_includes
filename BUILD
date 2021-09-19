load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "hello_world",
    srcs = [
        "hello_world.cpp",
        # Should be added to the list of srcs, but deliberately commented out to demo that Bazel does not complain about undeclared inclusion(s) in this case.
        # "@prop_msvc_toolchain//:all_files",
    ],
    includes = ["prop_msvc_toolchain"],
    nocopts = "/Z7",
)
