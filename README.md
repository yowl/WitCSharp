# C# Wit Bindgen

## Code gen in Rust or C#?

### Rust :

#### Pro:

- Implementation more complete.
- Can run wit-bindgen tests easily
- PRs get feedback from main wit-bindgen team (maybe 😊 )
- Breaking changes in API force developer to fix C#

#### Cons:

- Not natural to attract more c# developers
- Tooling for creating c# source code maybe not as good as from C#

### C#

#### Pro:

- Easier for newcomers
- More control over implementation – no need for approval from main wit-bindgen maintainers
- Better tooling for creating C# source code, maybe

#### Cons:

- Implementation is considerably less complete.
- If the codegen API changes we have to catchup

## Target Runtime

Feeling that we need to develop for both mono and NativeAOT (NativeAOT-LLVM). Are we supporting Mono Interpreter or Mint?

## Deployment model MSBuild Task or CLI or both. (VSIX?)

## Future:

WASI Workload?
