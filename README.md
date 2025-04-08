1. `buf generate --template libs/proto/buf.gen.yaml -o libs/proto` works fine
2. `buf generate --template services/service_a/buf.gen.yaml -o services/service_a` returns an error: protoc-gen-go: unable to determine Go import path for "common/types/v1/uuid.proto"
