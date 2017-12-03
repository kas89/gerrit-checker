load("//tools/bzl:plugin.bzl", "gerrit_plugin")

gerrit_plugin(
    name = "checker",
    srcs = glob(["src/main/java/**/*.java"]),
    manifest_entries = [
        "Gerrit-PluginName: checker",
        "Gerrit-SshModule: com.googlesource.gerrit.plugins.checker.SshModule",
        "Gerrit-Module: com.googlesource.gerrit.plugins.checker.Module",
    ],
    resources = glob(["src/main/resources/**/*"]),
)
