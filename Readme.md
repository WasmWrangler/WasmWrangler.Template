[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Build Status](https://github.com/WasmWrangler/WasmWrangler.Template/workflows/CI/badge.svg)](https://github.com/WasmWrangler/WasmWrangler.Template/actions)

# WasmWrangler Template

A template project for getting started with WasmWrangler.

## Building

Due to what I what I think is a bug you may have to call restore directly on the project one time:

```
dotnet restore WasmWrangler.Template.csproj
```

Just calling `dotnet restore` or calling restore on the `sln` file will not trigger the downloading of
the Mono WASM SDK.

## Launching

Right now the template is using `dotnet-serve` to serve the output. You can install `dotnet-serve` with the
following command:

```
dotnet tool install -g dotnet-serve
```

