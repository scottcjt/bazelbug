package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

filegroup(
    name = "runtime_py_srcs",
    srcs = glob(["python/**/*.py"]),
)

py_library(
    name = "runtime_py",
    srcs = ["runtime_py_srcs"],
    imports = ["python"],
)
