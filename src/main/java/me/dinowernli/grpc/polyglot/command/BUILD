package(default_visibility = ["//visibility:public"])

java_library(
  name = "command",
  srcs = glob(['*.java']),
  deps = [
    "//src/main/proto:config_proto",
    "//src/main/java/me/dinowernli/grpc/polyglot/grpc",
    "//src/main/java/me/dinowernli/grpc/polyglot/io",
    "//src/main/java/me/dinowernli/grpc/polyglot/oauth2",
    "//src/main/java/me/dinowernli/grpc/polyglot/protobuf",
    "//third_party/google-oauth",
    "//third_party/grpc",
    "//third_party/guava",
    "//third_party/logging:logging-api",
    "//third_party/protobuf",
  ],
)
