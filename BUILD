java_binary(
    name = "mavendeps",
    srcs = glob(["src/main/java/**/*.java"]),
    resources = glob(["src/main/resources/**"]),
    deps = [
        "@maven//:org_apache_logging_log4j_log4j_core",
        "@maven//:org_apache_logging_log4j_log4j_api"
    ],
    main_class = "ca.uwaterloo.cs489.mavendeps.Main"
)
