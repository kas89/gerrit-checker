load("//tools/bzl:plugin.bzl", "gerrit_plugin")

gerrit_plugin(
    name = "checker",
    srcs = glob(["src/main/java/**/*.java"]),
    manifest_entries = [
        "Gerrit-PluginName: checker",
    ],
    resources = glob(["src/main/resources/**/*"]),
)
