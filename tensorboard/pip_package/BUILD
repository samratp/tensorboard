# Description:
#  Tools for building the TensorFlow pip package.

package(default_visibility = ["//visibility:private"])

licenses(["notice"])  # Apache 2.0

sh_binary(
    name = "build_pip_package",
    srcs = ["build_pip_package.sh"],
    data = [
        "LICENSE",
        "MANIFEST.in",
        "README.rst",
        "setup.cfg",
        "setup.py",
        "//tensorboard",
        "//tensorboard:lib",
        "//tensorboard:version",
    ],
)
