load("//tensorboard/defs:defs.bzl", "tf_ts_library")

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])  # Apache 2.0

tf_ts_library(
    name = "tf_dashboard_common",
    srcs = [
        "array-update-helper.ts",
        "dashboard-style.ts",
        "data-loader-behavior.ts",
        "run-color-style.ts",
        "scrollbar-style.ts",
        "tensorboard-color.ts",
        "tf-dashboard-layout.ts",
        "tf-downloader.ts",
        "tf-dropdown-trigger.ts",
        "tf-filterable-checkbox-dropdown.ts",
        "tf-filterable-checkbox-list.ts",
        "tf-multi-checkbox.ts",
        "tf-no-data-warning.ts",
        "tf-option-selector.ts",
    ],
    strict_checks = False,
    visibility = ["//visibility:public"],
    deps = [
        "//tensorboard/components_polymer3/polymer:irons_and_papers",
        "//tensorboard/components_polymer3/polymer:legacy_element_mixin",
        "//tensorboard/components_polymer3/polymer:paper_inky_focus_behavior",
        "//tensorboard/components_polymer3/polymer:register_style_dom_module",
        "//tensorboard/components_polymer3/polymer:utils_mixin",
        "//tensorboard/components_polymer3/tf_backend",
        "//tensorboard/components_polymer3/tf_color_scale",
        "//tensorboard/components_polymer3/tf_storage",
        "//tensorboard/components_polymer3/vz_sorting",
        "@npm//@polymer/decorators",
        "@npm//@polymer/polymer",
        "@npm//@types/d3",
        "@npm//@types/lodash",
        "@npm//d3",
        "@npm//lodash",
    ],
)
