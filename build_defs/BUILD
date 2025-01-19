
subinclude("///cc//build_defs:compilerPlugin")

filegroup(
    name = "gcc_file",
    srcs = ["gcc.build_defs"],
    visibility = [":gcc"]
)

compilerPlugin(
    name="gcc",
    include="///gcc//build_defs:gcc_file",
    compiler="translationUnit",
    archiver="archive",
    linker="link"
)
