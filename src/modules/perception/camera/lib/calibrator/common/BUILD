load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "histogram_estimator",
    srcs = ["histogram_estimator.cc"],
    hdrs = ["histogram_estimator.h"],
    deps = [
        "//cyber",
        "//kernels/perception/common/i_lib/core",
        "@eigen",
    ],
)

cpplint()
