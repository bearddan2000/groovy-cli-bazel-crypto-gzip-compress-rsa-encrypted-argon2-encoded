load("@io_bazel_rules_groovy//groovy:groovy.bzl", "groovy_binary")

groovy_binary (
    name = "BazelApp",
    srcs = glob(["groovy/**/*.groovy"]),
    main_class = "example.Main",
    deps = [
      "@maven//:de_mkammerer_argon2_jvm",
      "@maven//:javax_xml_bind_jaxb_api",
    ],
)
