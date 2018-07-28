android_library(
  name = "activities",
  srcs = glob(["src/main/java/com/google/bazel/example/android/activities/*.java"]),
  custom_package = "com.google.bazel.example.android.activities",
  manifest = "src/main/java/com/google/bazel/example/android/activities/AndroidManifest.xml",
  resource_files = glob(["src/main/java/com/google/bazel/example/android/activities/res/**"]),
)

android_binary(
    name = "android",
    custom_package = "com.google.bazel.example.android",
    manifest = "src/main/java/com/google/bazel/example/android/AndroidManifest.xml",
    resource_files = glob(["src/main/java/com/google/bazel/example/android/res/**"]),
    deps = [":activities"],
)