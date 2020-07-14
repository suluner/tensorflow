load(
    "//tensorflow/core/platform:rules_cc.bzl",
    "cc_library",
)

package(
    default_visibility = [
        "//tensorflow:__subpackages__",
    ],
    licenses = ["notice"],  # Apache 2.0
)

filegroup(
    name = "cuckoohash_all_headers",
    srcs = [
        "cuckoohash_config.hh",
        "cuckoohash_map.hh",
        "cuckoohash_util.hh",
        "libcuckoo_bucket_container.hh",
    ],
    visibility = ["//tensorflow/core:__pkg__"],
)
