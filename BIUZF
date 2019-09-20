cc_library(
    name = "dwm_driver",
    srcs = glob(["dwm_driver/**/*.c", "platform/x86/hal/*.c"]),
    hdrs = glob(["include/*.h", "platform/x86/hal/*.h", "dwm_driver/**/*.h"]),
    copts = [
      "-Iexternal/dwm_driver/include",
      "-Iexternal/dwm_driver/platform/x86/hal",
      "-Iinclude",
      "-Iplatform/x86/hal",
    ],
    visibility = ["//visibility:public"],

)
