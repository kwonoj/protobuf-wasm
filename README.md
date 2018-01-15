# protobuf-wasm

This repo contains small set of patches to protobuf (3.5.1.1) to build protobuf via [emscripten](https://github.com/kripken/emscripten). Simply apply all patches to protobuf source code, then run emcc. If you'd like to check example build, there is [docker image] (https://github.com/kwonoj/docker-arch-emscripten/blob/master/Dockerfile)

`protoc` compiler will not be built but any code generate by the standard protoc is compatible with emscripten.

This patches are based on prior work of https://github.com/invokr/protobuf-emscripten and follows same license.