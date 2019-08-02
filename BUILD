cc_library (
    name = "Box2D",
    hdrs = ["Box2D.h",],
    deps = [
        ":Box2Dlib",
    ],
    visibility = ["//visibility:public"],
)


cc_library (
    name = "Box2Dlib",
    hdrs = glob([
        "Common/**/*.h", 
        "Collision/**/*.h",
        "Dynamics/**/*.h",
        "Rope/**/*.h",
    ]),
    srcs = glob([
        "Common/**/*.cpp", 
        "Collision/**/*.cpp",
        "Dynamics/**/*.cpp",
        "Rope/**/*.cpp",
    ]),
)
