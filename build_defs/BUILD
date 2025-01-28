
subinclude("///cc//build_defs:compilerPlugin")

filegroup(
    name = "gcc_file",
    srcs = ["gcc.build_defs"],
    visibility = [":gcc"]
)

compilerPlugin(
    name="gcc",
    include="///gcc//build_defs:gcc_file",
    compiler="getTranslationUnit(\"c\")",
    archiver="archive",
    linker="link"
)

compilerPlugin(
    name="gpp",
    include="///gcc//build_defs:gcc_file",
    compiler="getTranslationUnit(\"c++\")",
    archiver="archive",
    linker="link"
)