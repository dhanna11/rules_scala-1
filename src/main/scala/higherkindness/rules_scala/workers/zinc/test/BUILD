load("//rules:scala.bzl", "scala_library")
load("//rules:scalafmt.bzl", "scala_format_test")

scala_library(
    name = "test",
    srcs = glob(["**/*.scala"]),
    scala = "//src/main/scala:zinc",
    visibility = ["//visibility:public"],
    deps = [
        "//src/main/scala/higherkindness/rules_scala/common/args",
        "//src/main/scala/higherkindness/rules_scala/common/sbt-testing:common",
        "@scala_annex_com_trueaccord_scalapb_scalapb_runtime_2_12",
        "@scala_annex_net_sourceforge_argparse4j_argparse4j",
        "@scala_annex_org_scala_sbt_compiler_interface",
        "@scala_annex_org_scala_sbt_test_interface",
        "@scala_annex_org_scala_sbt_zinc_apiinfo_2_12",
        "@scala_annex_org_scala_sbt_zinc_core_2_12",
        "@scala_annex_org_scala_sbt_zinc_persist_2_12",
    ],
)

scala_format_test(
    name = "format",
    srcs = glob(["**/*.scala"]),
)
